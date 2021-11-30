# Sublime PDML

[![Package Version][Package badge]][Package link]&nbsp;
[![ST Version][ST badge]][ST Link]&nbsp;
[![MIT License][License badge]][MIT License]&nbsp;
[![Build Status][Travis badge]][Travis link]

[Sublime Text] syntax support for [Christian Neumanns]'s [PDML] (Practical Data and Markup Language), the world's simplest text format to store data and markup code.

- https://github.com/tajmone/Sublime-PDML

Package created by [Tristano Ajmone], 2021/11/27, released under the [MIT License].

-----

**Table of Contents**

<!-- MarkdownTOC autolink="true" bracket="round" autoanchor="false" lowercase="only_ascii" uri_encoding="true" levels="1,2,3" -->

- [Package Info](#package-info)
- [Features](#features)
- [License](#license)
- [Links](#links)

<!-- /MarkdownTOC -->

-----

# Package Info

Sublime PDML adds syntax support for [Basic PDML], which is automatically associated with the `.pdml` file extension.

In the future, the package will also support upcoming official [PDML extensions], through [syntax inheritance], which is why this package is marked as requiring ST4, and also the reason why the Basic PDML syntax was kept minimal.

There also plans to add plug-ins to serialize from JSON, YAML and XML to PDML, and vice versa.

Contributions are welcome.


# Features

- [Basic PDML] syntax support:
    + File extension: `.pdml`.
- Mandatory PDML settings:
    + UTF-8 encoded files.
- Keyboard shortcuts:
    + <kbd>Ctrl</kbd><kbd>Alt</kbd><kbd>n</kbd> &rarr; new-node snippet.


# License

- [`LICENSE`][LICENSE]

```
MIT License

Copyright (c) 2021 Tristano Ajmone

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

# Links

- [github.com/pdml-lang] — PDML on GitHub.
- [pdml-lang.github.io][PDML] — official PDML website:
    + [Basic PDML Specification][Basic PDML].
    + [PDML Overview] — FAQ.

Related articles by [Christian Neumanns]:

- _[We Need a New Document Markup Language — Here is Why]_ — Mar. 11, 2019.
- _[Suggestion For a Better XML/HTML Syntax]_ — Apr. 20, 2021.
- _[Introduction to PDML]_ — Nov. 16, 2021.

<!-----------------------------------------------------------------------------
                               REFERENCE LINKS
------------------------------------------------------------------------------>

[MIT License]: ./LICENSE "View MIT License file"

<!-- PDML -->

[PDML]: https://pdml-lang.github.io "PDML website"
[github.com/pdml-lang]: https://github.com/pdml-lang "PDML organization on GitHub"

[PDML Overview]: https://pdml-lang.github.io/docs/faq/index.html "PDML: Frequently Asked Questions"

<!-- PDML Refs -->

[Basic PDML]: https://pdml-lang.github.io/docs/basic-specification/index.html "Basic PDML Specification"
[PDML extensions]: https://pdml-lang.github.io/docs/introduction/index.html#extensions "Learn more about PDML extensions"

<!-- articles -->

[We Need a New Document Markup Language — Here is Why]: https://pdml-lang.github.io/docs/introduction/index.html "Read the 'We Need a New Document Markup Language — Here is Why' article, by Christian Neumanns"
[Suggestion For a Better XML/HTML Syntax]: https://pdml-lang.github.io/docs/introduction/index.html "Read the 'Suggestion For a Better XML/HTML Syntax' article, by Christian Neumanns"
[Introduction to PDML]: https://pdml-lang.github.io/docs/introduction/index.html "Read the 'Introduction to PDML' article, by Christian Neumanns"

<!-- Sublime Text -->

[Sublime Text]: https://www.sublimetext.com "Visit Sublime Text website"
[syntax inheritance]: https://www.sublimetext.com/docs/syntax.html#inheritance "ST Docs: Syntax Definitions » Inheritance"

<!-- project files -->

[LICENSE]: ./LICENSE "View MIT License file"

<!-- badges -->

[License badge]: https://img.shields.io/badge/License-MIT-blue
[Package badge]: https://img.shields.io/badge/Package-1.0.0-yellow "Sublime PDML latest release"
[Package link]: https://github.com/tajmone/Sublime-PDML/releases
[ST badge]: https://img.shields.io/badge/Sublime_Text-4075-yellow?logo=sublime-text&logoColor=FF9800 "Supported Sublime Text version (click to visit download page)"
[ST link]: https://www.sublimetext.com/download "Supported Sublime Text version (click to visit download page)"
[Travis badge]: https://img.shields.io/travis/com/tajmone/Sublime-PDML/main?logo=travis
[Travis link]: https://app.travis-ci.com/github/tajmone/Sublime-PDML "Travis CI: EditorConfig validation status"

<!-- people and orgs -->

[Christian Neumanns]: https://github.com/pdml-lang "View Christian Neumanns's GitHub profile"
[Tristano Ajmone]: https://github.com/tajmone "View Tristano Ajmone's GitHub profile"

<!-- EOF -->
