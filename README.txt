 Here's how to get your Google OAuth Client ID:

 Step 1: Go to Google Cloud Console
 1. Visit https://console.cloud.google.com/
 2. Create a new project (or select existing)

 Step 2: Enable Google+ / Google Identity API
 1. Go to APIs & Services → Library
 2. Search for "Google+ API" or "Google Identity Services"
 3. Click Enable

 Step 3: Configure OAuth Consent Screen
 1. Go to APIs & Services → OAuth consent screen
 2. Choose External
 3. Fill in:
     - App name: "Login with Google POC"
     - User support email: your email
     - Developer contact: your email
 4. Click Save and continue (skip scopes for now)

 Step 4: Create Credentials
 1. Go to APIs & Services → Credentials
 2. Click Create Credentials → OAuth client ID
 3. Application type: Web application
 4. Add authorized JavaScript origins:
     - http://localhost:8000 (for local testing)
 5. Add authorized redirect URIs:
     - http://localhost:8000 (or wherever you host it)
 6. Click Create
 7. Copy the Client ID

759460576260-mismtigeeh3435ehnkjnhrglpvhs7qg1.apps.googleusercontent.com




 Step 5: Update the code
 Replace YOUR_GOOGLE_CLIENT_ID.apps.goog leusercontent.com in index.html with your actual Client ID.
