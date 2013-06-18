Hungry Hero
===========

Hungry Hero is a sample game for FastCanvas.

See https://github.com/phonegap/phonegap-fast-canvas-plugin

After cloning HungryHero, import 'Existing Android Code Into Workspace' in Eclipse, selecting `HungryHero\Android`.

HungryHero is a port of the ActionScript game http://www.hungryherogame.com/

Bugs
----
1. Update Code - iOS stays pending forever, requires refresh to show built status
2. IE9 - app settings screen refreshes constantly
3. Update cordova version in XML file, must delete and re-create app
4. Create new app from git repo, on refresh only two apps shown
5. Create new app from git repo, before first build description rendered in wrong place
6. After adding app, no ready to build button.  Must manually refresh
7. When are we going to get the full list of plugins on build?
8. Windows - none of the text is centered properly in the buttons
9. After making a new app, can't update code until you build.
10. After making a new app, can't set iOS key until after first failed build.
11. When selecting iOS key, all platforms rebuild, not just iOS.
12. Apps in "Ready to Build" state can have hydration or debug changed, but built apps have to drill down to settings.
13. Update code causes a rebuild even when the remote git repo hasn't changed
14. Builds take forever.
