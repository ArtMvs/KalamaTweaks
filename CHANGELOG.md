Update 15.0

- high-quality full refactoring of the script part (many thanks LolD for the help
- added "protection" for those who do not read the "installation and update" item
- added launcher refresh rate selection during installation (Vol+ 144Hz, Vol-stock)
- significant improvements in refresh rate stability, scrolling, transitions, animation processing, reduction of phantom lags
- increase in sot during "normal" use on a dark theme by an average of +1h~ (without games and other crashes)
- improvement of the "clear voice" function
- heating reduction
- vrr improvement

Update 14.0

- disabled unnecessary coresight debug
- disabled high volume warning in headphones
- unlocked 160MHz channel width for wifi (thanks Skavellion xda)
- minor edits

Update 13.0

- Improved overall smoothness and responsiveness
- increased refreshrate stability
- improved smoothness of camera viewfinder
- improved memc
- enabled paralel dexopt
- enabled clear voice (settings-sound)

Reminder: you can't update over, delete the old version and install a new one.

Update 12.0

- switch to a script basis
- reduced heating
- improved refreshrate part

Changed the concept of getting 144Hz in the interface, coloros reacts negatively to the full transition to 144Hz (due to the fact that oppo simply does not have devices with 144Hz and the system is not optimized for this, gnilmi gives us this as a feature, and quite clumsily), some elements should work as in stock, at 120Hz, for the sake of stability and adequate operation.

The lock screen and unlock animation is a separate story, oppo stupidly locked it at 120Hz and at the same time, each time the screen is turned on, for some reason, constantly setting this frequency, and because of this you see a lag and ragged animation. If you unlock from a black screen with a fingerprint, the animation will be smooth precisely because what I described earlier does not happen.

Now devices with 144Hz screens will have separate TweaksAddon "module" for get 144hz in launcher.

The latest update .401 turned out great, a huge difference in UX after .320, a little more and it can be called a great experience. Updated gpu drivers, many libs and frameworks, fixed the operation of the refreshrate at 45% brightness.

The module has switched to a script view, now you do not need to wait for the module to update for the new version of the system

Delete the old version and reboot before installing the new one, the module is updated in the same way, you cannot update on top. When installing, the module is compiled with your current files.

Update 11.0

- module rewritten for cos15

What is in the module at the moment:

- 144Hz at high refresh rate and in all applications
- touch 320Hz in the system, 420Hz in games, 500 in games in gt mode (at 144Hz)
- high refreshrate when using the camera in TikTok, Instagram, Whatsapp, vk/sova, telegram/telegraph/nekogram
- improved overall refreshrate behavior
- wifi improvements
- increased aod smoothness
- optimizations of system services in the background are enabled
- display of kernel git date and cpu information is enabled
- sharpness is enabled
- ai eye protection is enabled
- paper texture effect in eye protection is enabled
- tenderness vibration effect is enabled
- memc 120Hz is enabled for mx player and vlc

camera:
- cameraX extensions enabled
- audio modes for video enabled
- 144Hz in the camera app at standard resolution

Due to the changes in coloros 15 (and the spokes in the wheels from oppo), well and in the a15 itself, the module had to be redone, many previous changes were dropped to get a "clean base", also oppo encrypted the camera config so there will be no other camera improvements in the module.
From the first beta of cos15 and on the current stable 320, a bug from the latest builds of coloros 14 was returned (which was fixed in the latest builds) which was observed on all 144Hz devices by rotten, when the brightness is set to 45%-50% (the hertz breaks, therefore, the auto-brightness) and lag freezes, this bug is currently present in all Chinese cos15 for neo 5, 5se, gt5, gt5 pro, because of this, the display operation is generally disrupted (even if you do not set the brightness in this range). Surprisingly, it was fixed in the same .320 on the global gt3. Nothing was fixed from the old problems, except for the constant CPU load in the region of 45%-60% on gt5, well, and they added an old-new bug that was described earlier and errors in the kernel log (next time take OnePlus).
Anniversary update of the module.





#

Archived part:

Update 10.0

-adjustment for 1120
-kernel tuning almost all the main aspects from the file system to tcp
-reduced heating and overall load
-reduced load on little cores
-updated Hz config from gt5 pro
-disabled view override (they started to disable it on 14.1 with the latest snapshots, before that only mtk)
-disabled "signals" for rewriting Hz from applications
-disabled most modem logs
-completely disabled power pasr
-optimizations for zygote and watchdog
-disabled blur on icons
-vrr improvements
-feature for improved synchronization of the GPU with the display
-camera improvements
-minor edits and other improvements

Also updated undervolt config in KalamaExtraPackV2

Return to stock one pulse dimming for a while, if in cos 15 there will be an implementation for 144Hz screens.
Also removed conflicting lines with pui theme

Clear cache and acceleration in the phone manager. Clear data and camera cache.

Update 9.7

-adjustment for 1110
-increase frame buffers for sf
-improvements for appswitchboost
-minor edits

Update 9.6

-new refreshrate configuration as in coloros 14.1, the basis is taken from gt5 pro. Adequate operation of the hertz allows you not to even turn off slowdown and view override.

Update 9.5

-high refresh rate in the system camera at standard screen resolution
-high refresh rate when using the camera in TikTok, Instagram, Whatsapp, vk/sova, telegram/telegraph/nekogram
-high refresh rate in screenshots
-reduced heating

Clear cache and dynamic acceleration/trinity engine, interval reboot, reassign refresh rate for applications (even if it is set to 120 by default, this is not the case, this is a cos bug, reassign)

Update 9.1

-adjustment to 1102
-finished

Update 9.0

-disabled tombstoned
-,,lightened,, animations (the animations themselves are not changed)
-improvements for dexopt and fstrimm
-improved interaction with the display backlight (brightness changes smoother, reacts faster)
-extended memory allocation for graphics
-improvements for GPS and GNSS
-perf libe hints enabled during long rendering cycle
-modem improvements
-wifi improvements
-vrr improvements and disabled ambient (they finally started to disable it, ambient is the dynamic behavior of the hertz from the illumination)
-optimization of pre anim, scroll change, frame insert as on oppo and OnePlus
-pixelworks imv (adaptive frame booster for supported games)
-boot acceleration
-applications open faster in .1102
-heat reduction
-reduced power consumption
-general increase in smoothness and responsiveness

New features:

-ai eye protection and paper texture in .1102 (screen-eye protection and sleep)

A lot has been done and due to the fact that during all the time of "development", a lot has changed, returned, canceled, added. Previous changelogs will go to the archive for chronology and a list of what I have done so far and in general what the module gives will be presented.

Clear cache and dynamic acceleration/trinity engine, interval reboot, leave overnight on charge. Reassign the hertz of applications.

Update 8.3

-removing the hertz lock when using the camera in telegram, telegraph, whatsapp
-minor edits

Update 8.2

Adaptation for update .800

-reducing the load from animations and ui effects
-improvements for sensors
-disabling system statistics
-disabling the qualcomm logging service
-enabling the aptx adaptive 2.2 codec

Kernel tweaks

-disabling iostats
-tweaks for the i/o, ufs scheduler

Make a cleanup and dynamic acceleration in the phone manager.

Update 8.1

-enabled ,,fast,, vsync
-increased camera smoothness
-increased smoothness and responsiveness
-reduced heating in normal use (surfing)

Update 8.0

Adapted to the .703 update

-tweaks for greater smoothness and speed
-tweaks for dalvik
-squeezed tombstone
-tweaks vsync
-tweaks sf
-tracking and preventing memory leaks at the system boot stage
-tweaks for the file system
-disabling transition tracing in sf
-disabling redundant thermal, perf tracing in onetrace
-100% jpeg quality in the camera
-reduced background task snapshots
-refreshrate and vrr edits

New features

-ai eye protect in the game assistant (only in .703)

Make a cleanup and dynamic acceleration in the phone manager and clearing data and camera cache

The new .703 update brought updated systemui and launcher apk, a new android 14 build and again updated gpu drivers (it's very rare that they are updated within a minor), fixed adfr fakeframe, finally enabled cvt manager, but almost all configs and components remained the same as on 420, tons of errors in the logs and some errors in the kernel were not fixed, even more errors appeared in the logs. If someone wants to try switching to a14, I think it can be done with the next minor update..

Update 7.2

-new game manager config

-wifi improvement
-zram writeback enabled
-new frame insert, scroll change, pre-anim configuration
-vrr edits
-refreshrate config edits
-disabling some audiologs

Update 7.1

The module has been rewritten from scratch

- finally fixed the behavior of the hertz (it only remains for realme to finally fix adfr fakeframe)
- fix backlight distribution
- fix brightness slider
- improvements for dalvik
- surfaceflinger durations fixes
- network fixes
- reworked vrr
- additional disabling of telemetry
- improvements for lmk, closing processes with memory leaks
- accelerated opening of applications
- enabled preliminary rendering of frames
- touch improvements

Removed the feature of increased brightness until realme adds configs for the display to enable this feature

Update 7.0

-significant improvement in smoothness and reactivity
-improvements for sf
-improvements for animations and inclusion of new ones
-reworked surfaceflinger durations
-improvements memc
-reduced the impact of background dexopt on performance
-additional disabling of dynamic behavior of hertz, in particular from light
-completely reworked network part
-updated osense memory config
-vrr fixes

-returned improvements for sensors
-returned improved fstrimm
-rejection of disabling view override, in favor of its fine-tuning.
- partial updates returned
- smart touch left in stock (it was added in 310)
- jemalloc returned
- boot animation returned
- kernel settings postponed for some time

New features

- game accelerator (settings-additional) in 410
- increased brightness (settings-screen and brightness) in 410 (there will be a fix)
- game launch after activating gt mode (settings-battery-gt mode) in 410
- display effects in eye protection
- new implementation of dc dimming from realme
- quick launch of the camera (camera-settings)

You don't need to do a redex, as soon as you update to 410 it will do itself, put it on charge to 100% and wait for the device status to be charged, then reboot.

The module has been updated to 14.0.0.410. The jokers finally updated the database, finally gave new gpu drivers, surprisingly, but updated the kernel (usually vendors update only after a major), fixed a ton of errors in the kernel log out of two, however, everything said above was done in oneplus 11 and find x6 in early February with the release of cos .411 for them, which I have been yelling at realme bbs since March a couple of times a week, although I have been yelling there since the release of the first beta of coloros 14.
The next update should definitely fix almost all the moments, they should also give a new curtain of quick settings, cos 14.0.1 will probably be given only in August (when all devices around ours will already receive it))

Update 6.0

The module has been completely redesigned, a kind of refresh, some changes from previous versions have been canceled.

-smart touch enabled
-use of the new touch panel library enabled
-all system animations have been simplified (without changing the animations themselves, they just "eat" less resources)
-speeding up interface rendering, general reactivity
-disabling dynamic fps (part of the aggressive power saving cos that gives 5 minutes of battery life, and in return lags and freezes and slowdown of everything and everyone)
-extensions for frameshed enabled
-improvements for surfaceflinger
-disabled horae (a cos module that regulates/cuts performance, also part of the aggressive power saving that gives an unstable experience of using the device)
-updated RAM config
-improvements in vrr config (also disabling dynamic behavior from the illumination level)
-disabled partial updates (so that the ui does not crash when scrolling)
-the pwm switch has been replaced with a forced pwm.
-network improvements
-remote preload enabled
-cos telemetry disabled

Kernel tweaks 

-entropy settings
-disabling kfence to improve RAM performance

New features

-touch adaptation (settings-additional settings)

Due to changes in the latest android, cache cleaning scripts do not work as they should. It is enough to clear the settings cache, system launcher and the system graphical interface. Also do a couple of reboots.

Update 5.5

-Improved hertz processing
-Fix reset selective hertz after reboot
-Fix touch frequency reset after screen lock
-Enable cvt manager
-Enable fingerprint sensor feature (unlock by touch)
-Enable skip first frame to speed up display
-Enable improved fstrimm
-VRR edits

Removed background optimizer from qcom

After installation, clear cache as in v3, and do redex (updated commands)

Update 5.1

-Accelerated rendering and minimized interface delays
-improved scrolling and minimized prolags
-improved dalvik, applications start faster and work more stably
-enabled background and RAM usage optimizer from qualcomm (does not conflict with the system one)
-VRR edits

New features

- dynamic island enabled (settings-laboratory. For some reason, normal display only at high resolution. 

If you updated from v5, after installation, clear the cache of the system graphical interface, system launcher, settings, wireless network settings.
Then a couple of reboots (not immediately after the lockscreen appears, run for 5 minutes and reboot)

Update 5.0

- improved performance and smoothness of the interface
- improved sound and microphone for calls
- new and optimized vrr
- improvements for surfaceflinger
- improvements for aon, sensors and detectors
- enabled regionsampling for smooth animations
- disabled forced use of software rendering in favor of hardware
- disabled security elements affecting performance. (Like spectre, meltdown)
-accelerated game launch
-improved network, connectivity (network, internet, wifi)
-improvements for gps
-improvements for vibration

New features

-enabled natural color mode 2.0 (settings-screen)
-enabled clear voice (settings-sound)
-enabled soundproof call (dialer-settings)
-enabled eye protection and sleep 2.0
-bright mode in camera
-hdr 2.0 in games
-improved high resolution mode in games
-edr mode in games (like improved hdr, available in global game assistant)
-enabled hdr vision
-enabled wcg 1.0
-enabled avt and frame stablize in vrr
-enabled display of extended version and kernel date
-enabled additional swipe gestures
-enabled new, updated, perfect dc dimming which does not have the disadvantages of the previous one (settings-screen-eye protection and sleep)
-also added pwm dimming switch (settings-developer mode)
-now the touch gives 450Hz in the system and 600 in games (there is one but, the system energy saver or something else, resets to the stock 240Hz when you lock the screen, but if you switch the hertz or go into the game, the set values ​​​​return). I was looking for a fix for a long time, so the release of the update was delayed. By the way, on the global gt3, for which I saw the TaroTweaks module, there is no such problem.

The module has been redesigned and adjusted to the last version of the firmware. I hope realme will continue to give us root changes for our device, there are still significant shortcomings inside, but it seems they have undertaken to fix it. I also hope they will adjust our ROM to the last coloros ~400 build.

Look at the actions after installation.

Update 4.5

- fixed ProXDR and Sharpness
- optimized vrr
- tweaks for interface performance
- fundamentally improved hertz operation, view override disabled (because of it the hertz slows down, 144 feels like 90, this also fixes freezes of interface elements, animations, etc., in short +- fixes the crooked implementation of the hertz of color os)

But there is one nuance, from disabling view override, which I have been digging since the beginning of December, if you do not set 3D games to 120Hz (some work fine, because these studios brought oppo, and the configs for 144Hz are in encrypted files), then there will be 48 fps and hard freezes, all this is due to the fact that oppo does not have 144Hz screens and from this in color os "Underdeveloped" display config, it only knows about 60 and 120Hz, and realme gives us 90 and 144 as a feature with crutches. The procedure is one-time, but it flies off after reboot (setting 120Hz for adequate operation). I think this will not bother you much, because you do not reboot the device 100 times a day like me.
* As it turned out, this is partly a problem of the crooked rui 5.0.

Clearing the cache as for 3.0

Update 4.0

- Improved overall performance, reactivity, reduced interface delays.
-display improvements
-surfaceflinger improvements
-framebuffer improvements
-dolby improvements
-network, wifi improvements
-scrolling improvements
-disabling internal logging and system tracing
-using skiaglthreaded instead of vulkan for the interface
-touch improvements
-vrr optimization
-animation improvements
-application startup acceleration
-sensor improvements

New features

-Sleep mode (eye protection and sleep)
-adaptive frame boost (same place as super resolution, 144 fps in any game that supports 60 fps)
-vibration improvements, new vibration effects included.
-32-bit application performance improvements included

Rejection of cgroups, kernel tweaks, hardware acceleration.

After installation, do everything as for 3.0 except cleaning the camera.

I recommend updating to stable a14

Update 3.0

-Significant improvement in overall performance, speed, smoothness and power saving
-kernel tweaks
-gpu tweaks
-cgroups and core distribution
-surfaceflinger improvements
-reduced overall latency and jitter
-display improvements
-switching ui to hardware acceleration
-cleaning system junk every reboot
-disabled tombstone
-additional disabling of all sorts of statistics (oh, this cos)
-improved audio, dolby, dolby surround enabled.
-improved wifi
-improved connection
-enabled priority for using lte_ca
- improved graphics, enabled frame_rescue (less frame drops)
- improved GPS
- faster fingerprint scanner

New features and improvements

- enabled adaptive detail enhancement (settings-screen resolution)
- enabled Holo Audio (sound settings)upd (added in 14.0.200 for gt5)
- spatial audio for all outputs
- enabled bluetooth dual mode transport
- enabled lossless aptx adaptive le codec
- enabled bluetooth volume sync

- enabled adfr, frtc, touch frame changing, cvt for display, disabled touch idle, hw, histogramm, color temp ir, color temp cct, local hdr, sharpness and other display, color and backlight improvements.
- Dolby Vision refinement
- Natural shades mode refinement

- Additional normal animations of the system, scrolling and flings are enabled
- AppSwitchBoost is enabled
- Features to speed up application launches
- Flagship gaming assistant and its internal components upd are enabled (was added in 14.0.120)
- Touch improvement (smart touch)
- Enable SmoMo for games and camera
- Additional super alive features are enabled

Camera

- Switch to OpenGL 3 is enabled
- Thermal improvements for video are enabled
- Xpan mode is enabled
- Use of updated quick jpeg is enabled
- Super stabilization for wide-angle is enabled
- Quickcameraswitch and quickmodeswitch features are enabled
- Smoothness of camera viewfinder is improved

- Maybe I forgot something, a lot of work. Be sure to check the actions after installation.

Update 2.0

- added new props to improve the smoothness and reactivity of ui, scrolling.
- display tweaks
- enabled section 84 thermal
- enabled the use of 8 threads for dex
- additional disabling of logs and statistics
Features:
- enabled support for Dolby Vision in the display
- enabled support for natural shades mode (settings-screen)
- enabled haptics styles (settings-tactile response)
- enabled audio modes for video (camera-settings)
- improved smoothness of viewfinder
- accelerated switching between front and rear camera modules
- enabled track focus in 60fps modes
- enabled normal animations of the upd system (were added in 14.0.91)
- accelerated application launch
- enabled holographic effect for weather.
Read the post-installation steps regarding the updated module.

Update 1.1

- fixed hertz modes, auto-120, standard 60, high 144.
- enabled wifi 7 support (if you have such a router, test it, delete the network and reconnect)
- improved connection, amr wideband enabled
- improvements for skia, increased rendering performance, reduced latency.

Main
