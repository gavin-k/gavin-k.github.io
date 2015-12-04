---
title: "Developer Checklist"
layout: "post"
description: 
categories: [tools]
author: "Gavin Lee"
---


Here's my personal checklist while installing a Mac machine:

### Installation:

- Xcode
- Alfred
- Moom
- Dash
- Homebrew: Installation: `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`, ortherwise available at [http://brew.sh/];
- Haskell: Software available [online](https://www.haskell.org/platform/mac.html) or `brew install ghc haskell-platform cabal-install`;
- Node: `brew install node` will install Node.js perfectly;
- Set up SSH public key on various servers, including Github and Phabricators

### Sublime Modules:

- Package Control, installer available [online](https://packagecontrol.io/installation): `import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)`
- DocBlockr
- Emmet
- Git
- GitGutter
- Jade Snippets
- JavaScript & NodeJS Snippets
- Terminal
- Highlights for code:
    + LESS
    + Sass
    + SCSS
    + Stylus
    + Swift
    + Markdown Editing
- Style Updates
    + SideBarEnhancements
    + Theme - Centurion
    + Theme - Spacegray
- Linter
    + SublimeLinter
    + SublimeLinter-annotations
    + SublimeLinter-coffee
    + SublimeLinter-csslint
    + SublimeLinter-jslint
    + SublimeLinter-jsxlint

### Xcode Plugins:

- Alcatraz, package manager for Xcode, [http://alcatraz.io], install via `curl -fsSL https://raw.github.com/supermarin/Alcatraz/master/Scripts/install.sh | sh`
- XToDo, collect TODO list;
- FuzzyAutocomplete，auto completes methods;
- KSImageNamed, prints image name while refrencing images;
- GitDiff, shows editid files;
- CocoaPods, manages cocoa pods;
- Backlight, highlights current editing line;
- SCXcodeMiniMap, shows code map as Sublime Text;
- VVDocumenter, creates documentation block automatically;

