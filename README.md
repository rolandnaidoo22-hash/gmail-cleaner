# Gmail Cleaner

A private Gmail cleanup tool, published on GitHub Pages.

Live site: https://gmail.rolpris.com

The app talks only to Google from your browser. You paste your own Google Cloud client ID on first use.

If sign-in fails after the move, add these to your OAuth client's Web application settings in Google Cloud Console:

- Authorised JavaScript origins: `https://gmail.rolpris.com`
- Authorised redirect URIs: `https://gmail.rolpris.com/`
