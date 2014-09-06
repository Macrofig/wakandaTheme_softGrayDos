# Soft Gray Dos

It's like Soft Gray, but with a "Dos" at the end.

Also, there's some tiny things fixed. Like radio buttons all looking selected and text alignment as well.

## How to Install

Wakanda creates a Theme folder during install. More info [here](http://doc.wakanda.org/Architecture-of-Wakanda-Applications/Custom-Theme.200-1024475.en.html).

### Step One

Clone into your Wakanda Studio's Theme folder.

```batch
cd WAKANDA_HOME/Themes
git clone https://github.com/Knowledge-Sharing-Systems/wakandaTheme_softGrayDos.git softGrayDos
```
Or you can [browse to the repo](https://github.com/Knowledge-Sharing-Systems/wakandaTheme_softGrayDos) and click the "Download ZIP" link. Make sure you rename the zipped folder to `softGrayDos`.

### Step Two

Open desired page in Wakanda. Select the `body` element. Click on the "Design" tab in the properties pane. Select `softGrayDos` from the list of available themes.

You may need to restart Studio in order for the theme to display properly in the editor.

You should also clear the cache of your browser and restart Wakanda Server.

### Step Three

Repeat Step Two for all applicable pages in the project.


## How to Update

You should *star* this repo so you get nifty messages when the repository is updated.

### Step One

If you cloned from Github:

```batch
cd WAKANDA_HOME/Themes/softGrayDos
git pull
```
This will get mad if you have edited the theme at all. You can stash or revert (or pull request!) your changes then do the above command.

If you downloaded the ZIP, you will have to download it again.

**Make sure that the theme files are directly inside the folder `softGrayDos`!!**  Wakanda will not display the theme properly otherwise.
