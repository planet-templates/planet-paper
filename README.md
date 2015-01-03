# `paper` -  Pluto Planet Template Pack

## What's Pluto?

Pluto is a feed reader that lets you build web pages from published
web feeds. More [Pluto Project Site »](http://feedreader.github.io)


### Style Settings

~~~
$font-family: Helvetica, sans-serif;

$primary-color: black;

$item-body-color: #222222;
~~~

[(Source: `css/_settings.scss`)](css/_settings.scss)


## Usage

### Try It Yourself - How To Use the Top Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ pluto install paper

Or as an alternative clone the template pack using `git`. Issue the commands:

    $ cd ~/.pluto
    $ git clone git://github.com/planet-templates/planet-paper.git

To check if the new template got installed, use the `list` command:

    $ pluto list

Listing something like:

    Installed templates include:
       top (~/.pluto/paper/paper.txt)

Showtime! Let's use the `-t/--template` switch to build a sample Planet Ruby. Example:

     $ pluto build ruby.yml --template paper     or
     $ pluto b ruby -t paper

Open up the generated planet page `ruby.html` in your browser. Voila. That's it.



## License

The `paper` scripts and templates are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [Planet Pluto and Friends Forum/Mailing List](http://groups.google.com/group/feedreader).
Thanks!

