<html>
<head>
</head>

# Purpose of this repo

The purpose of this repo is to test markdown / html features in markdown
documents. Initially this was made to try and get umlauts and other diacritics
to work with GitHub but it's been expanded for other tests as well. It seems in
this repo umlauts do work but in another they do not in all cases. 

Using `rdiscount` locally when trying to centre links it just shows the raw
markdown rather than the html. This appears to be a markdown limitation itself
if the GitHub failure to do this as well is a valid indication (which it seems
to be).

Progress / additional tests will be made in time depending on other things going
on and if any tests need to be made. As I discover what works and what does not
I'll update the sections below on what's known not work and what is known to
work.

## What's known so far to _NOT_ work

The following does _**NOT**_ work:

- Centred links in the markdown style (`<a>` does work).
    * For instance having `<div align="center">This [README.md](README.md) link
    should be centred but it isn't.</div>` will show the markdown literally in
    the centre; that is the text itself is centred but the link is not. One
    _**can**_ have links centred using `<a`>.

- Certain html elements like `<title>`. At this time the only one I know not to
work is in fact `<title>` but others do. For instance: `<title>Test html and
markdown in GitHub rendered pages</title>` shows that text literally on the
rendered document.

## Current tests


## The below are all known to work:

### Umlauts

Some example umlauts

ä ë ö ü

### Accents

Some example accents.

á ó ý

### Others

Do German snakes go ßßßßßßßßßßßßßßßßßßßßßßßßß?


### HTML elements / tags

Test links being centred if using `<a>` anchors:

<div align="center"><a href="README.md">README.md link</a></div>

Most other html tags / elements are known to work as well.

</html>
