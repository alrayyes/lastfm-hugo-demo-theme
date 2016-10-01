Last.fm Hugo Demo Theme
=================

This is a simple demo theme that shows how to use [last.fm](https://last.fm) with [hugo](https://gohugo.io).

Installation
------------

Inside the folder of your Hugo site run:

    $ mkdir themes
    $ cd themes
    $ git clone https://github.com/alrayyes/lastfm-hugo-demo-theme

For more information read the official [setup guide][setup_guide] of Hugo.

### The Config File ###

Add the following to your config.toml:

```toml
[Params]
username = "<username>"
apikey = "<apikey>"
limit = "<limit>"
```

Username is your [last.fm](https://last.fm) username and the limit is the number of scrobbles you want to see (max 200). You can get an api key by creating an api account [here](http://www.last.fm/api/account/create).

Used Libraries
---------

- [Boostrap](https://getbootstrap.com/)
- [Momentjs](http://momentjs.com/)
- [Jquery](https://jquery.com/)

Contributing
------------

Report any bugs using the [issue tracker][issue_tracker]. Submit your own bug
fixes or feature additions via a [pull request][pull_request].

License
-------

This theme is released under the MIT License. For more information read the
[license][license].

[setup_guide]: http://gohugo.io/overview/installing/
[issue_tracker]: https://github.com/alrayyes/lastfm-hugo-demo-theme/issues
[pull_request]: https://github.com/alrayyes/lastfm-hugo-demo-theme/pulls
[license]: https://github.com/alrayyes/lastfm-hugo-demo-theme/blob/master/LICENSE.md
