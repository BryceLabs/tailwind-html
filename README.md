In the root directory run:

`npm install`

To run a process that will compile the css file when a change is detected run:

`npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch`

and leave it running.

You can run a live-server to make changes and have the browser update in real-time. My one issue with this is that I need to save twice most of the time because the live server reloads before the css is compiled:

`npm install -g live-server`

From the root directory of the project run:

`live-server`
