# GraphGuard Proxy landing page

## 💿 Setup

Make sure you have installed [Node.js](https://nodejs.org/en/).<br>
Install [Stylus](https://stylus-lang.com/) by running the command `npm i -g stylus` in your console.<br>
If you encounter an error and you are using macOS, run this command as the super user with `sudo`.

## 🧰 Development

To have a live preview of the project, use VS Code with the recommended extension ["Live Server"](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).<br>
Start a stylus file watcher in your console inside this directory by `stylus -w stylus.styl`, where `-c` just compresses (minfies) the output and `-w` watches the file.<br>
For debugging purposes you may even run without the flag `-c`, to have not minfied CSS.

You can get futher information by running `stylus -h`.

## 🔨 Deployment

Inside this directory run `stylus -c style.styl` to transpile the Stylus code into CSS code.<br>
Now deploy everything except the file `style.styl`, as it is transpiled into the CSS file `style.css`.

Done.
