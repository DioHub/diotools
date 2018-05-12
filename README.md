# DIO-TOOLS

## DESCRIPTION

DIO-Tools is a small extension for the browser game Grepolis. (approved in most Grepolis markets) It offers, among other things, some displays, a smiley selection box for text input fields, trade options and some changes to the layout.

The first release was on 26th November 2013.

It all started with a simple smiley script, because I was too lazy to dig out the cute green smileys every time.

Over time, more and more features were added to the script. There are more than 20 features now.

## INSTALLATION

At first you need a userscript addon to install DIO-Tools on your browser. In the following list you can see which specific addon you need for your browser. You only need to click on the link to be redirected to the installation page. You can skip this step if it is already installed.

* [Google Chrome](https://www.google.com/chrome/) needs [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en)
* [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/) needs [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)
* [Opera](https://www.opera.com/) needs [Tampermonkey](https://addons.opera.com/en/extensions/details/tampermonkey-beta/?display=en)
* [Maxthon](http://maxthon.com) needs [Violentmonkey](http://extension.maxthon.com/detail/index.php?view_id=1680&category_id=)
* [Safari](https://support.apple.com/downloads/safari) needs [Tampermonkey](https://safari.tampermonkey.net/tampermonkey.safariextz)

After installing the addon you need to restart your browser. Finally you can install [DIO-Tools](https://diotools.de/downloads/DIO-TOOLS.user.js).

### TROUBLESHOOTING

If DIO-Tools does not work properly, please check the following points

#### INSTALLATION & ACTIVATION

Please check if the userscript addon is properly installed and enabled. There should be a button for the addon (![alt text][addon-tampermonkey] ![alt text][addon-greasemonkey] ![alt text][addon-violentmonkey] ![alt text][addon-noideawhat]) in your browsers toolbar.

If this is the case, look in the user script overview if DIO-Tools is installed and enabled.

#### UPDATES

Do you use the latest version? Otherwise, you should update. Sometimes it happens that the script does not work properly after Grepolis changes. By default the addons are checking every 24 hours for updates. This includes userscripts as well. As long as nothing else has been set, it should update automatically. Of course you can also update manually. Advanced users can change the update interval.

If the automatic update does not work, you should manually click on the update/install link on this page. Because download links in the [wiki](https://wiki.de.grepolis.com/wiki/Community-Projekte) might be outdated.

#### BLOCKING SCRIPTS

Maybe another script is blocking DIO-Tools? It is possible that other faulty/outdated scripts prevent the execution of following scripts. To check this you should disable the other userscripts temporarily and refresh the browser window then. You could also change the excecution order of the scripts to check it.

#### BUGS

If something does not work in Grepolis, you should first disable the userscript addon temporarily to make sure that it is not caused by any script. Please do not post bugs in the grepolis forum without checking it with disabled scripts, because it takes time to reproduce bugs. Please do not waste the time of Grepolis staff! It often happens that errors are caused by scripts. Usually caused by Grepolis changes. Because our userscripts are just adaptations of Grepolis. If something changes in the Grepolis code, it may cause following errors. Please consider that it is no one's fault. Grepolis developers and script authors are not to blame for it!

When you finally know that the bug is caused by a script, please identify the exact script! The way to find out is by separately testing the scripts. Please read the **Blocking Scripts** paragraph.

If you are sure that the bug is caused by DIO-Tools, please write a detailed and exact description of the bug (use the feature terms of the script!). This includes the specification of the browser and the current DIO-Tools version! When does the error occur? Don't be sloppy, otherwise you waste my time.

If you know how to use the browser console, you can identify the error more precisely. Create a screen of it.

[addon-greasemonkey]: http://diotools.de/images/icons/addon_gm.png "Greasemonkey"
[addon-tampermonkey]: http://diotools.de/images/icons/addon_tm_black.png "Tampermonkey"
[addon-violentmonkey]: http://diotools.de/images/icons/addon_vm.png "Violentmonkey"
[addon-noideawhat]: http://diotools.de/images/icons/addon_nk.png "No idea what Addon that is"