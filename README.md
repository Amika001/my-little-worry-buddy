# My Little Worry Buddy

A free, static Persian-language web app for GitHub Pages. No paid API, backend, account, or external dependency is required.

## Publish on GitHub Pages
1. Create a public GitHub repository, for example `my-little-worry-buddy`.
2. Upload `index.html` (and optionally this README) to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. The URL will be shown in Settings → Pages.

## What works without APIs
- Four-step questionnaire.
- Personalized result text and a locally rendered SVG character.
- Downloadable PNG result card generated in the browser.
- Copyable English image-generation prompt for use in an image tool of the user's choice.

## Important limitation
The app does not call an AI image-generation service. The character illustration and result card are generated locally in the browser, so the experience is free and does not require API keys. To get a photorealistic or more elaborate AI-generated image, the user can copy the prompt and use an image tool separately; free usage limits depend on that provider.
