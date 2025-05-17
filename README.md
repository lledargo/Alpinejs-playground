# AlpineJS Playground
This is just a spot to have fun with and learn AlpineJS. So far there is only one project here.

### Timer App
index.html contains an html/JS webapp for managing timers which track elapsed time. It is not strictly necessary for this app to be contained in a single file, but I did have fun making it that way. 

Currently timers are stored as a JSON in either cookies or browser local storage, as chosen by the user on first viewing. The storage preference is always stored as a cookie. Note: though you can use this app by opening the html document directly in a browser, cookies will only be valid for the current session. For this reason it is recommended to serve the page with an http server (or give it a try at https://lledargo.github.io/Alpinejs-playground/).

In the future I may add additional storage options, different types of timers (countdowns, or timers which show lap history), ability to rename timers and adjust their epoch manually, better drag and drop animation, some actual styling, a debug mode. 

Tip: Try dragging the timers around 