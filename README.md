SublimeText-Perl-Test-More
==========================

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This package provides snippets for Perl's [Test::More](https://metacpan.org/pod/Test::More) for [Sublime Text 2 and 3](http://www.sublimetext.com/)

<!-- MarkdownTOC depth=1 -->

- [Introduction and Usage](#introduction-and-usage)
- [Installation](#installation)
- [Issues](#issues)
- [Motivation](#motivation)
- [Acknowledgements](#acknowledgements)
- [History](#history)
- [License](#license)

<!-- /MarkdownTOC -->

<a name="introduction-and-usage"></a>
# Introduction and Usage

The package is currently offering the following snippets:

```perl
BAIL_OUT
can_ok
cmp_ok
diag
is
isa_ok
isnt
like
ok
unlike
is_deeply
done_testing
```

You simply write the [Test::More](https://metacpan.org/pod/Test::More) routine you want and press the `tab` key

An example:

```perl
ok<tab>
```

expands to:

```perl
ok($got eq $expected, 'test_name');
```

1. _tabbing_ once again lets you write the assertion
2. _tabbing_ yet again lets you label the test
3. And then you can run your test suite

This package can with compliments the [package](https://github.com/jonasbn/SublimeText-Perl-Test-Class) for Perl's [Test::Class](https://metacpan.org/pod/Test::Class) for **Sublime Text 2 and 3**.

<a name="installation"></a>
# Installation

For installation several options are available.

<a name="via-package-control"></a>
## Via [Package Control](https://packagecontrol.io/):

- `Control`+`Shift`+`P` on Linux/Windows,
- `Command`+`Shift`+`P` on OS X,
- or for any OS
  1. Select `Tools->Command Palette` from the menu
  2. Select `Package Control: Install Package`
  3. Select **perl-Test-More** from the list of available packages

<a name="git"></a>
## Git:

Clone the repository in your Sublime Text Packages directory.

`$ git clone https://github.com/jonasbn/perl-Sublime-Test-More`

The advantage of using either Package Control or git is, that the plugin will be automatically be updated.

See also the [Package Control page](https://packagecontrol.io/packages/perl-Test-More) for this plugin. 

<a name="from-zip"></a>
## From ZIP

### Sublime Text 3

1. [Download](https://github.com/jonasbn/SublimeText-Perl-Test-More/archive/master.zip) the zip file
2. Unpack it in your Sublime Text directory, as per OS and Sublime Text 
  - OS X    ~/Library/Application Support/Sublime Text 3/Packages/
  - Linux   ~/.config/sublime-text-3/Packages/
  - Windows %APPDATA%\Sublime Text 3\Packages\
3. Start using it! (see section above)

### Sublime Text 2

1. [Download](https://github.com/jonasbn/SublimeText-Perl-Test-More/archive/master.zip) the zip file
2. Unpack it in your Sublime Text directory, as per OS and Sublime Text 
  - OS X    ~/Library/Application Support/Sublime Text 2/Packages/
  - Linux   ~/.config/sublime-text-2/Packages/
  - Windows %APPDATA%\Sublime Text 2\Packages\
3. Start using it! (see section above)

<a name="issues"></a>
# Issues

Please report any issues via [github](https://github.com/jonasbn/SublimeText-Perl-Test-More/issues).

<a name="motivation"></a>
# Motivation

I write a lot of test code across projects/distributions and since [Test::More](https://metacpan.org/pod/Test::More) is put to such wide use it is nice to be able to write tests fast and consistenly.

<a name="acknowledgements"></a>
# Acknowledgements

- Daniel Salgado Población contributed `is_deeply` and `done_testing`, resulting in version 1.1.0

<a name="history"></a>
# History

<a name="2015-11-27-110"></a>
## 2015-11-27 1.1.0

- `is_deeply` and `done_testing` added

<a name="2015-08-15-100"></a>
## 2015-08-15 1.0.0

- Initial version

<a name="license"></a>
# License

The package is licensed under the  Artistic License 2.0 and pull-requests are most welcome, please see [the contribution guidelines](CONTRIBUTING.md).

jonasbn, Copenhagen/Denmark
