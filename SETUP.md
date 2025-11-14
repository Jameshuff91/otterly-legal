# Setting Up GitHub Pages

To make your privacy policy publicly accessible, follow these steps:

## Enable GitHub Pages

1. Go to your repository: https://github.com/Jameshuff91/otterly-legal
2. Click on **Settings** (top menu)
3. In the left sidebar, scroll down and click **Pages**
4. Under "Source", select:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Click **Save**

## Accessing Your Privacy Policy

After enabling GitHub Pages (it may take a few minutes to deploy), your privacy policy will be available at:

**https://jameshuff91.github.io/otterly-legal/privacy.html**

## Using in Your App

You can now use this URL in:
- Your app's settings screen
- App store listings (Google Play, App Store)
- Google Firebase configuration
- Any other service that requires a privacy policy URL

## Custom Domain (Optional)

If you want to use a custom domain like `legal.otterly.app`:

1. In GitHub Pages settings, add your custom domain
2. Create a CNAME file in the repository root with your domain
3. Configure DNS with your domain provider:
   - Add a CNAME record pointing to `jameshuff91.github.io`
