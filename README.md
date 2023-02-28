# JSExpertMax Gesture Controller - Week JS Expert 7.0

## Preview

<img width=100% src="./initial-template/assets/demo-template-lg.gif">

## Pre-reqs

- This project was created using Node.js v19.6

## Running

- Run `npm ci` in the folder containing `package.json` to restore the packages
- Run `npm start` and then go to your browser at [http://localhost:3000](http://localhost:3000) to view the above page

## Checklist Features

- Titles List

  - [] - Search field should not crash when typing search term
  - [] - Should draw hands on screen and make background elements still clickable 🙌
  - [] - Should trigger scroll up when using open palm 🖐
  - [] - Should trigger scroll down when using closed palm ✊
  - [] - Should trigger click on nearest element when using pincer gesture 🤏🏻
  - [] - When moving elements on the screen, should trigger **:hover** event on elements in context

- Video Player
  - It should be possible to play or pause videos with the blink of an eye 😁 - All Machine Learning processing should be done via Web worker
  - [] - All Machine Learning processing should be done via Web worker

### Challenges

- Class 01 - Differentiate blink between right and left eye and update log to show which eye blinked.
- [] - Class 02 - Recognize individual hand gestures and print on the log
- [] - Class 03 - To be defined
- [] - Class 04 - To be defined

### Links shown in the classes:

- I have gathered all the links in [references](./references.md)

### FAQ

- browser-sync is throwing errors in Windows and never starts:
  - Solution: Replace browser-sync with http-server.
    1. install the **http-server** with `npm i -D http-server`.
    2. in package.json delete the whole `browser-sync` command and replace it with `npx http-server .`
    3. now the project will be running on :8080 so go in the browser and try to access http://localhost:8080/
       The only thing is, the project won't restart when you change some code, you'll need to hit F5 every time you change something

### Credits to Layout

- Interface based on the project [Streaming Service](https://codepen.io/Gunnarhawk/pen/vYJEwoM) by [gunnarhawk](https://github.com/Gunnarhawk)
