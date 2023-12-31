# AllSet Learning Chinese Grammar Wiki

This repo contains a copy of grammar points from [AllSet Learning Chinese Grammar Wiki](https://resources.allsetlearning.com/chinese/grammar/) ("ASG" for short), a fantastic and well-structured free resource on Mandarin grammar. As well as related scripts to work with it.

- `wiki/ASGxxxxx.txt`: grammar point articles.
  - Article title is stored inside `<!-- -->` comment on the first line of each file, the rest of file is raw mediawiki markup as crawled from 'View source' pages.
  - Named after internal redirect IDs on ASG wiki: `https://resources.allsetlearning.com/chinese/grammar/ASGxxxxx` -> redirects to the actual article.
  - Crawled in October 2023.
- `wiki/index.tsv`: list of ASG IDs and article titles.

## License

ASG wiki's content has been released under [Creative Commons BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) at the time of downloading it (Oct 2023). Upstream copyright notice:

> All content on the Chinese Grammar Wiki ©2021 AllSet Learning, and **may not be used for commercial purposes or without attribution**. For more information on how to legally use this content, please see our [Creative Commons license](http://creativecommons.org/licenses/by-nc-sa/3.0/).
>
> When attributing the source of the Chinese Grammar content, you must provide a link on every page/view where the content appears, using this full name:
>
> **AllSet Learning Chinese Grammar Wiki** (https://resources.allsetlearning.com/chinese/grammar/)
>
> Furthermore, the non-commercial requirement means that in addition to prohibiting regular for-profit business use, *no website or app that generates any revenue at all through advertising may legally use Chinese Grammar Wiki content* through this Creative Commons license.
>
> **不允许任何以商业为目的或不注明**归属Chinese Grammar Wiki ©2013 AllSet Learning 的内容引用。关于合法使用此内容的更多信息，请参阅我们的知识共享权限条款（[Creative Commons license](http://creativecommons.org/licenses/by-nc-sa/3.0/deed.zh)）。
>
> Thank you for your support of this free resource!

License for code (scripts, jupyter notebooks): public domain / [Unlicense](https://unlicense.org).
