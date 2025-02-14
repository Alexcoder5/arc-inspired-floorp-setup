# Arc Inspired Floorp + Sidebery setup

If you like it (I can see it by amount of stars on the project ⭐️) I can make it easier to customize.

<img style="display: block" src="img/preview.png" alt="preview" width="1000"/>

## How to install

1. Download and unzip the project:

<img style="display: block" src="img/download-project.png" alt="how to download" width="600"/>

<h3>Floorp</h3>

2. Download and install Floorp.
3. Go to `about:profiles`. Search for **Profile: default-release** and press **Show in Finder**.
<img style="display: block" src="img/floorp-profile.png" alt="how to download" width="600"/>

4. Go to a folder ending with `.default-release` and find a `chrome` folder (create it if needed).
5. Drop `userChrome.css` inside the `chrome` folder (replace or create if needed).
6. Restart Floorp.
7. Go to Floorp settings: <br>
    a. **Browser Manager sidebar** → **Show the Browser Manager Sidebar** - off.<br>
    b. **Design** → **Tab Bar** → **Optimise browser for Vertical Tab Bar**.<br>
    c. *(optional)* **Design** → **Tab Bar** → **Browser appearance** → **Firefox Proton UI**.<br>
    d. *(optional)* **Home** → **Show blank page and disable background**.<br>
7. View → Toolbar → Customise toolbar:

    a.`bookmarks toolbar items` (drag it from bookmarks bar) - `flexible space x3` - `search` - `flexible space x3` - `whatever you like here`. <br>
    <img style="display: block" src="img/toolbar.png" alt="toolbar" width="800"/>
    b. On the bottom select **Toolbars** → **Bookmarks Toolbar** → **Never Show**.

    Note: *Add bookmarks to bookmarks toolbar without name so only icon is displayed*.

# Sidebery

8. Install Sidebery add-on.
9. Go to **Settings** → **Help** → **Import addon data** → select `sidebery-settings.json`.

Note: *I removed the close tab button and close it with double click (you can adjust this and many other things from settings).*

## Nice to have
### Open Bookmarks in a new tab

1. Bring up Firefox's Advanced settings/config page by typing the following into your URL bar: `about:config`.
2. Accept the risk and continue
2. Search `browser.tabs.loadBookmarksInTabs`.
3. Locate `browser.tabs.loadBookmarksInTabs` and double-click it to change the value from `false` to `true`.

<hr/>

### If you find any bugs just post it under the `issues` in this project. I'll fix it when I have time.
### If you want to support me and make me spend more time on this project: https://www.buymeacoffee.com/alex_coder