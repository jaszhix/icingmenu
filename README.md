Icing Menu
=============

This is a fork of the default Cinnamon 3.2 menu applet, with more customization options, and some optimizations.

### Features

 * Set the height and width of the menu.
 * Accurate drill down of search results.
 * Move the search box and app info area to the top, bottom, or hide them.
 * Ability to hide the scrollbar.

Tested on Cinnamon 3.0.7 and Cinnamon 3.2.2.

### Contributing

*  Use [Node 6.x](https://github.com/nodesource/distributions).
```sh
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
sudo apt-get install -y nodejs
```
*  Install node modules: ```npm install```
*  Install gulp globally if you haven't already. ```sudo npm install -g gulp```
*  Start transpile watch task: ```gulp spawn-watch```
*  Monitor logging output: ```tail -f -n100 ~/.cinnamon/glass.log```