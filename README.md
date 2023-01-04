# lasermetal.art Documentation

## config.toml

This file contains general information and customization about the site.

| Parameter | Description |
|---|---|
| `baseURL` | URL of the site |
| `title` | Title of the site |
| params > `mapIframe` | Google maps iframe url |
| params > `footerText` | Text displayed on the footer |
| params > `address` | Contact page address information |
| params > `instagram` | Instagram username |
| params > `email` | E-mail, used in footer and contact page |
| params > `formUrl` | Url for the form submission backend |

## Homepage (content/_index.md)

Frontmatter variables:

| Parameter | Description |
|---|---|
| `title` | Title of the page |
| `heroTitle` | Text displayed on top of the page under the header |
| `featuredArtworkSlider` | Images displayed on the homepage slider |
| `tig` | Image, Title and texts listed under the slider. Each tig item should contain `title`, `paragraph` and `img` |
| `cta` | Call to action section displayed under the page |

## Gallery (content/gallery.md)

Frontmatter variables:

| Parameter | Description |
|---|---|
| `title` | Title of the page |
| `heroTitle` | Text displayed on top of the page under the header |
| `images` | Image list that displayed on the page. You need to give image path value, it can be served online or local file |

## About / The Process (content/about/the-process.md)

> Note: This page can have better content management method rather than just changing the html code. I'm planning to update
> it in the future.

Frontmatter variables:

| Parameter | Description |
|---|---|
| `title` | Title of the page |
| `heroTitle` | Text displayed on top of the page under the header |
| `heroParent` | Text displayed on the left of `heroTitle`. It's opacity slightly lower than normal |
| `cta` | Call to action section displayed under the page |

Content of the page:
The content is coming from the html for now. It's can be found at `/layots/_default/the-process.html`. To add/change images on the
slider just play with html elements under `<div class="swiper-wrapper">`.

## About / Family Business (content/about/family-business.md)

Frontmatter variables:

| Parameter | Description |
|---|---|
| `title` | Title of the page |
| `heroTitle` | Text displayed on top of the page under the header |
| `heroParent` | Text displayed on the left of `heroTitle`. It's opacity slightly lower than normal |
| `cta` | Call to action section displayed under the page |

Content of the page:
The content is coming from the html for now. It's can be found at `/layots/_default/family-business.html`.

## About / F.A.Q (content/about/faq.md)

Frontmatter variables:

| Parameter | Description |
|---|---|
| `title` | Title of the page |
| `heroTitle` | Text displayed on top of the page under the header |
| `heroParent` | Text displayed on the left of `heroTitle`. It's opacity slightly lower than normal |

Content of the page:
Each question uses `###` heading 3 as title. It's data straightly coming from it's markdown file, yay :^) .

## About / Contact (content/about/contact.md)

Frontmatter variables:

| Parameter | Description |
|---|---|
| `title` | Title of the page |
| `heroTitle` | Text displayed on top of the page under the header |
| `heroParent` | Text displayed on the left of `heroTitle`. It's opacity slightly lower than normal |

## About / Free Quote (content/about/free-quote.md)

Frontmatter variables:

| Parameter | Description |
|---|---|
| `title` | Title of the page |
| `heroTitle` | Text displayed on top of the page under the header |
| `heroParent` | Text displayed on the left of `heroTitle`. It's opacity slightly lower than normal |

Content of the page:
To add/remove form elements you can change the html from `/layouts/_default/free-quote.html`. After changing html it'll automagickly
update the getform, so you don't have to change anything from it's panel.
