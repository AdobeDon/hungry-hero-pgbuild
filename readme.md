Hungry Hero
===========

Hungry Hero is a sample game for FastCanvas.

See https://github.com/phonegap/phonegap-fast-canvas-plugin

After cloning HungryHero, import 'Existing Android Code Into Workspace' in Eclipse, selecting `HungryHero\Android`.

HungryHero is a port of the ActionScript game http://www.hungryherogame.com/

Issues
------
1. Update Code - iOS stays pending forever, requires refresh to show built status
2. IE9 - app settings screen refreshes constantly
3. Update cordova version in XML file, must delete and re-create app
4. Create new app from git repo, on refresh only two apps shown
5. Create new app from git repo, before first build, description rendered in wrong place
6. After adding app, no ready to build button.  Must manually refresh
7. When are we going to get the full list of plugins on build?
8. Windows - none of the text is centered properly in the buttons
9. After making a new app, can't update code until you build.
10. After making a new app, can't set iOS key until after first failed build.
11. When selecting iOS key, all platforms rebuild, not just iOS.
12. Apps in "Ready to Build" state can have hydration or debug changed, but built apps have to drill down to settings.
13. Update code causes a rebuild even when the remote git repo hasn't changed
14. Builds take forever.
15. Submit an app; on submission no ready to build button - must refresh - chrome windows
16. If plugin js file is in there, build won't work.
17. No way to get platform specific plugin.xml data in AndroidManifest.xml
18. No way to get platform specific config.xml data in AndroidManifest.xml
19. After I delete an app, win chrome - goes back to apps page showing app; refresh and app is gone
20. Added FastCanvas 1.0.1 - shows up at bottom of list with 1.0.0 at top.  Bad sort order in AllSupportedPlugins
21. Rebuilt app that previously used 1.0.0 now that 1.0.1 is active; 1.0.1 didn't get appcount incremented
22. Rebuilt app that previously used 1.0.0 now that 1.0.1 is active; 1.0.1 didn't get used, 1.0.0 still used; requires create new app to get 1.0.1
23. No "Public Page" button on app details screen, why not?  Only on app list screen.
