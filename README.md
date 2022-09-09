# SAFE fonts bug repro

Demonstrates a bug when referring to an npm-installed font via SCSS

Before installing the font (https://github.com/mattgallagher92/safe-fonts-bug-repro/commit/b8254a7ae5e2612f67bc10b2ea20ea983a856e7e):
![Standard SAFE Todo list. The targeted item does not have the correct typeface.](https://user-images.githubusercontent.com/46973220/189375920-99815df8-609c-42cb-b991-91889c9afd73.png)

After installing the font (https://github.com/mattgallagher92/safe-fonts-bug-repro/commit/14c86f432ed34f1f89d7c670434440ca49628fcb):
![Browser console showing OTS parsing errors](https://user-images.githubusercontent.com/46973220/189376348-b90a5c02-4020-434e-8ba1-19643cd09857.png)

After updating webpack config (https://github.com/mattgallagher92/safe-fonts-bug-repro/commit/9037df9354f567ce8ed613a4eb68fb553bcdef26):
![Standard SAFE Todo list. The targeted item has the correct typeface](https://user-images.githubusercontent.com/46973220/189376579-8334cb7b-e638-42d5-b567-4d2988d5545d.png)
