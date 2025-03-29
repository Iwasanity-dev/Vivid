### **Modified version of Vivid for Jellyfin WebUI**

[Go to installation](#installation)

Also available as a [Userstyle](https://userstyles.world/style/21514/vivid-oled-modified)

---

### **Vivid Base Theme**

<img src="./images/homepage.png" alt="homepage" width="100%"/>
<img src="./images/Details.png" alt="details" width="100%"/>
<img src="./images/movies.png" alt="movies" width="100%"/>
<img src="./images/dashboard.png" alt="dashboard" width="100%"/>
<img src="./images/login.png" alt="login" width="100%"/>

### Base Theme
`@import url('https://cdn.jsdelivr.net/gh/LitCastVlog/vivid-mod@latest/CSS/vivid-theme.css');`

### Vivid-mod (Add this below the Options)
`@import url('https://cdn.jsdelivr.net/gh/LitCastVlog/vivid-mod@latest/CSS/vivid-mod.css');`

 - B/W Logo (credits: [RoyalxZealot](https://www.steamgriddb.com/logo/128502))
 - Squared Dark/Transparent Indicators
 - Smaller Cast/Crew section
 - Hide "Upcoming on TV" and "Next Up" section in Season View

### Options (Add these below the base theme)
- Disable static left drawer 
    - `@import url('https://cdn.jsdelivr.net/gh/LitCastVlog/vivid-mod@latest/CSS/disable-static-drawer.css');`
- Themes:
    - Seafoam
        - `@import url('https://cdn.jsdelivr.net/gh/LitCastVlog/vivid-mod@latest/CSS/theme-seafoam.css');`
        - <img src="./images/seafoam.png" alt="seafoam-theme" width="40%"/>
    - Coral
        - `@import url('https://cdn.jsdelivr.net/gh/LitCastVlog/vivid-mod@latest/CSS/theme-coral.css');`
        - <img src="./images/coral.png" alt="coral-theme" width="40%"/>
    - Snow
        - `@import url('https://cdn.jsdelivr.net/gh/LitCastVlog/vivid-mod@latest/CSS/theme-snow.css');`
        - <img src="./images/snow.png" alt="snow-theme" width="40%"/>
    - OLED
        - `@import url('https://cdn.jsdelivr.net/gh/LitCastVlog/vivid-mod@latest/CSS/theme-oled.css');`
        - <img src="./images/homepage-oled.png" alt="homepage-oled" width="100%"/>
        - <img src="./images/Details.png" alt="details-oled" width="100%"/>

---

### **Installation:**

---
### Easy install (one liner) 
`@import url('https://cdn.jsdelivr.net/gh/LitCastVlog/vivid-mod@latest/CSS/vivid-mod-oneliner.css');`

*if the logo is too big or doesn't apply (iOS, Android), append this line as well (per client)* 
* `.pageTitleWithDefaultLogo {
    background-image: url("https://cdn2.steamgriddb.com/logo/3f44f3018ff71ff4a7d22a98f3babb55.png");
    background-size: 50%; }`

**Server-wide install:**
* Click the hamburger icon (Top left)
* Navigate to "Dashboard" (If you don't see this, make sure you are signed in to your admin account)
* Navigate to "General"
* Near the bottom, under "Custom CSS code", paste the `@import url` for the base Vivid theme
    * Example:
    * <img src="./images/install-server-base.png" alt="install-server-base" width="80%"/>
* Optional - Paste the `@import url` for any options / themes you may want
    * Example:
    * <img src="./images/install-server-options.png" alt="install-server-options" width="80%"/>
* Click "Save"

---

**Single client install:**
* Click the hamburger icon (Top left)
* Navigate to "Settings"
* Navigate to "Display"
* Near the middle, under "Custom CSS code", paste the `@import url` for the base Vivid theme
    * Note - 
        * If there is any server-wide custom CSS, you may want to enable "Disable server-provided custom CSS code", as the two themes WILL interfere with each other
    * Example:
    * <img src="./images/install-client-base.png" alt="install-client-base" width="80%"/>
* Optional - Paste the `@import url` for any options / themes you may want
    * Example:
    * <img src="./images/install-client-options.png" alt="install-client-options" width="80%"/>
* Click "Save"
