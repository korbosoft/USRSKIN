# USRSKIN
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

Client-side customization for individual users' messages

## !! This theme REQUIRES [Vencord](https://github.com/Vendicated/Vencord) and the _ThemeAttributes_ plugin to function. !!

## Usage

### Installation
1. Enable the _ThemeAttributes_ plugin in Vencord.
2. Add `https://raw.githubusercontent.com/korbosoft/USRSKIN/main/USRSKIN.theme.css` to your online themes.

### Customization
At the moment, you'll have to make a Pull Request to this repository -- adding css styling to USRSKIN.theme.css -- in order to add customization to YOUR messages. I promise it'll get easier. Pinky swear
Heres an example that makes your message text red:
```css
/* YOUR_USERNAME_HERE */
[data-author-id="YOUR_USER_ID_HERE"] {
  [class^="contents_"] [class^="messageContent_"] {
    color: red !important;
  }
}
```
(Obviously, you'll have to fill in your username and user ID in place of `YOUR_USERNAME_HERE` and `YOUR_USER_ID_HERE` respectively. You can find your user ID by enabling developer mode in Discord's settings, clicking your profile picture in the bottom left, and clicking "Copy User ID". _This is **NOT** personal information, and is accessable by anyone._)

## Legal

USRSKIN © 2024 by Korbin Marshall is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
