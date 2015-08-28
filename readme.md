# ChangeWindows

This repository contains all build files used by ChangeWindows on http://changewindows.org.

## Contribute

### Missed features in Windows
It could happen that we miss out on a feature that's new in any build of Windows. If that's the case, please tell us! You can do so by creating a pull request or opening a new ticket. The following requirements apply:

- Start your pull request or ticket with [BUILD], where BUILD is replace by the build number of the feature your submit
 - In case the feature is confirmed to appear but the build is not known, use [NEXT]
 - E.g. [9924] New XAML-based start menu
- You need to include proof of this feature to be included in that Windows build in the description of your pull request or ticket (not the code itself), reliable source required
- Do not submit any subjective information, we want to stay objective on this as much as possible (which is a 100%), no rumors
- With pull requests, as soon as the information is pulled to our main repository, you lose the rights on the pull request
- If there is a mistake in a feature that already has been listened, you can open a new ticket or pull request to remove it from its respective build, again with the [BUILD]-syntax, and a short description of the issue
 - E.g. [9841] The Notification center wasn't added
 
You can't create a file for a new build. We'll do that ourselves and publish it as soon as possible to the repository for you guys to make pull requests to it. Feel free to add a changelog for 9834, through.

### Features for ChangeWindows
In case you have some nice ideas for the website itself, we would like to hear it to! Again, you can open a ticket and describe the new feature as well as possible. Of course, the actual code won't be published here.

## FAQ

**Will you publish the whole website here one day?**

That's not currently in the planning. We're thinking about doing so, through. Perhaps one day. We're considering releasing the next version of our website as a GitHub Pages project, and thus, open sourcing it by default.

**Can we add images?**

Yes, but there are a couple of requirements, and only 1 can be added for each build:
- The image resolution must be Full HD 1080p
- Scaling must be 100%
- It must have the default wallpaper of that build as background
- The screenshot must show off some of the larger changes in this build (for 10158, for example, that was the Edge branding, new browser and new toggles in Action Center)

**I found some spelling mistakes in the build information, can I create pull requests/tickets for those too?**

Of course! Go wild! You can create a new ticket or pull request for anything related to the website.

**The information I added is merged with the master branch, yet my changes do not appear on the websites, what's going on?**

After you submit your data, and we merge it into our main branch, it doesn't publish the data automaticaly to our website, we'll validate it once again before the information is synced to the server.

**What license is this information released with?**

To describe it shortly: the information in this repository is copyrighted by us, if you add new information to this through pull requests, you take a distance of all the information and code given. You can not use it to build a duplication of our website, or any other purpose. We make one exceptation: websites that report on these kind of things are free to use it, as long as they add a link to our website to such article.