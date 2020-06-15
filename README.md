# StartTerminal
## Directions
1. Download Zip of repo & make sure all the file are in a folder.
2. Navigate to your browsers extension manager (Chrome://extensions or brave://extensions, etc)
3. Turn on developer mode and select load unpacked
4. Navigate and select project folder.
5. The extension will now be installed. Turn off developer mode.

## Commands
- Most common ones can be found using `ls`
- Search commands include 
- - `[search term] -g` for a google search
- - `[search term] -y` for a youtube search
- - `[search term] -w` for a wikipedia search
- - `[search term] -v` for a vimeo search
- - `[search term] -i` for a google image search
- - `[search term] -m` for a wolfram alpha search
- You may also just type in a domain such as `github.com` to be redirected there
- 4chan boards can be quickly visited by typing in their extension. Ex: `/b` or `/wsg`

## Setup
### Weather
- Type `weather` to get directions in the CMD windows
- Get a [weather api key](https://openweathermap.org/appid) by signing up for free
- type `edit .weatherkey` and paste the api key
- Save by hitting `esc`, and typing `close'
- It may take several hours for your api key to become active.
- Type `locate` to save your coordinates (location required & only collected when this command is executed)
- Weather should work :)
### Config File
- To change the username: `edit .config` and add `userName:XX`
- To change the computer name: `edit .config` and add `userMachine:XX`
- Presented in the terminal windows as `userName@userMachine`
- One per line. No empty lines. Save as before by hitting `esc`, and typing `close'
### Bookmarks
- Type `edit .bookmarks`
- Add one per line in this format `google https://www.google.com/`
- One per line. No empty lines. Save as before by hitting `esc`, and typing `close'
- You may visit the bookmarks by simply typing their name into the prompt

## Contributing
### Files
- bin.js -> Functions & Welcome text
- change.js -> Used to force command promp focus away from the browsers url bar.
- edit.js -> Functions related to managing virtual files
- index.html -> The main html page.
- manifest.json -> Settings for chromium extension
- scrollbar.css -> Scrollbar styles
- start-index.html -> HTML file used to redirect to index.html / Part of changing focus to terminal page
- style.css -> Main styles
- term.js -> Main JS file. Conducts startup


Credits: Based on the work by [vapor-404](https://github.com/vapor-404/vapor-404.github.io/tree/master/terminal)
