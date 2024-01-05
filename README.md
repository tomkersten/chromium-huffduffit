# Huffduffit - When a bookmarklet just won't suffice

This is a very basic Chrome extension that replaces the functionaly the
[HuffduffIt!][hdi] suggested bookmarklet offers.

# Why?

With the [declining investment (and market share)][ff] of Firefox, I migrated
to [Arc browser][arc]. For whatever reason, the [bookmarklet didn't seem to work
in Arc][arc-bm].

# How was it created?

As per [a comment][arc-bm] in [the Reddit thread linked above][arc-bm], I used
the ["bookmarklet-to-extension" tool][bm2e], but it was using an outdated Chrome
extension manifest version (v2). I upgraded it to be compatible with the current
Chrome extension manifest format and thought others maybe be in a similar situation.

# How to use it?

1. Clone this repository.
1. [Load the directory as an "unpacked extension"][load-ext].

## Note

I've only tested this in [Arc][arc]. PRs are welcome.

# Thanks to...

- [Peter Legierski][pl] for the [tool that did the initial conversion][pl-tool]. Although
  it's very simple, with no Chrome extension experience, I would not have even looked into
  it had this not made the first version/step in the process so easy.
- [Jeremy Keith][jk] for creating Huffduffer. I love it and use it frequently.

# License

See [LICENSE](./LICENSE) file (tl;dr: it's MIT).

[arc]: https://arc.net/
[arc-bm]: https://www.reddit.com/r/ArcBrowser/comments/118ggqt/get_bookmarklets_to_work/
[arc-bmc]: https://www.reddit.com/r/ArcBrowser/comments/118ggqt/comment/j9irv84/
[bm2e]: https://sandbox.self.li/bookmarklet-to-extension/
[hdi]: https://huffduffer.com/add
[ff]: https://huffduffer.com/add
[pl]: https://blog.self.li/post/16366939413/how-to-convert-bookmarklet-to-chrome-extension
[pl-tool]: https://sandbox.self.li/bookmarklet-to-extension/
[load-ext]: https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#load-unpacked
[jk]: https://adactio.com/
