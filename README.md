# Sample Progressive Web Application (PWA)
Just trying out some basic functionality of PWA's in-general by creating a sample app
## manifest.json Terminology
1. **name** --> The title of the app. This is used when prompting the user to install the app. It should be the full title of the app.
2. **short_name** --> Is the name of the app as it will appear on the app icon. This should be short and to the point.
3. **lang** --> The default language the app is localized in.
4. **start_url** --> Tells the browser which page to load up when the app is launched.
5. **display** --> The type of shell the app should appear in. For our app, we are using standalone to make it look and feel like a standard native app.
6. **background_color** --> The color of the splash screen that opens when the app launches.
7. **theme_color** --> Sets the color of the tool bar and in the task switcher.

Add the manifest in the index file 
```html 
<link rel="manifest" href="/manifest.json">
```