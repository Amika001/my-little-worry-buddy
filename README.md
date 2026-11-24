# My Little Worry Buddy

A free, static Persian-language experience for GitHub Pages. No paid API, backend, account, or external dependency is required by the website.

## Publish on GitHub Pages
1. Upload `index.html` and `README.md` to the root of a public repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site.

## How it works
- Three short questions collect a user's worry, when it becomes more noticeable, and an optional unspoken thought.
- The browser builds a detailed, personalized creative prompt locally.
- The user copies the prompt and opens ChatGPT to generate the original character image and its story.
- No answers are sent to this website's server; this is a static page.

## Important limitation
The site itself does not generate AI images. Image generation happens in ChatGPT after the user pastes the prompt. ChatGPT account access and free image-generation limits may apply.
