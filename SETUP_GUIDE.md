# Setup Guide for Ashley's Drive Time

## Step 1: Get Your Own API Key (Important!)

The current API key in the file is mine and should be replaced with your own.

1. Go to: https://console.cloud.google.com/
2. Sign in with your Google account
3. Click "Create Project" (top bar) → Name it "Ashleys Drive Time"
4. Wait for project to be created

## Step 2: Enable Required APIs

1. In the left menu: "APIs & Services" → "Library"
2. Search for "Maps JavaScript API" → Click it → Enable
3. Search for "Distance Matrix API" → Click it → Enable  
4. Search for "Directions API" → Click it → Enable

## Step 3: Create Your API Key

1. Left menu: "APIs & Services" → "Credentials"
2. Top bar: "+ CREATE CREDENTIALS" → "API key"
3. Copy the key that appears (looks like: AIzaSy...)
4. Click "CLOSE"

## Step 4: (Optional but Recommended) Restrict Your Key

1. Click the pencil icon next to your new key
2. Under "API restrictions" → Select "Restrict key"
3. Check these boxes:
   - Maps JavaScript API
   - Distance Matrix API
   - Directions API
4. Click "SAVE" at bottom

## Step 5: Add Key to Your App

1. Open `index.html` in a text editor (Notepad, TextEdit, VS Code, etc.)
2. Find line 399 or search for: `const API_KEY = 'AIza`
3. Replace the key between quotes with YOUR new key
4. Save the file

## Step 6: Test It!

1. Double-click `index.html` to open in browser
2. Enter two addresses
3. Click "Calculate Arrival Time"
4. Should work! 🎉

## Troubleshooting

**"API key not valid"**
- Make sure you enabled all 3 APIs
- Wait 2-5 minutes for APIs to activate
- Check you copied the entire key

**"Request denied"**  
- Make sure all 3 APIs are enabled
- Check API restrictions (if you set them)

**Page shows code instead of app**
- Open in a web browser, not a text editor
- Try different browser (Chrome, Firefox, Safari)

## Cost

Google gives you **$200 FREE per month** which covers about 40,000 route calculations. For personal use, you'll never pay anything!

You can set spending limits in Google Cloud Console if you want to be extra safe.

---

Need help? Check the full README.md file!
