This uses the native firefox vertical tabs and the default bookmarks bar.

All files go in the chrome directory.

In about config set the below: <br>
widget.windows.mica to true <br>
widget.windows.mica.toplevel-backdrop to 2

I use MicaForEveryone with ONLY "Enable Blur Behind" turned on.

If you bookmark folders look off center right click and clear the folder name and save or don't and suffer :)

Edit the below code in userChrome.css for your own background colour or use a theme or Adaptive tab Color addon. <br>
#main-window {
  background: rgba(27, 127.5, 125, 1) !important;
}
