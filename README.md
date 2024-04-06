# ChiptuneJS in browser
Play tracker files in your browser with Javascript right in your browser!

## How it works
It's actually quite simple. This website or project uses ChiptuneJS from [here](https://github.com/deskjet/chiptune2.js/) and libopenmpt from [here](https://lib.openmpt.org/libopenmpt), along with the use of [emscripten](https://github.com/kripken/emscripten) for the websockets. To make it work, select your tracker file from the "Select file" area (has to be tracker related format!) and the website will play your file in just three seconds! You can interact with the tracker file using the controls on your screen as well! The website uses the websocket for the libery in some cases, but it depends if you have that support for your browser of course.

## Additonal information
This site is mainly a fork from this repo [here](https://github.com/deskjet/chiptune2.js), only with a few tweeks and features on top of it. The theme or CSS libery is using Bootstrap 5, only with a few modifications I added myself to make it look better (at least). You can run this yourself on your own server or dev enviroment. I use Live Server with Visual Studio Code, which should give you a good start on using this locally. You are free to modify it however you please, any of your changes should **NOT** be pushed to this repo. If you want to make a contribution to this project/repo, please email me on that topic.
