# Quick Ref

Re-deploy

At image that can be click expanded and gallery in a modal (using lightbox 2 js)

```
  {{<imageToClick imagePath = "DALL·E 2022-11-14 21.23.51 - Fullstack problem solver agilist collaborator as a battle scene oil painting. Has computers and technology floating around.png" Capition = "DALL·E 2022-11-14 21.23.51 - Fullstack problem solver agilist collaborator as a battle scene oil painting. Has computers and technology floating around"  width = "75%" >}}
```


# Pete Modified

WIP of Pete's updates to this theme.

This repo is a submodule of that.

Source for WIP site is here: [Sandbox site](https://github.com/dunhampa/hugo_sandboxThemePapaya) (gif video from August 2022)

---
# Papaya

Minimalist Hugo theme with social buttons and analytics.

## Getting started

1. Install Hugo https://gohugo.io/getting-started/quick-start/
2. Clone or download this theme into the `themes` directory
3. Update your `config.toml`file to point to the theme
````
theme = "papaya"
````
4. Start the server with `hugo server``
5. Go to http://localhost:1313

## Example config.toml

````
baseURL = "https://example.com/"
languageCode = "en-gb"
title = "Example"

theme = "papaya"

[taxonomies]
  tag = "tags"

# The value of pre is the icon name in https://feathericons.com/
[menu]
  [[menu.main]]
    name = "Home"
    pre = "home"
    url = "/"
    weight = 1
  [[menu.main]]
    name = "Blog"
    pre = "edit"
    url = "/blog/"
    weight = 2
  [[menu.main]]
    name = "Tags"
    pre = "tag"
    url = "/tags/"
    weight = 3

[params]
  dateFormat = "Jan 2, 2006"
  authorName = "John Doe"
  googleAdSense = "ca-pub-0000000000000000"
  googleAnalytics = "UA-000000000-1"

[social]
  twitter = "Example"
````

*dateFormat* will be the format used to display the of the posts

*authorName* will be displayed on the home page, but note that each post can have its own author

*googleAdSense* (optional) your Google AdSense code

*googleAnalytics* (optional) your Google Analytics code

*twitter* handle that you want to show as source with `via` when sharing on Twitter
