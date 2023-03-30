<html>
<head>
</head>

# Purpose of this repo

The purpose of this repo is to test getting umlauts and other diacritics to work
with GitHub markdown files - as well as other funny things noticed. It seems
that in this repo umlauts do work but in another they do not in all cases. 

Meanwhile using `rdiscount` locally at least when trying to centre links it just
shows the raw markdown rather than the html. Maybe it's `rdiscount` or maybe
it's the way markdown works.

Progress might or might not be made and this might or might not be worked on at
different times depending on other things going on.

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


## The below are all known to work:

### Umlauts

Some example umlauts

ä ë ö ü

### Accents

Some example accents.

á ó ý

### Others

Do German snakes go ßßßßßßßßßßßßßßßßßßßßßßßßß?

### Links


### HTML tags

Test links being centred if using `<a>` anchors:

<div align="center"><a href="README.md">README.md link</a></div>

</html>
