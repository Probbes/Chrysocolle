## This project is in beta
![/assets/chrysocolle.png](/assets/chrysocolle.png)
### An emulator and game manager made in rust using dioxus with cloud integration with git for save management
- Auto detect games inside app folder
- Manually add emulators and assign them to games for quick launch
- When the game launches, automatically transfer saves from repository to the emulator save folder
- When the app is closed, automatically transfer the saves files inside the repo and push

### How to use
The app is not fully ergonomic yet, you have to
- At the first start of the app, choose the folder you want for the app to use
- Clone your repo inside the "Save" folder that the app created
- Add you git repo name and link to the app under the "Cloud" tab
- Add an emulator by specifying its save folder, location and more
- Finally, assign an emulator to a game inside the "Game" tab

### Known issues
- The icon does not appear on linux
- When settings changes, the change does not propagate

### TODO
- Add folder sorting
- Better ergonomics
- Switch from git command to git2 crate
- Create an update checker