TL;DR: Dynamic theming in this app is broken, I honestly don't know how to fix it, and I am lacking the motivation I think would be needed for me to fix it, so it may be better to move to a different Signal app.

# The current state of Signal-You
If you compare the screenshots in [the repository's original README](https://github.com/nekorubu/Signal-You/blob/main/README-orig.md) to what the app looks like now, you can probably tell that there's some glaring issues with the hallmark feature of this app (as seen in [issue 11](https://github.com/nekorubu/Signal-You/issues/11)). Issues like this have actually been going on for quite a while. It originally started with the main settings menu, then other settings pages, and now to the bottom bar on the main conversations list.

Why haven't they been fixed? It's mainly because I haven't been able to figure out how to fix them, nor have I been able to find the focus or time to try to figure out how to fix the issue.

So, with that being said, I'm deciding to go ahead and retire (or sunset, possibly even) the fork.

# Why?
At this point, trying to fix the current issues with the dynamic theming is becoming too overwhelming for me, as I'm not really sure where to even begin in trying to fix it. As of now, I think that I would have to try and learn / figure out how the Signal app itself is built, and given the very little Android experience that I have, that will take a lot of time and focus to do. Sure, I'm sure that there are many people out there who would be willing to help in fixing the issues (as evident to me by the sheer number of stars on this repository), but unfortunately, I'm not very motivated to keep trying to fix them at this point...

I'd rather see someone with more motivation and (hopefully) more knowledge of how to develop Android apps take on this idea, than for the app to continue to not have the main feature fixed.

# What will happen to the fork, then?
As of now, I'll still keep the app up to date, at least for a while, in case people still want whatever dynamic theming is still available, or just aren't ready to move to a different fork yet. However, as of now, I don't really plan on trying to fix the theming issues. Thankfully, the app should still work despite the fragmented dynamic theming.

# What should I do then?
As of now, I suggest that if you all want some consistency with the app's theme, then moving to a different fork might be a good idea.

## If you want a more maintained fork
Then you can always go back to the upstream fork: [Signal-JW](https://github.com/johanw666/Signal-Android). Make sure to make a backup, uninstall the app, then install johanw's version and import the backup. This should be a smooth process, as not much should have changed from his version, so you should be able to import a backup to the matching version.

## If you want Material You
Then I'd look at [Molly](https://github.com/mollyim/mollyim-android). They have a much more complete dynamic theme than I was able to get to as of the latest version, and you also get some nice security features with it as well, but it doesn't support all of the features of Signal-JW, such as importing from a WhatsApp database or treating view-once media as normal media. They aren't always on the absolute latest version of Signal available, either, as they say in the fork's README:

> We update Molly every two weeks to include the latest Signal features and fixes. The exceptions are security patches, which are applied as soon as they are available.

You can, however, use the app as a linked device to this fork, Signal-JW, or even the original version until they get to a version that's available for you to update to. Or you can just keep using it that way if you'd like. I will say, though, that linking Molly to the main Signal app on the same device has been a bit tedious in my experience, but hopefully, that's because of how I went about doing it.

# What if I want to keep maintaining the fork?
If you'd like to do that, while I'm not comfortable with handing the repository over to someone else, since the code is open source, anyone's free to make a fork of the app and have their hand at maintaining it and fixing the theming issues if they'd like.

With all that being said, thank you all for using this fork all these years, as well as for the stars that this project has gotten (seriously how did this get 120 stars what the heck), as well as those who contributed to this fork through issues and code contributions.

<sup>I'm actually surprised that this fork has gone on as long as it has...</sup>