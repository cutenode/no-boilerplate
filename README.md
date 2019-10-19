# No Boilerplate

I often have the urge to create websites that serve a single purpose. That often to simply assert one word: No.

No boilerplate is a simple, no boilerplate HTML boilerplate that allows you to ship a GitHub pages site to answer a yes/no question super quickly.

## Usage

**Step One:**

Clone the repo.

```bash
$ git clone git@github.com:cutenode/no-boilerplate.git <path to directory you want to put it in>

# For example:
#
# git clone git@github.com:cutenode/no-boilerplate.git amiareal.dev
# The above command will put it in the directory named amiareal.dev
```

**Step Two:**

Update the git origin to your project's Git Repo. Now's a good time to make any changes to the site if you'd like to!

```bash
$ git remote rm origin
$ git remote add origin git@github.com:<ORG OR USER>/<REPO>.git
$ git push

# Make sure you update the second command as appropriately. For example, I used this for amiareal.dev:
#
# $ git remote add origin git@github.com:cutenode/amiareal.dev.git
```

**Step Three:**

Follow the guidance provided by GitHub to publish with GitHub Pages ([About GitHub Pages](https://help.github.com/en/articles/about-github-pages), [Configuring a Custom Domain for your GitHub Pages Site](https://help.github.com/en/articles/configuring-a-custom-domain-for-your-github-pages-site)), or use your preferred static site host.

One good thing to note here is that you should use the `master` branch as a source for your GitHub Pages.

**Step Four:**

Ship it 🚢

## Optional tweaks

### Change "No" to "Yes"

By editing `index.html`, you can change the default "No" to "Yes"... or something else if you want to, I guess.

### Change or Remove the Hidden Message

There's a hidden message that can be seen if the user scrolls. Pretty generic for this kind of site. I like having added nice bits, and it was less work to copy/paste the HTML and CSS for the H1 and tweak it to be an H2 than it was to make it so they could display on the same page... so the universe just kinda worked things out pretty neatly for me.

If you want to tweak the hidden message, you can do so in `index.html`.

If you want to remove the hidden message, you can do so in `index.html`. Additionally, I'd request that you remove the excess lines of CSS in `index.css` to maybe increase load times by less than 1ms for your users.

### Change the Font

I spent a few minutes looking for a nice font on Google Fonts. If you want to change the font, you'll need to update the second `<link>` tag in `index.html` and the font family on the `h1` and `h2` elements in `index.css`.

## Contributing

This repo has a [Code of Conduct](./CODE_OF_CONDUCT.md). Follow it.

Contributions to enhance the repository are more than welcome. I can't guarantee how responsive I'll be to PRs since I have a pretty overwhelming inbox of PRs on projects, but if you don't hear back from me on something feel free to [DM me on Twitter](https://twitter.com/bitandbang) – I'll almost certainly respond to that and take some time to review your PR.

If you want to contribute anything that would invalidate the name – No Boilerplate – please reconsider and don't spend your time on something that probably won't be merged.
