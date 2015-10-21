#Terminal-gif

This is a small utility to wrap all the stages required for recording your terminal inputs into a pretty gif.

I've only tested it on OSX so any contributions or bugfixes welcome.

##Demo

![Demo of using terminal-gif](https://raw.githubusercontent.com/michaeldfallen/terminal-gif/master/demo.gif)

##Installation

###OSX

```sh

brew install imagemagick
brew install ttyrec
git clone git@github.com:michaeldfallen/terminal-gif.git


```

The `terminal-gif` script itself will handle initialisation of ttygif.

To install Terminal-gif to `/usr/local/bin` for easy access to the script run:

```sh
./terminal-gif install
```

##Usage

To use simply call the script with a file name:

```sh
terminal-gif giffy.gif
```

Then start typing your commands. Once you are ready to stop and create the gif just execute the command `exit`

