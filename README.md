# Random Number Generator

A simple, single-page random number generator. Enter a lower and upper limit, choose integer or decimal, and generate.

## Features

- Lower and upper limit inputs (both inclusive for integers)
- **Integer** (default) or **With decimal** output
- Adjustable decimal places (1 to 10, default 2)
- Input validation with clear error messages
- Uses the browser's `crypto.getRandomValues` for uniform randomness
- Responsive layout with automatic light and dark mode
- No dependencies, no build step: one `index.html` file

## Usage

1. Open `index.html` in any modern browser, or visit the hosted page.
2. Enter the **Lower limit** and **Upper limit**.
3. Pick **Integer** or **With decimal** (and set the decimal places if needed).
4. Click **Generate** or press Enter.

### Notes

- If the lower limit is greater than the upper limit, an error is shown.
- In integer mode, decimal limits are narrowed to the whole numbers between them. For example, 1.2 to 3.8 can return 2 or 3.

## Deploy to GitHub Pages

1. Put `index.html` in the root of your repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set the source to **Deploy from a branch**, then choose your main branch and the `/ (root)` folder.
4. Save. The site will be available at `https://<your-username>.github.io/<repo-name>/`.

## License

Released under the [MIT License](LICENSE).
