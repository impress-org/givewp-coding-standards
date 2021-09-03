# GiveWP Coding Standards

This repository is the master record for the GiveWP coding standards. When using another GiveWP
repository, its standardization files should match these. If they do not, they should be updated.

If you have any standardization questions or suggestions, please create an Issue or Pull Request
in this repository. Changes can be applied otherwise.

## Philosophy

After years and years of development, I (@jasontheadams) have come to realize that standards don't matter
as much as wish they did. Whether there's a trailing comma, spaces vs tabs, curly bracket before or after
the function, and so forth — people with all manners of formatting preferences manage to accomplish
enterprise-level work.

Ok. So why have a standard? One word: **consistency**.

Diving into a codebase and seeing ten standards in a single file because ten developers touched it at
different times is overwhelming and disorienting. Being able to move through a codebase a have it all
look uniform and consistent is lovely.

In short, it's less about the perfection of a standard, and more about being consistent in the use of
that standard.

So how do you choose a standard? This can be debated a bit, but my opinion is that the standard should
be consistent within the industry, simply for the reason that it's nice to move from one organization to
another and have consistent results. That is why how the following standards were selected.

## PHP Standards

We use PSR-12. For ease of use with PhpStorm, just zip up the contents of the phpstorm directory
and do File > Manage IDE Settings > Import Settings. Don't worry, it won't override themes or
stuff like that, just inspections and code standards.

## JS Standards

We use [Prettier](https://prettier.io/) for JS, JSX and TS. Why? Because it's simple and opinionated.

## Everything Else

For all other files, Prettier and the .editorconfig file addresses those.
