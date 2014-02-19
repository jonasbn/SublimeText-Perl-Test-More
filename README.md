SublimeText-Perl-Test-More
==========================

This package provides snippets for Perl's [Test::More](https://metacpan.org/pod/Test::More) for [Sublime Text 2](http://www.sublimetext.com/2)

# Introduction

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
3. And you can run your test suite

This package can with luck be used with the [package](https://github.com/jonasbn/SublimeText-Perl-Test-Class) for Perl's Test::Class for Sublime Text 2.

# Installation

1. [Download](https://github.com/jonasbn/SublimeText-Perl-Test-More/archive/master.zip) the zip file
2. Unpack it in your Sublime Text directory
3. Start using it! (see section above)

# Issues

Please report any issues via [github](https://github.com/jonasbn/SublimeText-Perl-Test-More/issues).

# Motivation

I write a lot of test code across projects/distributions and since Test::More is put to such wide use it is nice to be able to write tests fast and consistenly.

# License

The package is licensed under the  Artistic License 2.0 and pull-requests are most welcome.

jonasbn, Copenhagen/Denmark