Credit: [NichtsHsu](https://github.com/NichtsHsu
)
Personal blog based on [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme customization, [click here to enter](https://nihil.cc/).

[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)

Differences from the original Chirpy:

* On the original supported commenting systems [Disqus](https://disqus.com/), [Utterances](https://utteranc.es/) and [Giscus](https://giscus.app/zh-CN ), add support for [Valine](https://valine.js.org/) / [Waline](https://waline.js.org/) comment system, see `_config.yml` comments` and their respective configuration sections. It is recommended to consider using Waline instead of Valine.
* Using [Zhihu-style 404 interface](https://404.life/564.html), you can return to the home page or return to the previous page.
* Added sharing to Line, QQ, Qzone and Weibo, see `_data/share.yml`.
* Use [iconfont](https://www.iconfont.cn/) instead of [Font Awesome](https://fontawesome.com/), there are more icon options, see `_config.yml` iconfont_css`.
* Added external links block to the right sidebar, see `_data/external_links.yml`.
* Freely control which blocks are displayed on the right sidebar in the post. See `panel` in `_config.yml`.
* Added subdomain page. See `_data/subdomain.yml`. Just delete `_tabs/subdomain.md` if you don't need this page.
* Added the style of `<details>` tag and modified the style of blockquote.
* Use table styles adapted from [`just the docs`](https://github.com/pmarsceill/just-the-docs).
* Applied code coloring to inline code segments, e.g. `` `let fuck_rust = 114514;`{:.language-rust} ``.
* Use [Fira Code](https://github.com/tonsky/FiraCode) as the code snippet font. By default, Ligature is not enabled for inline code, but is enabled for block code. Siamese is disabled in shell languages ​​for some reason.
* In the dark theme, the title and bold content are indistinguishable in the white text, and the glow effect is added to highlight it.
* Can configure to highlight certain lines in the code segment, refer to [here](http://nihil.cc/posts/highlight_lines_for_jekyll/#%E4%BE%8B%E5%AD%90).
* To run the code to display the output (under development, some languages ​​are currently supported), you need to add `{: run="lang" }` to the next line of the code segment, for example:

    ````markdown
    ```rust
    fn main() {
        println!("hello world");
    }
    ````
    {: run="rust" }
    ````

    Language support:
    | Supported languages ​​| `run="lang"` parameter | backend |
    | :-: | :-: | :-: |
    | C++ | `run="cpp"` | [Coliru](https://coliru.stacked-crooked.com/) |
    | JavaScript | `run="javascript"` | N/A (local) |
    | Rust | `run="rust"` | [Rust Playground](https://play.rust-lang.org/) |

If you like my customized version, welcome to Fork, but please modify the `id` of `google_analytics` in `_config.yml`, the `server` of `waline`, and the domain name configured in the `CNAME` file, please do not use my configuration.

Typically, [`upstream/master`](https://github.com/cotes2020/jekyll-theme-chirpy) is merged at least once a week to track new features.

The original version of Chirpy will also be kept in sync in the [original-chirpy](https://github.com/NichtsHsu/nichtshsu.github.io/tree/original-chirpy) branch.