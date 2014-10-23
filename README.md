# NAME

Task::Kensho::WebCrawling - Web Crawling

# VERSION

version 0.34001

# SYNOPSIS

    > cpanm --interactive Task::Kensho::WebCrawling

# DESCRIPTION

From [http://en.wikipedia.org/wiki/Kensho](http://en.wikipedia.org/wiki/Kensho):

> Kenshō (見性) (C. Wu) is a Japanese term for enlightenment
> experiences - most commonly used within the confines of Zen
> Buddhism - literally meaning "seeing one's nature"\[1\] or "true
> self."\[2\] It generally "refers to the realization of nonduality of

Task::Kensho is a first cut at building a list of recommended modules
for Enlightened Perl development. CPAN is wonderful, but there are too
many wheels and you have to pick and choose amongst the various
competing technologies.

The plan is for Task::Kensho to be a rough testing ground for ideas that
go into among other things the Enlightened Perl Organisation Extended
Core (EPO-EC).

The modules that are bundled by Task::Kensho are broken down into
several categories and are still being considered. They are all taken
from various top 100 most used perl modules lists and from discussions
with various subject matter experts in the Perl Community. That said,
this bundle does _not_ follow the guidelines established for the EPO-EC
for peer review via industry advisers.

Starting in 2011, Task::Kensho split its sub-groups of modules into
individually-installable tasks. These individual tasks will always install all
their modules by default. This facilitates the ease and simplicity the
distribution aims to achieve. Each Task::Kensho sub-task is listed at the
beginning of its section in this documentation.

## Web Crawling: Task::Kensho::WebCrawling

- [HTTP::Lite](https://metacpan.org/pod/HTTP::Lite)

    Lightweight HTTP client implementation

- [LWP::Simple](https://metacpan.org/pod/LWP::Simple)

    Simple procedural interface to LWP

- [LWP::UserAgent](https://metacpan.org/pod/LWP::UserAgent)

    Full-featured Web client library for Perl

- [WWW::Mechanize](https://metacpan.org/pod/WWW::Mechanize)

    Handy web browsing in a Perl object

- [WWW::Mechanize::TreeBuilder](https://metacpan.org/pod/WWW::Mechanize::TreeBuilder)

    This module combines WWW::Mechanize and HTML::TreeBuilder.

# RELEASE SCHEDULE

Starting with release 0.18 Task::Kensho was moved to a monthly release
cycle. This will facilitate a consistent schedule for upstream vendors
to track the changes in Task::Kensho.

# BUGS AND LIMITATIONS

This list is by no means comprehensive of the "Good" Modules on CPAN.
Nor is this necessarily the correct path for all developers. Each of
these modules has a perfectly acceptable replacement that may work
better for you. This is however a path to good perl practice, and a
starting place on the road to Enlightened Perl programming.

Please report any bugs or feature requests to
`bug-task-kensho@rt.cpan.org`, or through the web interface at
[http://rt.cpan.org](http://rt.cpan.org).

# SEE ALSO

[http://www.enlightenedperl.org/](http://www.enlightenedperl.org/),
[Perl::Dist::Strawberry](https://metacpan.org/pod/Perl::Dist::Strawberry)

# AUTHOR

Chris Prather <chris@prather.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2008 by Chris Prather.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
