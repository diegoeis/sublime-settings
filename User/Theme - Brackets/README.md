# Brackets Theme

Custom UI theme for _Sublime Text_ inspired by the _Brackets_ Editor. It is based on [Soda Theme](http://buymeasoda.com/) by Ian Hill.


## Design

![Brackets Theme](https://github.com/SalvoGentile/brackets-theme/raw/master/Resources/Images/Brackets.png)


## Installation

This theme is designed to work with the latest [development build](http://www.sublimetext.com/dev) of Sublime Text.

### Using Sublime Package Control

Because we are still developing this theme, it is not yet available through the [Sublime Package Control](http://wbond.net/sublime_packages/package_control). It propably will be later though.

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text 2 application settings area.

You can locate your Sublime Text 2 `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/SalvoGentile/brackets-theme/ "Theme - Brackets"

### Download Manually

* Download the files using the GitHub .zip download option;
* Unzip the files and rename the folder to `Theme - Brackets`;
* Copy the folder to your Sublime Text `Packages` directory.


## Activating the theme

To configure Sublime Text 2 to use the theme:

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`;
* Add (or update) your theme entry to be `"theme": "Brackets.sublime-theme"`.

### Example User Settings

    {
        "theme": "Brackets.sublime-theme"
    }


## Bonus Options

### Syntax Highlighting Colour Schemes

The Brackets screenshot uses the [Br4ckets Color Scheme](https://github.com/l4ci/Br4ckets-Theme).

![Br4ckets Color Scheme](https://github.com/l4ci/Br4ckets-Theme/raw/master/Images/Br4ckets-Day.png)

If you'd like to use the syntax highlighting schemes shown in the screenshots:

* Download [the scheme here](https://github.com/l4ci/Br4ckets-Theme/archive/master.zip);
* Unzip and place the extracted `tmtheme` files in the Sublime Text `Packages/User` folder;
* Enable the colour scheme via `Preferences -> Color Scheme -> User`.

### Code Font

The code font shown in the screenshot is [Source Code Pro](https://github.com/adobe/source-code-pro).


## License

Brackets Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so. 