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

## Setup
### Weather
- Type `weather` to get directions in the CMD windows
- Get a [weather api key](https://openweathermap.org/appid) by signing up for free
- type `edit .weatherkey` and paste the api key
- Hit the `esc` key and type save. Press enter & then 're'. You may need to confirm the reload.
- It may take several hours for your api key to become active.
- Type locate to save your coordinates (location required & only collected when this command is executed)
- Weather should work :)
### Config File
- To change the username: `edit .config` and add `userName:XX`
- To change the computer name: `edit .config` and add `userMachine:XX`
- Presented in the terminal windows as `userName@userMachine`
- One per line. No empty lines. Save as before (hit `esc`, type save, hit `enter` amd type `re` to reload the page)

Credits: Based on the work by [vapor-404](https://github.com/vapor-404/vapor-404.github.io/tree/master/terminal)
