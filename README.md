# GAFK

Get Away From Keyboard

GAFK is a macOS app that helps to remind you to get up and move around.
Unlike normal stand up notifications, GAFK allows you to write a custom message that shows up as a notification. Write anything that motivates you, reminds you to do something during the day, or whatever helps you to move.
It includes time intervals from 20 min - 2 hours, an optional reminder sound, and a preview to see what the notification looks like with your message.
Further updates coming soon that will include a connection to HealthKit to display step count and step goals.

## Download

 [Download the latest version](../../releases/latest)

Grab the `.dmg` from the latest release, open it, and drag **GAFK** into your Applications folder.

## What's new in 1.1

**Reminder sound.** Reminders can now play a sound. It uses whatever alert sound you've picked in *System Settings › Sound*, at your alert volume, so it sounds like the rest of your Mac instead of adding a new noise. Toggle it under **SOUND** in Settings — it's on by default, and the *Show* button previews the sound along with the notification.

**The on/off switch pauses instead of starting over.** Switching GAFK off and back on used to throw away the countdown and restart the whole interval. It now keeps the time that was left — switch off with 19 minutes to go, switch back on, and you still have 19 minutes. While it's off the header reads `Paused · 19 min left` so you can see the time is being held.

**Sleeping your Mac no longer sets off a reminder when you wake it.** The countdown stops when your Mac sleeps and picks up where it left off, so you won't get a "get up and move around" notification the moment you open the lid.

**New time intervals.** The choices are now **20 min, 30 min, 45 min, 1 hour, 1.5 hours and 2 hours**. 45 minutes and 1.5 hours are new. The 10, 40 and 50 minute options are gone, along with 3 and 4 hours — for an app about getting up and moving, a 4 hour reminder only fires twice in a workday.

> If you were using an interval that's no longer there, GAFK moves you to the closest one automatically. Worth a quick look at Settings after updating to make sure it picked the one you wanted.

**Fixed:** pressing *Show* or *Get Up Now* used to make the countdown display jump to a new time while the real reminder still arrived at the original one. Those buttons now just show the notification and leave your countdown alone.

## Installing

1. Open the downloaded `GAFK-1.1.dmg`.
2. Drag the **GAFK** icon onto the **Applications** icon.
3. Launch GAFK from your Applications folder.

Already have GAFK? Quit it first, then drag the new copy over the old one when Finder asks.

The app is signed and notarized by Apple, so it opens without any security warnings.

## Requirements

- macOS 13.5 or later

---

*Thanks for checking it out! Feel free to hit me up with any ideas and feedback.*
