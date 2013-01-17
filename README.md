# jQuery Github Repos

[![Github Repo Demonstration](http://f.cl.ly/items/0J1y0o0D461A0T1v1328/Screen%20Shot%202013-01-13%20at%207.32.55%20PM.png)](http://zenorocha.github.com/jquery-github-repos/)

## Usage

Create an attribute called `data-repo`:

```html
<div data-repo="jquery-boilerplate/boilerplate"></div>
```

Include jQuery:

```html
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
```

Include plugin's CSS and JS:

```html
<link rel="stylesheet" href="assets/base.css">
<script src="jquery.github.repos.min.js"></script>
```

Call the plugin:

```javascript
$('[data-repo]').githubRepos();
```

And that's it \o/

[Check the full example here](https://github.com/zenorocha/jquery-github-repos/blob/master/demo/index.html)

## Forks

Prefer a non-jquery version with pure JavaScript? No problem, [@ricardobeat](https://github.com/ricardobeat) already did one :) Check [his fork!](https://github.com/ricardobeat/github-repos)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.2.3 January 17, 2013
  * Updated to jQuery v1.9
* v0.2.2 January 15, 2013
  * Fixed "Last commit" date
  * Cached repo data using sessionStorage
  * Added error message if API exceeds its limits
* v0.2.1 January 13, 2013
  * Added live demo
  * Replaced single images for a sprite
  * Added minified version
* v0.2 September 11, 2012
  * Code wrapped into a jQuery plugin
  * Demonstration page created
* v0.1 September 10, 2012
  * Initial commit

## License

[MIT License](http://zenorocha.mit-license.org/)