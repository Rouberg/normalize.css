# Changes to normalize.css

### 1.1.0 (Aug 9, 2018)
* Add default touch action `manipulation` from tag `html`.

### 1.0.1 (May 24, 2018)

* Fix `-webkit-tap-highlight-color` into form element and link element.

### 1.0.0 (May 22, 2018)

(Fork from [normalize.css](https://github.com/necolas/normalize.css) and create project.
Earlier change log in [here](https://github.com/necolas/normalize.css/blob/master/CHANGELOG.md))

* Remove IE related styles.
* Remove highlight background when touch an element.
* Reset root font-family, maybe more friendly to local zh_CN.
* Add font smoothing strategy of antialiased.
* Reset root line-height to 20px and unit of `%`, for postcss friendly.
* Remove text-decoration of tag `a`, in mobile browser we like distinguish by color more.
* Reset tag `a` Inherit color from parent
* Remove text-decoration of tag `abbr`, title upgrade by DIY component maybe is a better idea.
* Make font-size of tag `small` a little small and close to 11px.
* Remove textarea resize because it's not a good idea and we don't need it, scroll is better.
* Remove shadow dom's visibility of `input[type="number"]`. 
* Remove outline of textarea, input, button when them focus.
* Remove list-style-type, margin and padding of tag `ol`, `ul`.
* Remove iframe border. We had to use it sometimes although it's not the best idea.
