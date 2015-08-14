SublimeText-Perl-Test-More
==========================

This package provides snippets for Perl's [Test::More](https://metacpan.org/pod/Test::More) for [Sublime Text 2/3](http://www.sublimetext.com/)

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
```

So you simply write the Test::More routine you want and press the tab key

An example:

```perl
ok<tab>
```

expands to:

```perl
ok($got eq $expected, 'test_name');
```

1. tabbing again lets you write the assertion
2. tabbing yet again lets you label the test
3. And then you can run your test suite

This package can with luck be used with the [package](https://github.com/jonasbn/SublimeText-Perl-Test-Class) for Perl's Test::Class for Sublime Text 2.

# Installation

Several options are available for installation.

## Via Sublime Package Control:

- `Control`+`Shift`+`P` on Linux/Windows,
- `Command`+`Shift`+`P` on OS X,
- or for any OS
  1. Select `Tools->Command Palette` from the menu
  2. Select `Package Control: Install Package`
  3. Select **perl-Test-More** from the list of available packages

## Git:

Clone the repository in your Sublime Text Packages directory.

```git clone https://github.com/jonasbn/perl-Sublime-Test-More Test-More```

The advantage of using either Package Control or git is, that the plugin will be automatically kept _up-to-date_.

## From ZIP

1. [Download](https://github.com/jonasbn/SublimeText-Perl-Test-More/archive/master.zip) the zip file
2. Unpack it in your Sublime Text directory, as per OS
  - OS X    ~/Library/Application Support/Sublime Text 2/Packages/
  - Linux   ~/.config/sublime-text-2/Packages/
  - Windows %APPDATA%\Sublime Text 2\Packages\
3. Start using it! (see section above)

# Issues

Please report any issues via [github](https://github.com/jonasbn/SublimeText-Perl-Test-More/issues).

# Motivation

I write a lot of test code across projects/distributions and since Test::More is put to such wide use it is nice to be able to write tests fast and consistenly.

# License

The package is licensed under the  Artistic License 2.0 and pull-requests are most welcome.

jonasbn, Copenhagen/Denmark