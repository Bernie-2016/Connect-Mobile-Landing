# Landing Page for the Bernie Mobile App

Responsive mobile landing page for "Movement" built using

* [Slim Lang](http://slim-lang.com/)
* [SCSS](http://sass-lang.com/)
* [Bernstrap](https://github.com/SandersForPresident/bootstrap)
* [Wow.js](https://github.com/matthieua/WOW)
* [Animate.css](https://github.com/daneden/animate.css)

# Developer Dependencies

Install scss (if not present)

```
gem install scss
```
Install slim (if not present)

```
gem install slim
```

# Compiling Assets

`$ cd BernieWebApp/`

To compile the stylesheet once you've made changes, use the scss gem:

`$ scss -t compressed scss/main.scss css/main.css`

To compile the index page once you've updated the `slim` template, use the slim gem:

`$ slimrb index.slim > index.html`

# Contributing

## Making changes

In order to make changes, make your changes on a fork of the this repository and then issue a pull request. Please follow the advice below to ensure that your contribution will be readily accepted.

### Make your changes

* Create a branch for your changes (optional, but highly encouraged)
* Please test your changes (this site is mobile responsive so please make sure that any edits are compatible with multiple browsers and devices)
* Push your changes up to your fork at github

### Make a pull request

When you have finished making your changes and testing them, go to your forked repo on github and issue a pull request for the branch containing your changes.  Please keep in mind the following before submitting your pull request:

* We favor pull requests with very small, single commits with a single purpose.  If you have many changes, they'll be more readily received as separate pull requests
