# PHP generics

It is an exciting time for generics in PHP. Adding langauge level support for generics in PHP might be some time off as it [is hard](https://www.youtube.com/watch?v=teKnckg5x7I&feature=youtu.be&t=1121). However PHP static analyser tools such as [Psalm](https://psalm.dev) can be used to do type checking including generics. This step could be added into the build process as an equivalent of compliation stage in complied languages. 

This repo acts as a repository for links to articles, blog posts, etc about generics for PHP. Please submit PRs to include any relevant material.

## RFCs

- [RFC](https://wiki.php.net/rfc/generics) for PHP generics


## Articles, blog posts, tutorials

- [The case for Generics in PHP](https://www.phparch.com/2018/11/the-case-for-generics-in-php/) The benefits generics would bring to PHP.
- [Generics today (almost)](https://www.daveliddament.co.uk/articles/php-generics-today-almost/) How existing tools can be used as part of the build process to emulate generics. 
- [Phan's generics support](https://github.com/phan/phan/wiki/Generic-Types) A great explanation of how Phan (created by Rasmus) supports generics.
- [Psalm's generics support](https://psalm.dev/docs/annotating_code/templated_annotations/) Notation that Psalm uses for generics and templates. 
- [PHPStan generics](https://arnaud.le-blanc.net/post/phpstan-generics.html) How PHPStan will be introducing templates to it's analysis.


## Tools 

- [Psalm](https://psalm.dev) Psalm offers comprehensive support for generics.
- [Phan](https://github.com/phan/phan) Phan also has comprehensive support for generics.
- [PHPStan](https://github.com/phpstan/phpstan) PHPStan has basic support for generics with templates to be released soon.


## Request for generics support in IDEs

If you want generics in IDEs then perhaps you should upvote these requests:

- [PhpStorm support for @template](https://youtrack.jetbrains.com/issue/WI-47158)
- [PhpSotrm support for PHPDoc collections](https://youtrack.jetbrains.com/issue/WI-43843)



## And finally...

- [PhpGenerics](https://github.com/ircmaxell/PhpGenerics) Don't try this at home!
