# carlejlers.com

Forwards every visit on carlejlers.com to the portfolio on
[carlejlers.dk](https://www.carlejlers.dk), keeping the path.

GitHub Pages serves one custom domain per site and the portfolio
(`ejlers/ejlers.github.io`) already uses carlejlers.dk, so the .com gets this
small site of its own.

- `index.html` forwards the front page.
- `404.html` is a copy of it; Pages serves it for every other path, so deep
  links are forwarded too. Keep the two files identical.
- `CNAME` tells Pages this site answers on carlejlers.com.
- `.nojekyll` skips the build step; the files are served as they are.

Pages setting: deploy from the `main` branch, root folder.
