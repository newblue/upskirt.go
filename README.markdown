###Upskirt.Go

>A wrapper around Upskirt with Cgo to expose one simple Markdown-to-HTML function for Go (golang)

>Upskirt repository: https://github.com/tanoku/upskirt

1. Install Go
2. `./update.sh` (optional; updates Upskirt code to latest version)
3. `make`
4. `sudo make install`
5. ???
6. Profit!

---

The package name is `upskirt`.

The only function provided in this package is `Markdownify (string) string`, which takes a string of Markdown and returns a string of HTML.

---

For example usage, see `example.go`.

---

Because Upskirt is used at GitHub, the format is GitHub-Flavoured Markdown; see: http://github.github.com/github-flavored-markdown/

SmartyPants extensions are enabled; see: http://daringfireball.net/projects/smartypants/

---

Upskirt.Go was created on 2011-05-24 by Ryan Lester for use at Rewaved Corporation.
