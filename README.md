# Soundwave Interactive Releases & Changelog

## Download Link

[Latest](https://github.com/DeekyJay/SoundwaveInteractive-releases/releases/latest)

## Changelog

## 0.9.19 (2017/07/01)
- Oauth Tweaks.

## 0.9.17 (2017/05/03)
- Forced Refresh of Authentication on First Login.

## 0.9.16 (2017/05/02)
- Tweaked Firewall Blocking Handler.

## 0.9.15 (2017/05/02)
- Deprecated all cases of Interactive 1.0.
- Functionality added to convert Interactive 1.0 board to 2.0 board.
- Added Extra Error Handling.
- Removed background grid behind buttons, as they are much smaller with Interactive 2.0.
- Fixed bug where the user is unable to unassign a sound from a button.
- Unassigned buttons are now hidden from below the stream.
- Modified the error screen so the user knows the difference between failing to connect due to an error or firewall, or if they are restricted.
- Brought back task bar option.
- Added Toastr and log for people who press the button.

## 0.9.12 (2017/02/20)
 - Moved some robot logic to the main process for better performance.
 - Resolved the issue of needing to relogin after 6 hours.
 - Resolved the issue with users being unable to login via Microsoft, Twitter, & Discord'.
 - Resolved the issue with cooldowns not being properly set at the start of the application'.
 - Added a right click context menu to the board sounds to allow the user to modify & unassign them.

## 0.9.10 (2017/01/04)
 - Hid 'Minimize to System Tray' until Electron specific bug is resolved.
 - Resolved Issue with selected Output devices not showing as selected. (Electron specific)
 - Enhance Refresh Tokens to update into local storage.

## 0.9.9 (2016/12/11)
 - Tweaked wording in tutorial.
 - Allow duplicate sounds to be added to the sound library.
 - Tweaked OAuth Login Window to be more user friendly.
 - Update Electron to 1.4.12.
 - Fixed issue with default audio output device not loading on start of the application.
 
## 0.9.8 (2016/12/01)
- Fixed issue with audio playback.
- Fixed issue with global volume.

## 0.9.7 (2016/12/01)
- Added ability to kill all playing sounds.
- Added reconnect to ping timeout.
- Forced a parse on cooldown so it's always a number.
- Resized Icons.

## 0.9.6 (2016/11/28)
 - Added option to minimize to tray.
 - Expanded the drag zone for the window.
 - Linux/Mac builds.
 - Show active sounds in selected profile.
 - Better error handling.
 
## 0.9.5 (2016/11/22)

 - Added Tutorial for new users.
 - Handle better storage save.
 - Handle better storage clearing.

## 0.9.4 (2016/11/21)

 - Handle Auto Update error.

## 0.9.3 (2016/11/20)

 - Auto-Login loading transitions are a lot smoother now.
 - Holding time for sounds & profiles have been tweaked again for a smoother experience.
 - Modified wording on certain settings for clarity.
 - 20 minute interval auto-update checks added.
 - Force / Give direction to the user that they must have at least one profile.
 - Changed the maximize button to look like an actual maximize button.
 - Expanded the zone the user can select to move the window around.
 - Fixed storage saving immediately after loading.
 
## 0.9.2 (2016/11/18)

 - Fixed global static cooldown parsing issue.
 - Tweaked delay on dragging sounds/profiles.

## 0.9.1 (2016/11/18)

 - Fixed `id of null` error.
 - Fixed issue with analytics being disabled by default.

## 0.9.0 (2016/11/17)

 - Initial Closed-Beta Release.
