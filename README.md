Last.fm Hugo Demo
=================

This is a simple demo that shows how to use [last.fm](https://last.fm) with [hugo](https://gohugo.io).

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
limit = "200"
```

Username is your [last.fm](https://last.fm) username and the limit is the number of scrobbles you want to see (max 200). You can get an api key by creating an api account [here](http://www.last.fm/api/account/create).

[bootstrap]: https://getbootstrap.com/
[momentjs]: http://momentjs.com/
[jquery]: https://jquery.com/
[issue_tracker]: https://github.com/alrayyes/lastfm-hugo-demo-theme/issues
[pull_request]: https://github.com/alrayyes/lastfm-hugo-demo-theme/pulls
[license]: https://github.com/chipsenkbeil/grid-side/blob/master/LICENSE