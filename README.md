# F L Y E R F O X

_An opinionated Firefox userChrome.css optimized for macOS. Bret Michael's slider is still in beta unfortunately._

![FlyerFox Tool Bars Hidden](screenshot_0.png)
![FlyerFox URL Bar & Tab Bar Shown](screenshot_1.png)
![FlyerFox 100% Width URL Bar](screenshot_2.png)


## Features

- **Minimal**: No toolbars unless you want them. When they are shown they try not to be greedy.
- **Practical**: Cmd|Ctrl - L or hover to focus the URL and Tab Bar.
- **Clean**: Many elements are hidden until they need to be see.
- **Flexible**: Support for compact, normal, and touch densities.
- **Themeable**: You can still using custom themes with full compatibility.
- **Customizable**: You are able to change settings like navbar's width, animation speed, and hidden elements at the top of the userChrome.css file.


## Installation

1. In the searchbar, type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`** and change it to **True**.
3. Go to your Firefox profile:
   - In the searchbar, type `about:support` and press `Enter`.
   - Search for **`Profile Directory`** and click on **`Open Directory`** button.
4. Create a folder and name it **`chrome`** (with lowercase).
5. Paste userChrome.css file into the folder.
6. Restart Firefox
7. Enjoy your new Firefox!


## Customization

- You can change some settings inside the userChrome.css file.
- Use `--navbarWidth` variable to change the width of the navbar (you can use px units for a fixed width, or vw units for a percentage one).
- Use `--animationSpeed` variable to change (or disable) animations.
- Hide or show the elements you want by commenting or uncommenting them:
```css
/* This element is hidden */
/* "Shield" icon */
#tracking-protection-icon-container {display: none !important}

/* This element is visible */
/* This is the "Search with" indicator on the urlbar */
/* #urlbar-search-mode-indicator {display: none !important} */
```
## Projects I Like 
- **Pywal Fox**: ![Frewacom/pywalfox](https://github.com/Frewacom/pywalfox) 
   - A Dynamic Theme Color Scheme for Firefox which uses Pywal as a backend.
- **Pywal**: ![dylanaraps/pywal](https://github.com/dylanaraps/pywal)  
   - A Tool Used to Generate Color Themes for Almost Everything and Farm Karma on ![r/UnixPorn](https://www.reddit.com/r/unixporn)
- **SpaceBar**: ![cmacrae/spacebar](https://github.com/cmacrae/spacebar)
   - A Status Bar for Yabai.
- **Yabai**: ![koekeishiya/yabai](https://github.com/koekeishiya/yabai)
   - A Tiling Window Manager for macOS. 
### Feel free to donate to any of these great projects or to your favorite charity. 

