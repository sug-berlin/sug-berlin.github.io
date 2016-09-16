# SailfishOS Meetup Berlin

Tis repository contains the SailfishOS-Meetup-Berlin.github.io page

# Update and publish the page

There is a built in tool at github.com that is used to generate the [SailfishOS Meetup Berlin Page](http://sailfishos-meetup-berlin.github.io).

## Updating

Simply update the [content.md](https://github.com/SailfishOS-Meetup-Berlin/sailfishos-meetup-berlin.github.io/blob/master/content.md) file of this repository. If not part of this github organisation you also could create a pull request containing your changes.

## Publishing

- Go to the [automatic page generator](https://github.com/SailfishOS-Meetup-Berlin/sailfishos-meetup-berlin.github.io/generated_pages/new?utf8=%E2%9C%93) within the setting dialog of the Sailfish Meetup Berlin repository page
- Copy the text from [content.md](https://github.com/SailfishOS-Meetup-Berlin/sailfishos-meetup-berlin.github.io/blob/master/content.md) and push the publish button
- Check the [published website](http://sailfishos-meetup-berlin.github.io) if everything is as expected

# Use jekyll instead of the automatic page creator

- Why? Page creator overwrites everything that is not part of the markdown code pasted. E.g. it's not possible to change the [download button](https://github.com/sailfishos-Meetup-berlin/blob/master/index.html#L17) on top of the generated page.

## Install jekyll

Follow the [installation description](https://jekyllrb.com/docs/installation/). It might be necessary to install the dev package as well (e.g. in Ubuntu 16.04: `sudo apt-get install ruby3.3-dev`). Afterwards jekyll could be installed (e.g. in Ubuntu 16.04: `sudo gem install jekyll`).

# Contributing

We are always looking for ideas, findings and people who would like to join our meetups or projects. If you would like to add content to the page just create a pull request for your version of the [content.md](https://github.com/SailfishOS-Meetup-Berlin/sailfishos-meetup-berlin.github.io/blob/master/content.md) or open an [issue](https://github.com/SailfishOS-Meetup-Berlin/sailfishos-meetup-berlin.github.io/issues).
