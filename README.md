## Single Column

Single Column is a blank Ghost theme by Precode.io. Use it to create your own Ghost theme.

## Copyright & License

Designed and developed by Precode.io.
Copyright (c) 2014 Precode.io - Released under the GPL License.

## How to install Single Column

Ghost themes live in `content/themes/`
After you have downloaded Single Column, extract it and place it in content/themes alongside the Casper default theme.

To switch to your newly added theme:

 * Restart Ghost. At the moment, Ghost won't notice that you've added a new folder to content/themes so you'll need to restart it

 * Login to your Ghost admin, and navigate to `/ghost/settings/general/`

 * Select your Theme name in the 'Theme' options dropdown

 * Click 'Save'

 * Visit the frontend of your blog and marvel at the new theme

If you are new to using Ghost, we recommend checking out the following:
 * Ghost Guide: http://docs.ghost.org/
 * Switching Themes: http://docs.ghost.org/themes/
 * Publishing with Ghost: http://docs.ghost.org/usage/writing/

## Make Single Column your own Ghost theme

The purpose of Single Column is to make it easy for anyone to create a Ghost theme.

## What files to edit

The primary file to edit is the `default.hbs` file. This file includes footer credit links. If you are planning to create an entirely new theme, you'll need to update the following:

  * `package.json` This stores the name of the theme in Ghost.
  * `default.hbs` This file includes footer credit links that need to be updated.
  * `screen.css` We've included theme name and author information in the stylesheet.
  * You'll also need to rename the primary directory of the `single-column` theme.

