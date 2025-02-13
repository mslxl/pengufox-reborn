# pengufox-reborn

**pengufox is a Firefox config that makes Firefox more beautiful, more secure and better protect privacy by using FirefoxCSS and disabling all telemetry.**

https://github.com/pznguin-kyun/pengufox/assets/123321507/1c9a01f5-2b23-491d-a58e-0b830a40a966

## Features

- Beautify Firefox with FirefoxCSS
- Turn off all telemetry, studies
- Add calculator to address bar
- Make Firefox suckless

## Installation

### Install automatically (Linux only)

```bash
git clone https://github.com/mslxl/pengufox-reborn pengufox
cd pengufox
./pengufox-installer.sh
```

### Install manually

- Clone this repository or download the [zip file](https://github.com/mslxl/pengufox-reborn/archive/main.zip)

```bash
git clone https://github.com/mslxl/pengufox-reborn pengufox
```

- Extract file (if you download the zip file)

- Copy all files and folders in penguinFox and paste to your profile folder
  - ```~/.mozilla/firefox/######.default-#####$``` (Linux)
  - ```/Users/[USERNAME]/Library/Application Support/Firefox/Profiles/######.default-######``` (macOS)
  - ```C:\Users\[USERNAME]\AppData\Roaming\Mozilla\Firefox\Profiles\######.default-######``` (Windows)

- Restart Firefox and enjoy

## Uninstall

- Just go to your profile folder and delete ```user.js``` and ```chrome``` folder

---

### Work with treestyle tabbar/sidebery

Copy the content of [userChrome.extra.css](files/chrome/userChrome.extra.css) to `chrome/userChrome.css` under your profile folder.
This would hide firefox's titlebar, but toolbar still will be show when hover on it.

![](https://private-user-images.githubusercontent.com/11132880/412812033-63975b61-75d2-4aa8-8993-cf0b28d5ff43.gif?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Mzk0MzgyNDQsIm5iZiI6MTczOTQzNzk0NCwicGF0aCI6Ii8xMTEzMjg4MC80MTI4MTIwMzMtNjM5NzViNjEtNzVkMi00YWE4LTg5OTMtY2YwYjI4ZDVmZjQzLmdpZj9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTAyMTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwMjEzVDA5MTIyNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTM2Y2Q4ZmYxZjZmMzcwMTcyYTE5OGE5ODRiMGU1NTRkNDg4OWQyOTZkMmYwMTVmZjJjOTY5NzBjMjE2MjYxNGYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.aNO8Q9TPPCUO1e8YGl5OPtduYoDQpyRi9axIHt7A7pA)

---

## Work with nightTab

![Screenshot_2023-07-15_20-47-24](https://github.com/pznguin-kyun/pengufox/assets/123321507/f52fe4ea-ac6c-49c4-a75c-cef1c9e8b27c)

### Install nightTab config

- Install [nightTab](https://github.com/zombieFox/nightTab)
- Download my nightTab config [here](https://github.com/pznguin-kyun/pengufox/blob/main/pznguin-kyun's%20nighttab%20config.json)
- Choose `Settings > Data > Restore > Import from file`
- Choose my nightTab config and apply it


---

## Contributions

1. Fork this project.
2. Edit files, add extensions, ...
3. Make a pull request.
