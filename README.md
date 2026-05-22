![Modified Lucid PREVIEW](https://github.com/user-attachments/assets/34ca3d1a-20ab-4f71-9aa8-0a3d6cd28206)

![Modified StarryNight PREVIEW](https://github.com/user-attachments/assets/3c9c4c33-d704-45e3-803e-3aaff9734bf5)

### ENJOY A BETTER SPOTIFY WITH THIS SPICETIFY SETUP!!

---

## IMPORTANT NOTES

- Use all the commands listed in this guide in PowerShell *(no admin needed)*

- In commands provided, make sure to replace `<noteslikethis>` for what they state

- The `zoomTheme.js` extension is just for the SpotifyDarkPurp Theme

---

### HOW TO INSTALL SPICETIFY

**Make sure [Spotify](https://www.spotify.com/ca-en/download/windows/) is installed via Desktop, NOT Microsoft store**

- Open PowerShell

- Run the following command:

```powershell
iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-cli/main/install.ps1 | iex
```

- Install Marketplace by using `y` when prompted

- Run backup:

```powershell
spicetify backup apply
```

You can also check out their page:

### [Spicetify Installation Guide + Info](https://spicetify.app/docs/advanced-usage/installation)

---

### HOW TO APPLY THEMES

- Move or copy the folders inside **My Modified Themes** into this location:

```text
C:\Users\%USERNAME%\AppData\Local\spicetify\Themes
```

- Run command:

```powershell
spicetify config current_theme <nameofthemefolder>
spicetify apply
```

For themes that come with more than one color scheme like Starrynight, you should specifiy it in the apply command. My modified Starrynight purple colorway uses color scheme `Base`, so use the following:

```powershell
spicetify config current_theme Starrynight
spicetify config color_scheme base
spicetify apply
```

---

### HOW TO INSTALL CUSTOM LOCAL FILE EXTENSIONS
*Use `Appdata\Roaming` locations for Custom Apps & Extensions, not `Appdata\Local`*

- Run command:

```powershell
spicetify config extensions <nameofextensionfile.itsformat>
```

---

### HOW TO INSTALL CUSTOM LOCAL FILE APPS
*Use `Appdata\Roaming` locations for local file Custom Apps & Extensions, not `Appdata\Local`*

- Place the custom app folder or file into this location:

```text
C:\Users\%USERNAME%\AppData\Roaming\spicetify\CustomApps
```

- Run command:

```powershell
spicetify config custom_apps <nameofcustomappfolderorfile>
```

---

### HOW TO APPLY MY SPICETIFY SETTINGS / SETUP

- Open Spotify

- Click the shopping cart *(Marketplace Icon)*

- Select the gear icon **Spicetify Settings**

- Under **Backup/Restore**, press **Open > Import From File**

- Select a setting in `Settings to Import` folder provided in this repo download

---

### IF USING THE LUCID THEME - HOW TO APPLY MY LUCID THEME SETTINGS

- Once you have Lucid Theme applied, select the tiny gear icon at the top right of Spotify

- Navigate to **Advanced** tab

- Open the `My Lucid Theme Setup.json` with Notepad

- Use `Ctrl + A` and copy all contents

- Paste into the **Import Configuration** section of Lucid’s Advanced Settings section

- You can customize the Lucid settings however you like from there :)

---

## NOTES

- Recommend to join the [Spicetify Discord](https://discord.com/invite/spicetify-842219447716151306)

- Spicetify usually needs to be updated whenever Spotify does, whenever Spicetify developers release an update use `spicetify update` then `spicetify apply`

- There is also a `Spicetify Commands.txt` included in this pack if you ever need

- This setup is just my personal favourite after having gone through everything like 20 times lol, enjoy!

---

## CREDITS

### [Spicetify Website](https://spicetify.app)

### [Spicetify Github](https://github.com/spicetify)

### [Lucid Theme](https://github.com/sanoojes/spicetify-lucid)

### [StarryNight Theme](https://github.com/spicetify/spicetify-themes/tree/master/StarryNight)

### [History in Sidebar](https://github.com/Bergbok/Spicetify-Creations/blob/main/CustomApps/history-in-sidebar/README.md)

All developers of Extensions, Custom Apps, & Snippets inside the settings import are credited in the Marketplace

---

## Found this useful?<img src="https://media.tenor.com/23NitOvEEkMAAAAj/optical-illusion-rotating-head.gif" width="30"><br>

[![Follow Me <3](https://img.shields.io/badge/Follow%20Me%20%3C3-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/landnthrn)   
[![Find More of my Creations on GitHub](https://img.shields.io/badge/Find%20More%20of%20my%20Creations%20on%20GitHub-311A82?style=for-the-badge&logo=github&logoColor=white)](https://github.com/landnthrn?tab=repositories)  
[![Gists: landnthrn](https://img.shields.io/badge/Gists-311A82?style=for-the-badge&logo=github&logoColor=white)](https://gist.github.com/landnthrn)  
[![Discord: landn.thrn](https://img.shields.io/badge/Discord-311A82?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/831735011588964392)  
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-311A82?style=for-the-badge&logo=buymeacoffee&logoColor=white)](https://buymeacoffee.com/landn.thrn/extras)  
[![PayPal](https://img.shields.io/badge/PayPal-311A82?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=K4PLHFVBH7X8C)

![](https://github-view-counter-1-0-0.vercel.app/api?username=landnthrn-Goat-Spicetify-Setup-for-Spotify&label=false&bgColor=20164C&color=6a5acd&iconColor=6a5acd)
