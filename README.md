# GraphGuard Proxy landing page

## 💿 Setup

Make sure you have installed [Node.js](https://nodejs.org/en/).<br>
Install [SASS](https://sass-lang.com/) by running the command `npm i -g sass` in your console.<br>
If you encounter an error and you are using macOS, run this command as the super user with `sudo`.

## 🧰 Development

To have a live preview of the project, use VS Code with the recommended extension ["Live Server"](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).<br>
Start a SASS file watcher in your console inside this directory by `sass --watch --no-source-map style.sass:public/style.css`.

You can get futher information by running `sass -h`.

## 🔨 Deployment

To compile the SASS code into CSS code, run the following command inside this directory:
```bash
sass --style=compressed --no-source-map --stop-on-error style.sass:public/style.css
```
The directory `/public` is now ready to be deloyed.
