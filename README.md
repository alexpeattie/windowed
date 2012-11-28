# windowed.js

![Animated demo](https://raw.github.com/alexpeattie/windowed/master/animated-demo.gif)

windowed.js is a jQuery plugin that implements Chris Norström's awesome ["Windowed Slider"](http://www.chrisnorstrom.com/2012/11/invention-multiple-choice-windowed-slider-ui/) concept. It takes your regular checkboxes or `<select>` lists and transforms them into slick 'windowed sliders'.

**For documentation, usage, and examples, see:
http://www.alexpeattie.com/projects/windowed/**

#### Requirements
- [jQuery](http://jquery.com/): 1.7+

### File size
- Uncompressed: 12.75 Kb
- Minified: 5.9 Kb
- Minified + gzipped: 2.2 Kb

## Quickstart

Add the `windowed.min.css` and `jquery.windowed.min.js` files to your HTML page:

```html
<head>
  <link rel="stylesheet" href="path/to/windowed.min.css">
</head>
<body>
  <!-- blah blah -->
  <script src='jquery.js'></script>
  <script src='/path/to/jquery.windowed.min.js'></script>
</body>
```

Transform your checkbox or `<select>` by calling `.windowed()`:

```javascript
$("select, input:checkbox").windowed();
```

See the site for **[more usage and examples](http://www.alexpeattie.com/projects/windowed/#usage)**

## Compatibility

See **[Compatibility](https://github.com/alexpeattie/windowed/wiki/Compatibility)** in the wiki for the most up-to-date info.

I've tested the plugin on recent versions of Firefox, Chrome and Safari (mobile & desktop) - theoretically it should work fine in IE7+ and Opera, but these are untested. If you've tried the plugin with an untested browser, please, add it to the wiki!

## Credits

- Created by [Alex Peattie](http://www.alexpeattie.com) ([@alexpeattie](https://twitter.com/alexpeattie))
- Original concept by [Chris Norström](http://www.chrisnorstrom.com/) ([@ChrisNorstrom](https://twitter.com/ChrisNorstrom))

## Changelog

__Version 0.1.0 (2012-11-28)__:
Initial version.

## Todo

- Add ability to swap the checkbox labels (i.e. have OFF on the left, rather than the right)
- Responsive (variable width) components
- Add tabbing support/keyboard navigation
 
## Contributing

If you want to have a stab at any of the todo items above - or anything else - [pull requests](https://github.com/alexpeattie/windowed/pulls) are gratefully received.

For any bug reports or feature ideas, head over to [Issues](https://github.com/alexpeattie/windowed/pulls). Another big help would be to expand the [documentation on browser compatibility](https://github.com/alexpeattie/windowed/wiki/Compatibility) in the wiki.

## License

windowed.js is freely distributable under the terms of the MIT license (see [LICENSE.md](https://github.com/alexpeattie/windowed/blob/master/LICENSE.md)).