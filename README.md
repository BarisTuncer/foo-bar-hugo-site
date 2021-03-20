
# How to deploy your Hugo project vith Netlify

Sample project (which has been created by hugo) to show how to deploy webpage on netlify

Results can be seen at: https://foobar-hugo-site.netlify.app/

You may want to watch: https://www.youtube.com/watch?v=gSiAcyTWU3c

## Thing to note:

1. Add the theme via `git remote add origin https://github.com/BarisTuncer/foo-bar-hugo-site.git`
2. In `config.toml` add `theme = "ace-documentation"` and `baseURL = "/"`
3. In the `Domain management` section of `Netlify` change the name of the deployment: In this case it is `foobar-hugo-site.netlify.app`
4. It's good to add `public/` to `.gitignore`

This way each time you make a change, results of the page will be updated via `Netlify`

