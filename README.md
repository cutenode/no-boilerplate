# No Boilerplate

I often have the urge to create websites that serve a single purpose. That often to simply assert one word: No.

No boilerplate is a simple, no boilerplate HTML boilerplate that allows you to ship a GitHub pages site to answer a yes/no question super quickly. Clone it, update your GitHub repo's GitHub Pages and Custom Domain settings as appropriate, and ship it.

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
