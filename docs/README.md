# List2Buy Documentation Site

This folder contains the GitHub Pages site for List2Buy app verification and documentation.

## Files

- `index.html` - Main documentation page
- `app-ads.txt` - AdMob verification file (required for Google AdMob)

## GitHub Pages Setup

To enable GitHub Pages for this repository:

1. Go to the repository Settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/docs" folder
5. Click "Save"

The site will be available at: `https://treetoptech.github.io`

## app-ads.txt

The `app-ads.txt` file authorizes Google AdMob to serve ads in the List2Buy Android app. It contains:

```
google.com, pub-8211927262245490, DIRECT, f08c47fec0942fa0
```

This follows the IAB Tech Lab app-ads.txt specification format:
- `google.com` - Exchange domain
- `pub-8211927262245490` - Publisher ID (from AdMob account)
- `DIRECT` - Direct relationship indicator
- `f08c47fec0942fa0` - Google's certification authority ID