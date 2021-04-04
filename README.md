# ALAN Repository Template [![CC0 Badge][CC0 Badge]][CC0 Link]

- https://github.com/alan-if/alan-repository-template

A boilerplate for quickly creating Alan projects with all the right settings in place.

Created by [Tristano Ajmone] on July 13, 2019. Released into the Public Domain.

[CC0 Badge]: https://licensebuttons.net/p/zero/1.0/88x31.png "CC0 1.0 Universal"
[CC0 Link]: #license

-----

**Table of Contents**


<!-- MarkdownTOC autolink="true" bracket="round" autoanchor="false" lowercase="only_ascii" uri_encoding="true" levels="1,2,3,4" -->

- [About this Template](#about-this-template)
    - [What Do I Get?](#what-do-i-get)
        - [Git Configurations](#git-configurations)
        - [EditorConfig Settings](#editorconfig-settings)
        - [README Template](#readme-template)
    - [License](#license)
- [Useful Alan Links](#useful-alan-links)
    - [Documentation and Tutorials](#documentation-and-tutorials)
    - [Code Examples](#code-examples)
    - [Libraries](#libraries)
    - [Editors](#editors)
    - [Miscellanea](#miscellanea)

<!-- /MarkdownTOC -->

-----

# About this Template

In June 6, 2019 GitHub announced a new feature to [generate new repositories with repository templates]. At the [Alan IF Development team] we promptly grasped the great potential of this new cool feature and decided to create a repository template for Alan projects, and release it into the public domain.

You can use this template to quickly create a GitHub repository for Alan projects by clicking on the <kbd>Use this template</kbd> button placed on the bar above the files list, or [by clicking on this link].

Your new repository created using this template will be optimally configured for working with Alan tools, adventures, commands scripts and game transcripts.

For more detailed information on using repository templates, see:

- [GitHub Docs » Creating a repository from a template]

To learn more about the internal details of this template, consult the [repository Wiki].

[by clicking on this link]: https://github.com/alan-if/alan-repository-template/generate "Create a new repository using the ALAN Repository Template!"
[generate new repositories with repository templates]: https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/ "Read full article on GitHub Blog"
[GitHub Docs » Creating a repository from a template]: https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template
[repository Wiki]: https://github.com/alan-if/alan-repository-template/wiki "Go to the Wiki of the ALAN Repository Template project"

## What Do I Get?

The template is just a boilerplate containing useful configurations designed to optimize Alan workflow in cross-platform collaborative projects.

Specifically, the repository template provides:

- [Git configurations](#git-configurations)
- [Editor configurations](#editorconfig-settings)
- [A README document template](#readme-template)

The configuration files for Git and EditorConfig cover the following Alan-specific files extensions:

|   ext    |                description                 |
|----------|--------------------------------------------|
| `.alan`  | Alan source files.                         |
| `.i`     | Alan source modules.                       |
| `.a3sol` | Alan commands script (aka solution files). |
| `.a3log` | Alan game transcripts.                     |

By default, the following Alan generated files will be excluded from the project:

|   ext   |           description           |
|---------|---------------------------------|
| `.a3c`  | Alan compiled adventures.       |
| `.ifid` | Source adventure IFID file.     |
| `.log`  | Compiler/ARun log files.        |
| `.sav`  | Saved games (used for testing). |


### Git Configurations

- [`.gitattributes`](./.gitattributes)
- [`.gitignore`](./.gitignore)

The template contains pre-set `.gitignore` and `.gitattributes` files with carefully designed patterns that will cover a variety of Alan usage scenarios in cross-platform environments.

The `.gitattributes` file defines EOL normalization settings for a variety of Alan related files, as well as covering common file extensions used in IF projects. It also provides additional settings for [GitHub Linguist], to improve repository statistics and Alan source files visualization on GitHub.

The `.gitignore` file defines _ad hoc_ file exclusion patterns for Alan projects, as well as covering common exclusion patterns for Windows, Linux and macOS.

[GitHub Linguist]: https://github.com/github/linguist "Visit the GitHub Linguist project on GitHub"

### EditorConfig Settings

- [`.editorconfig`](./.editorconfig)

The template contains [EditorConfig] settings for Alan files designed to offer support across multiple editors and IDEs, as well as to provide optimal source code previews on GitHub.

The [EditorConfig] file format is an application-agnostic standard for defining consistent coding style conventions for multiple developers working on the same project across various editors and IDEs. A growing number of editors and IDEs support EditorConfig out of the box, and numerous plug-ins and extensions are available for editors that don't.

One of the main benefits of the EditorConfig settings is the ability to enforce ISO-8859-1 encoding on Alan files (`*.alan`, `*.i`, `*.a3sol`, `*.a3log`) and prevent accidental UTF-8 file-corruption from copy-&-paste operations. Most editors that support [EditorConfig] should be able to enforce ISO-8859-1 strictness on Alan sources via the `.editorconfig` file.

As of Jun 2015, [GitHub natively supports EditorConfig] files within repositories. The `.editorconfig` file in this template will improve Alan sources visualization on GitHub. Although GitHub doesn't recognize Alan source files natively, it will honour the EditorConfig settings of this template.

[EditorConfig]: https://editorconfig.org/ "Visit the EditorConfig project website"
[Github natively supports EditorConfig]: https://github.com/editorconfig/editorconfig.github.com/pull/48


### README Template

- [`README.md`](./README.md)

You also get this markdown README document that you're reading right now, which contains the _[Useful Alan Links]_ section providing links to various Alan related assets, which you might reuse in your project. It's a well structured and polished markdown document, with many reference links to Alan assets (at the end of the source document) which might come handy — and could spare you a good amount of typing, if you're going to link to other Alan projects.

If you don't need the README file you can just trash it, but chances are that you'll be adding a `README.md` file to your project anyway, so you might as well just overwrite it, or keep the reference links that you need. After some initial thoughts, I finally decided that it was better to include this README file in the template, for the benefit of those wishing to offer links to the Alan community and assets, rather than leave it out. For those who'll need it, it's going to be a true time-saver, while those who don't need it shouldn't be bothered much by having to delete/overwrite it.

[Useful Alan Links]: #useful-alan-links "Jump to links section"

## License

To the extent possible under law, [Tristano Ajmone] has waived all copyright and related or neighboring rights to the [ALAN Repository Template]. This work is published from: Italy.

The __[ALAN Repository Template]__ is released into the public domain via the [CC0 1.0 Universal] dedication, so that it might be freely used for any project, without causing licenses conflicts and without imposing any restrictions or obligations (not even crediting or linking back).

[CC0 1.0 Universal]: https://creativecommons.org/publicdomain/zero/1.0/ "Learn more about Creative Commons 0"

> ## No Copyright
>
> The person who associated a work with this deed has dedicated the work to the public domain by waiving all of his or her rights to the work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law.
>
> You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission. See __Other Information__ below.
>
> ### Other Information
>
> * In no way are the patent or trademark rights of any person affected by CC0, nor are the rights that other persons may have in the work or in how the work is used, such as [publicity or privacy rights].
> * Unless expressly stated otherwise, the person who associated a work with this deed makes no warranties about the work, and disclaims liability for all uses of the work, to the fullest extent permitted by applicable law.
> * When using or citing the work, you should not imply [endorsement] by the author or the affirmer.

[publicity or privacy rights]: https://creativecommons.org/faq/#what-are-publicity-personality-and-privacy-rights
[endorsement]: https://creativecommons.org/faq/#do-i-need-to-be-aware-of-anything-else-when-providing-attribution

# Useful Alan Links

- [www.AlanIF.se][Alan] — the Alan website.
- [Alan IF Google Group] — for community help, announcements and discussions.
- [Alan sources on GitHub][Alan GitHub] — source code repository on GitHub.
- [Alan IF Development team] — GitHub profile and public projects.

## Documentation and Tutorials

- [Alan Docs] — GitHub repository for Alan documentation.
- _[The Alan Manual]_ — online-readable version of the latest _ALAN Adventure Language Reference Manual_.
- _[Alan Cookbook v2]_ — by [Anssi Räisänen].
- _[The Alan Beginner's Guide]_ — by Michael Arnaud (2006). [Tutorial source files available](https://github.com/alan-if/alan-docs/tree/master/alanguide/alanguide-code).
- _[Alan IDE Reference Guide]_ — by Robert DeFord (2018).

## Code Examples

- [Alan by Examples] — community driven collection of examples to learn Alan.
- [Samples & examples for Alan v3] — on Alan website.

## Libraries

- [Alan Standard Library] — by [Anssi Räisänen], GitHub repository.
- [Alan Library v0.6.2] — an earlier (but still working) library (2002–2007), mainly used to compile legacy adventures.
- [Alan StdLibLab] — experimental playground for variations on the Alan StdLib.
- [Alan Italian] — Italian port of the Alan StdLib.

## Editors

- [AlanIDE] — a complete Alan Integrated Development Environment, built in Java/Eclipse by Alan developer [Thomas Nilefalk]. For more info, see:
    + [AlanIDE info page].
    + _[Alan IDE Reference Guide]_ — by Robert DeFord (2018), PDF document.
    + [AlanIDE sources] — JAVA source files, on GitHub.
- [Sublime Alan] — [Sublime Text 3] package for Alan 3 (working Alpha).

## Miscellanea

- [Alan Goodies] — a collection of assorted assets for Alan.
- [Alan Builder] — a [Travis CI] compliant build tool for Alan IF adventures projects.
- [Alan Bugs Testbed] — collaborative project to report and test Alan bugs.
- [Alan Repository Template] — A boilerplate for quickly creating Alan repositories with the right settings.

<!-----------------------------------------------------------------------------
                               REFERENCE LINKS
------------------------------------------------------------------------------>

<!-- ALAN -->

[Alan]: https://www.alanif.se/ "Visit the Alan website"
[Alan IF]: https://www.alanif.se/ "Visit the Alan website"
[Alan IF Google Group]: https://groups.google.com/g/alan-if/ "Visit the Alan IF discussions group on Google Groups"
[Alan GitHub]: https://github.com/alan-if/alan/ "Visit the Alan source repository on GitHub"
[Alan SDK]: https://www.alanif.se/download-alan-v3/development-kits "Go to the Alan SDK section of the Alan website"

[Artistic License 2.0]: https://opensource.org/licenses/Artistic-2.0

<!-- AlanIDE -->

[AlanIDE]: https://www.alanif.se/download-alan-v3/alanide "Go to the AlanIDE download page on Alan website"
[AlanIDE info page]: https://www.alanif.se/information/alanide/alanide-intro "View the AlanIDE information page on Alan website"
[Alan IDE Reference Guide]: https://github.com/alan-if/alan-docs/blob/master/ideguide/ideguide.pdf "Get the 'Alan IDE Reference Guide' (PDF format)"
[AlanIDE sources]: https://github.com/thoni56/alanide "Visit the AlanIDE source repository on GitHub"

<!-- Alan StdLib -->

[Alan Standard Library]: https://github.com/AnssiR66/AlanStdLib/ "Visit the official repository of the Alan Standard Library on GitHub"

<!-- misc Alan projects  -->

[Alan Bugs Testbed]: https://github.com/alan-if/alan-bugs-testbed "Visit the Alan Bugs Testbed project on GitHub"
[Alan Builder]: https://github.com/alan-if/Alan-Builder "Visit the Alan Builder project on GitHub"
[Alan Goodies]: https://github.com/tajmone/alan-goodies "Visit the Alan Goodies project on GitHub"
[Alan Italian]: https://github.com/tajmone/Alan3-Italian "Visit the Alan Italian project on GitHub"
[Alan Library v0.6.2]: https://github.com/tajmone/alan-goodies/tree/master/libs "View Alan Lib v0.6.2 at the 'Alan Goodies' project"
[Alan Repository Template]: https://github.com/alan-if/alan-repository-template "Visit the Alan Repository Template on GitHub"
[Alan StdLibLab]: https://github.com/tajmone/Alan-StdLibLab "Visit the Alan StdLibLab project on GitHub"
[Sublime Alan]: https://github.com/tajmone/sublime-alan "Visit the Sublime Alan project on GitHub"

<!-- Alan docs & tutorials -->

[Alan Docs]: https://github.com/alan-if/alan-docs "Visit the Alan Docs project on GitHub"
[The Alan Manual]: http://htmlpreview.github.io/?https://github.com/alan-if/alan-docs/blob/master/manual/manual.html "Live HTML preview of the Alan Manual"
[Alan Cookbook v2]: https://www.alanif.se/download-alan-v3/all-downloads/documentation/alan-cookbook-v2 "Go to the 'Alan Cookbook' download page on Alan website"

[The Alan Beginner's Guide]: http://htmlpreview.github.io/?https://github.com/alan-if/alan-docs/blob/master/alanguide/alanguide.html "Live HTML preview of the Alan Beginner's Guide"

[Samples & examples for Alan v3]: https://www.alanif.se/information/samples
[Alan by Examples]: https://github.com/alan-if/alan-by-examples "Visit the Alan by Examples project"

<!-- 3rd party tools & services -->

[Sublime Text 3]: https://www.sublimetext.com/ "Visit Sublime Text website"
[Travis CI]: https://travis-ci.com/ "Visit Travis CI website"

<!-- people and organizations -->

[Alan IF Development team]: https://github.com/alan-if "Visit the Alan Interactive Fiction Development team organization on GitHub"

[Anssi Räisänen]: https://github.com/AnssiR66 "View Anssi Räisänen's GitHub profile"
[Tristano Ajmone]: https://github.com/tajmone "View Tristano Ajmone's GitHub profile"
[Thomas Nilefalk]: https://github.com/thoni56 "View Thomas Nilefalk's GitHub profile"

<!-- EOF -->
