# Resume

### resume for Mei

A clean, single column, monospace resume template built for jekyll, originally coppied from [researcher](http://ankitsultana.com/researcher)

### Installation

Simply fork the repository and edit away.

### Customization

* You can edit the `.md` (markdown) files as you see fit. You can also add some other markdown file, say `foo.md` in the root directory of the repository. It will then be accessible like so `{{ url of your website }}/foo`.

* You can of course remove `contact.md` if you don't want it

* To set the heading, edit the `title` variable in `_config.yml`

* To edit the `links` mentioned on the navigation bar, edit the file `_data/nav.yml`

* You can change the accent (color of hyperlinks) by editing the `accent` variable in `_sass/vars.scss`

* You can setup google analytics, by setting `tracking_id` in `_config.yml`

* To add a profile picture, make sure to give the image tag the class `profile-picture`. In other words,do it like so:

```html
<img class="profile-picture" src="sherlock.jpg">
```

**Note:** 

### License

[GNU GPL v3](https://github.com/bk2dcradle/researcher/blob/gh-pages/LICENSE)
