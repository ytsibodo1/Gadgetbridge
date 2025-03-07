### Changelog

### 0.60.0
* Initial support for FitPro bands
* Mi Band 6: really fix weather on new firmware
* Casio GBX-100: Fix connection
* Fossil Hybrid HR: Lower battery level warning threshold to 10%
* Add ringtine preference setting for find your phone feature
* Fix a bug where GB_LOGFILES_DIR_IS_UNDEFINED is used as a logfile directory
* Remove per-device preferences upon device removal (backup your keys if you do that)
* Exclude not worn sleep times from sleep sessions
* Add Icelandic and Czech transliteration

### 0.59.3
* Mi Band 6: Properly support firmware 1.0.4.38
* Mi Band 6: Add Flashlight to menu items
* ZeTime: Fix corruption on long notifications

### 0.59.2
* Mi Band 6: Support firmware 1.0.4.38 (experimental, still missing features)
* InfiniTime: Fix null being displayed as notification title

### 0.59.1
* Fossil Hybrid HR: Add power saving feature and many new widgets for the official Gadgetbridge watchface (battery, calories, 2nd TZ, chance of rain)
* Fossil Hybrid HR: Support setting metric/imperial mode
* Amazfit T-Rex Pro: Try to fix some menu items
* Huami: Re-enable setting the timezone correctly with included DST (fixes world time)
* Bangle.js: Add functions for pushing bitmaps
* Bangle.js: Aadd configurable MTU
* Add Heart Rate measurement screen, accessible via heart icon in device action icons

### 0.59.0
* Initial support for SMA Q2 OSS firmware (Emeryth)
* Fix broken UM25 support
* Fossil Hybrid HR: Add watchface designer
* use '_' instead ':' in exported and imported file names to fix problems with some Android versions
* Fix applying theme as set by the system
* Try to improve behavior when quitting Gadgetbridge

### 0.58.2
* InfiniTime: Support notification for battery level
* Allow importing GPX tracks via Android Intent/Share system
* Add option for black background to dark theme
* BangleJS, WaspOS: Support for transliteration
* Add missing icons to settings items

### 0.58.1
* Pebble: Fix broken app manager (regression from 0.57.1)
* Bangle.js: Try to fix crash when attempting to load activity chart
* Amazfit T-Rex Pro: Add barometer to menu items
* Remove battery data when device is being removed
* Add transliteration to PineTime
* Debug: Allow adding fake testing devices manually
* Reduce margin of icons in device_item to keep one row for typical amount of icons

### 0.58.0
* Initial experimental support for Amazfit T-Rex Pro
* InfiniTime: Try to fix firmware upgrade by fiddling with optimization rules
* Huami: Fix lost samples bug with timezones that are have a 30 minute offset
* Fossil Hybrid HR: Block dangerous intents by default and move some settings to developer settings submenu
* Improved logging in bonding and tried to recover from weirdness
* Use a separate notification channel for low battery warnings

### 0.57.1
* Mi Band 6: Add Pomodoro to menu items
* Mi Band 6: Support flashing firmware, res and watchfaces
* Mi Band 6: Enable Unicode Emoji support
* Fossil Hybrid HR: Move commute actions to device specific settings
* Fossil Hybrid HR: Use Gadgetbridge App Manager (same as Pebble), allowing quick switching of watchfaces and caching apps for later re-(installation)
* Huami: Send changed weight, birthday and height data to watch immediately
* Use flexbox layout for icons in device cards, allowing line breaks for small phones

### 0.57.0
* Initial limited support for Mi Band 6
* Amazfit GTR2/GTS2: Fix for flashing watchfaces
* Amazfit GTR/GTS/GTR2/GTS2/Bip S: Allow flashing AGPS bundles
* Amazfit Neo: Add lift wrist setting
* Fossil Hybrid HR: Restructure settings menus for calibration, file management and physical buttons
* Fossil Hybrid HR: Hide old settings on newer firmwares
* Improved PineTime/InfiniTime firmware DFU metadata parsing and checks

### 0.56.2
* Amazfit GTR2: Improve firmware update support (still partly broken)
* Amazfit GTR2/GTS2: Prevent emoji transliterating (Seems to support emoji)
* Amazfit GTS2/GTR2: Fixes for setting menu items (Probably still partly broken)
* Amazfit GTS2/GTR2: Send wind speed and sunrise/sunset
* Fossil Hybrid HR: Send actual application icons for notification on the watch
* Fossil Hybrid HR: Support dismissing incoming calls with a quick SMS reply
* Huami: Remove unused calendar slots
* Huami: Send wind speed in Beaufort for some devices
* InfiniTime: Add support for battery info
* InfiniTime: Support title for notifications on firmware 0.15
* InfiniTime: Implement find device by simulating a phone call
* Adjust Steps Charts steps values offset to account for large phone screen sizes
* Make Activity Charts dates move as calendar months and to go to now if jumping past today
* Make Battery Info time span jump as calendar months and not as days

### 0.56.1
* Fossil Hybrid HR: Fix compatibility for oder firmware revisions
* Amazfit Neo: Implement firmware update
* Amazfit Neo: Support setting all menu items and fix menu cycling bug
* Amazfit Neo: Fix notifications
* Amazfit Neo: Support sound settings
* Allow OpenTracks and FitoTrack to send ongoing notifications
* Make transliteration a per-device setting

#### 0.56.0
* Initial support for UM25 voltage meters
* Pebble: Remove read/dismissed notifications on watch (can be disabled)
* Fossil Hybrid HR: Remove read/dismissed notifications on watch (can be disabled)
* Fossil Hybrid HR: Fixes for running firmware DN1.0.2.20 or newer (disable widget features, currently not supported)
* Fossil Hybrid HR: Fix up/back navigation and add titles to Fossil specific menus
* Huami: Fix displaying title for calendar events
* Use requestLegacyExternalStorage in manifest to fix file access problems in some Android 10 roms
* Add chart to each item in activity list
* Add scroll view to activity detail to handle landscape view
* Add header title to activity detail

#### 0.55.0
* InfiniTime: Fix music control for newer firmware releases
* InfiniTime: Support call control and notification
* Sony SWR12: Fix broken support since 0.53.0
* Wasp-OS: Fix crash on Android 7 and lower
* Add activity list dashboard summary calculations
* Add battery level logging and graph activity
* Use distinct icons for total step and distance values in widget
* Flip and scale GPX canvas
* Try to fix call notification on outgoing VoIP calls

#### 0.54.1
* Amazfit GTS2e: Really fix broken support
* Amazfit Bip S Lite: Fix broken support (probably)

#### 0.54.0
* Initial support for Amazfit X
* Fix missing menu items for GTS 2 Mini (some improvements also for other GTR2/GTS2 models) 
* Amazfit GTS2e: Fix broken support

#### 0.53.0
* Initial support for wasp-os on nRF52 devices
* Initial support for Zepp E
* Initial support for Amazfit GTS 2 Mini
* Initial support for Amazfit Neo
* Initial support for Amazfit GTR/GTS 2e
* Fossil Hybrid HR: Fix bug with unknown data
* Fossil Hybrid HR: allow app management on watch from GB
* Fossil Hybrid HR: enumerate apps on watch on every connect
* Fossil Hybrid HR: Do not configure buttons in unauthenticated mode
* Fossil Classic: Fix unknown wearing state
* Fossil Classic: Allow synchronizing activity data
* Amazfit Bip U: Fix sports activity summary
* Huami: Add Strength Training activity type
* Honor Imperial units settings in widget, Activity list and workouts
* Show all eligible devices in Widget Configuration Activity
* Also include step of not-worn samples in weekly step statistics

#### 0.52.0
* Amazfit Bip U Pro: Initial support
* Amazfit GTS2: fix pairing
* Amazfit GTS/GTR2: Fix incoming call display
* Fossil Hybrid HR: avoid unnecessary widget rendering
* A lot of Data(base) Management screen clarifications and improvements
* Fix a crash when when forecastConditionType length is 0 in weather notification data
* Change Do Not Disturb support to allow priority notifications
* Fix problems when pairing some devices which require a pin to be entered

#### 0.51.0
* Amazfit Bip U: Initial support
* Amazfit Verge Lite: Initial Support
* Amazfit T-Rex: Add missing menu items, remove non-existent
* Amazfit Bip S: Fix crash with notifications with only a title (GitNex does this)
* Casio GBX-100: Add step count data and more device settings
* Fossil Hybrid Q: Support firmware upgrade
* Bangle.js: Support for HRM and steps activity recording
* Huami: Add new option to properly distinguish connected advertising and 3rd party hr exposure
* Huami: Use blue icon instead of rainbow color icon for Signal (the rainbow icon was blue in early days)
* Complete overhaul of the daily stats widget
* Better error message for invalid authentication keys

#### 0.50.0
* Initial support for Casio GBX-100
* Mi/Amazfit Band 5: Support watchface installation
* Mi Band 5: Add missing NFC menu item
* Casio GB-5600B/GB-6900B: Add configurable disconnect notification
* Casio: Add support for synchronizing profile settings
* Fossil Hybrid HR: Keep widget values after widget reload
* Allow sorting and disabling charts/statistics tabs in per-device settings
* Improve Sports Activities dashboard and Filter
* Bug fixes for notification removal
* Allow to clear activity labels

#### 0.49.0
* Initial support for Amazfit Bip S Lite
* Initial support for Amazfit GTR/GTS 2
* Huami: allow sorting of shortcuts and menus (all except Mi Band 2)
* Amazfit Band 5: Allow enabling SpO2 menu
* Mi/Amazfit Band 5: Support shortcuts (right/left swipe)
* Amazfit GTS: Fix firmware flashing on Firmware >=0.1.1.16
* Amazfit GTR: Fix firmware flashing on Firmware >=1.3.7.16 or >=1.7.0.10
* Amazfit GTR/GTS: Add missing settings menu item in preferences
* Fossil Hybrid HR: Remove Android notifications when deleting them from the watch
* Fossil Hybrid HR: Enable rejecting calls on newer firmwares
* Fossil Hybrid HR: Support hands calibration
* Fossil Hybrid HR: Support factory reset
* InfiniTime: Improve notification support for firmware >=0.9
* Add version to About screen
* Show GPS track in Sport Activity detail screen
* Add Activity List Dashboard/Summary view to charts
* Add heart rate average to Activity and Sleep charts
* Add intensity to Sleep charts
* Recognize Wire messenger as a chat application
* Add confirmation dialog for find device button

#### 0.48.0
* Initial support for Sony SWR12
* Initial support for Lefun Smart Bands
* Initial support for Nut devices
* InfiniTime: Improved music support for latest firmware
* Fossil Hybrid HR: Fixes and better support for newer firmwares
* Fossil Hybrid HR: Debug activity for dumping and sending resources to the watch
* Huami: Improve style of sports activity lists
* Add sport activity list tab in charts
* Allow sharing of sports activity summaries as image (full scroll view)
* Weather: Fix wind speed and direction not being passed properly
* Fix find your phone feature on Android 10 (need companion device pairing)

#### 0.47.2
* Amazfit Bip S: Send sunrise and sunset on latest firmware if enabled
* Huami: Support new firmware update protocol (fixes firmware flashing with firmware 2.1.1.50/4.1.5.55 on Amazfit Bip S)
* Huami: Allow flashing latest GPS firmware
* InfiniTime: Add support for music control
* Pebble: Fix steps on home screen widget
* Bangle.js: Fix issue where call state reporting was corrupted
* Add charts to sport activity summary view
* Add missing icons for new sport activity types

#### 0.47.1
* Huami: Add new activity types found in recent Bip S firmware
* Huami: Many improvements to the activity summary view, including a global view for all devices, filtering per activity type and much more
* Huami: Prevent generating broken elevation data when they are not sent by the device
* Amazfit Bip S: Allow flashing more font files and GPS almanac (only cep worked before)
* Pinetime-JF: Recognize device if it announces itself as InfiniTime
* ZeTime: Fix weather forecast icons on older firmwares, try to send weather even if no firmware version was detected
* HPlus: Improve Unicode, notification lenth and  weather support
* Fix warnings and colors for AboutScreen

#### 0.47.0
* Initial experimental support for Pinetime-JF (not yet usable)
* HPlus: Recognize Lemfo SG2
* Huami: Support events forwarding via intents or direct triggering of certain actions (eg. stop music when fall asleep)
* Huami: Add Sports Activity Detail screen from decoded sports summary values
* Huami: Recogize and decode lot more activity (workout) types
* Amazfit Cor/Cor2: Allow workout syncing
* Add Sports Activity Summary filtering and statistics
* Many icons have been re-drawn as vectors, also several new device and sports activity icons added
* Many improvements to the Bluetooth discovery and scanning
* Fix crash when opening GPX files

#### 0.46.0
* Initial support for Mi Band 5
* Initial support for TLW64
* Amazfit GTR/GTS: Fix broken activity data on newer firmwares
* Big refactoring of the device discovery activity (See PR #1927 description for details)
* Add about screen
* New icon for Amazfit Bip
* Avoid duplicated entries in preferred media player selection
* Avoid a lot of crashes and improve error handling in various places

#### 0.45.1
* Amazfit GTR/GTS: Fix connection issue with latest firmwares (probably other Huami devices also affected)
* Add experimental support for TinyWeatherForecastGermany

#### 0.45.0
* Initial support for Amazfit T-Rex
* Amazfit Bip S: Support installation of latest .res
* Amazfit Bip S: Support longer notification messages
* Huami: Limit weather forecast to 7 days to fix problems with "Weather Notification" 0.3.11
* Huami: Improve music playback information
* Huami: Ensure cutting strings on UTF-8 border
* Stop incoming call notification when VoIP calls are missed
* Fix a crash when with Farsi translation

#### 0.44.2
* Huami: Support flashing newer GPS firmware and GPS ALM
* Amazfit Bip S: Support music control
* Amazfit Bip S: Support flashing firmware, res, gps firmware, watchfaces, fonts and GPS CEP
* Amazfit Bip S: Allow setting high MTU (much faster firmware installation, default off since it does not work for some)
* Amazfit Bip S: remove disconnect notification and button action settings (they do not work)
* Mi Band 4 (possibly others): Fix detected RES version being always 69 for non-whitelisted res files
* Fossil Hybrid HR: Add last notification widget
* Try to fix vanishing incoming call information when VoIP call support is enabled
* Allow setting device aliases (useful if you manage multiple ones of the same type)

#### Version 0.44.1
* Amazfit Bip S: Support setting shortcuts
* Amazfit Bip S: Fix setting display items
* Amazfit Bip S: Fix incoming call notification
* Huami: Fix menu items vanishing from the device when they were never configured through Gadgetbridge
* Lenovo Watch9: Fix launch of wrong calibration activity
* Reduce calls to onSetMusicInfo/onSetMusicState when playing music

#### Version 0.44.0
* Initial support for WatchX(Plus)
* Add support for Amazfit GTR Lite (untested and incomplete)
* Fossil Hybrid HR: Fix some issues with custom widgets
* Fossil Hybrid HR: Allow setting alarm titles and descriptions
* Fossil Hybrid HR: Fix step data parsing
* Amazfit GTS: Fix setting menu items with low MTU
* Amazfit GTR: Allow setting menu item like GTS
* ZeTime: Support setting the watch language
* ZeTime: Support rejecting calls
* ZeTime: Try to fix weather conditions on newer firmware
* ZeTime: Fix could not synchronize calendar on connect
* ZeTime: Fix calendar event time and date
* ZeTime: Send up to 16 upcoming calendar events on connect if option is enabled
* Allow set light/dark theme according to system settings (new default)

#### Version 0.43.3
* Fossil Hybrid HR: Initial support for activity tracking (no sleep yet)
* Fossil Hybrid HR: Support setting alarms on newer firmware
* Amazfit GTR/GTS: Fix flashing watchfaces and maybe firmware/res update (still untested)
* Amazfit GTS: Support enabling/disabling menu items on the watch
* Implement transliteration for Korean

#### Version 0.43.2
* Fossil Hybrid HR: Allow choosing and cropping image to be set as watch background
* Fossil Hybrid HR: Option to draw circles around widgets
* Fossil Hybrid HR: Experimental firmware update support
* Fossil Hybrid HR: Fix vibration strength setting
* Huami: Do not display firmware information and whitelist information when flashing watchfaces
* Huami: Disable air quality indicator on Huami devices instead of showing 0
* Bangle.js: Change encoded char set to match Espruino's 8 bit fonts
* Steps/Sleep averages: Skip days with zero data

#### Version 0.43.1
* Initial support for Amazfit Bip S (incomplete, needs the official app once to obtain the pairing key)
* Amazfit Bip Lite: Allow relaxing firmware checks to allow flashing of the regular Bip firmware (for the brave)
* Fossil Hybrid HR: Fix notification history on newer firmwares
* Fossil Hybrid HR: Add option to disable widget circle
* Bangle.js: Don't set time if the option is turned off in settings
* Bangle.js: DST and time zone fixes
* Add Arabic-style Eastern Arabic numerals to transliteration

#### Version 0.43.0
* Initial support for Fossil Hybrid HR (needs complicated key extraction, read wiki)
* Fossil: Allow switching off the Q Icon and use the default Gadgetbridge icon
* Fix VoIP call handling during DND
* Fix find-my-phone for Android 10
* Huami: Fix crash when calendar event description or title was null
* Huami: Ignore all-day events when syncing calendar events

#### Version 0.42.1
* Fix accepting/rejecting calls on Android 9
* Mi Band 3/4, Amazfit Bip/Cor/GTS/GTR: Option to sync calendar events as reminder

#### Version 0.42.0
* Initial iTag support
* Fix indefinitely lasting Bluetooth scans when location permission has not been granted
* Try to stop incoming VoIP call notification when the call is answered
* Vectorize some icons and add a new Mi Scale 2 icon
* Mi Band 4: Make high MTU optional, fixes problems on some phones
* ZeTime: Fix probably broken support (duplicate id used by Fossil)

#### Version 0.41.1
* Huami: allow to have alarms without snooze feature
* Mi Band 2: Properly stop a call notification when text notifications are disabled
* VoIP calls: ignore notifications with only one action, assuming it is an outgoing call
* Try to fix notifications from Business Calendar

#### Version 0.41.0
* JYou Y5: Initial support
* Mi Band 2/Amazfit Bip: Redesign button actions for easy music control setup and support long presses on Bip
* Amazfit Bip: Remove RES file limit (for BipOS)
* Huami: Automatically toggle alarm switch when toggling on the Band/Watch while in Alarm settings in Gadgetbridge
* Recognize Pixart-Messenger as Chat App

#### Version 0.40.1
* Mi Band/Amazfit: Recognize changes when toggling alarm on device (immediately when connected, else when connecting)
* Mi Band/Amazfit: Fix some bugs with stuck connection when re-connecting
* Mi Band 4: Support higher MTU for multiple times faster firmware transfer (probably also Amazfit GTR/GTS)
* Amazfit Cor: Fix setting language to Chinese manually

#### Version 0.40.0
* Fossil Q Hybrid: Initial support
* Bangle.js: Initial support
* Reserve Alarm for Calendar feature restricted to Mi Band 1/2 and moved to per-device settings
* New icon for App Manager

#### Version 0.39.1
* Try to actively re-connect when a connection gets interrupted (interval grows up to 64 seconds)
* Mi Band2/Amazfit Bip: Make button action settings per-device and enable for Amazfit Bip

#### Version 0.39.0
* Amazfit GTS: Initial and incomplete support, mostly untested
* Add forward/backward buttons to charts for faster navigation
* Debug: allow to reset last fetch date for Huami devices

#### Version 0.38.0
* Amazfit GTR: Initial and incomplete support, mostly untested
* Amazfit Bip: add Portuguese to the list of selectable languages
* Mi Band 4: Enable emoji font setting
* Makibes HR3: Support the English version
* Makibes HR3: Enable Bluetooth pairing for working re-connection
* Work around crash when trying to display changelog
* Sleep detection settings: Rolling 24 hours (existing style) or Noon to noon
* Add alternative color to heart rate in chart settings

#### Version 0.37.1
* Amazfit Bip Lite: Support flashing firmware and watch faces

#### Version 0.37.0
* Initial Makibes HR3 support
* Amazfit Bip Lite: Initial working support, firmware update is disabled for now (we do not have any firmware for testing)
* Amazfit Cor 2: Enable Emoji Font setting and 3rd party HR access
* Find Phone now also vibration in addition to playing the ring tone
* ID115: All settings are now per-device
* Time format settings are now per-device for all supported devices
* Wrist location settings are now per-device for all supported devices
* Work around broken layout in database management activity
* Show toast in case no app is installed which can handle GPX files
* Mi Band 4/Amazfit Bip Lite: Trim white spaces and new lines from auth key
* Mi Band 4/Amazfit Bip Lite: Display a toast and do not try to pair if there was no auth key supplied
* Skip service scan if supported device could be recognized without UUIDs during discovery

#### Version 0.36.2
* Amazfit Bip: Untested support for Lite variant 
* Force Lineage OS to ask for permission when Trust is used to fix non-working incoming calls
* Charts: List multiple sleep sessions per day

#### Version 0.36.1
* Mi Band 2/3/4, Amazfit Bip/Cor: Add setting to expose the HR sensor to 3rd party apps
* Mi Band 4: Really fix weather location not being updated on the Band
* Mi Band 4: Fix call notification not stopping when call gets answered or rejected on the phone
* Amazfit Bip/Cor: Support for custom emoji font
* ZeTime: Enable emoji support
* ZeTime: Make watch language the same as the phone language by default
* New status and alarms widget
* Fix crash when entering notification filter settings
* Make diagram settings accessible from charts activity
* Add option to hide the floating plus button in the main activity
* Fix a potential crash on Android 4.4 KitKat

#### Version 0.36.0
* Initial Mijia LYWSD02 support (Smart Clock with Humidity and Temperature Sensor), just for setting the time
* Mi Band 3/4: Allow enabling the NFC menu where supported (useless for now)
* Mi Band 3/4, Amazfit Cor/Bip: Set language immediately when changing it (not only on connect)
* Mi Band 3/4, Amazfit Cor/Bip: Add icons for "swimming" and "exercise"
* Mi Band 4: Support flashing the V2 font
* Mi Band 4: Fix weather location not being updated on the Band
* Mi Band 4: remove unsupported DND setting from settings menu
* Amazfit Bip/Cor: Fix resetting of last fetched date for sports activities
* Amazfit Bip: Fix sharing GPX files for some Apps
* Pebble: Use Rebble Store URI
* Support LineageOS 16.0 weather provider
* Add Averages to Charts
* Allow togging between weekly and monthly charts

#### Version 0.35.2
* Mi Band 1/2: Crash when updating firmware while phone is set to Spanish
* Mi Band 4: Enable music info support (displays now on the band)
* Mi Band 4: Support setting date format (for built-in watch-faces)
* Amazfit Cor 2: Try to fix empty menu on device

#### Version 0.35.1
* Mi Band 4: Support flashing watch-faces, res and firmware (.ft untested)

#### Version 0.35.0
* Mi Band 4: Initial support (WARNING: INITIAL SETUP NEEDS MI FIT WITH ACCOUNT AND ROOT, NOT A RECOMMENDED DEVICE FOR GADGETBRIDGE)

#### Version 0.34.1
* Mi Band 1: Fix crash when entering per-device settings
* Mi Band 3: Allow setting date format in per-device settings
* ZeTime: Fix time stamps
* Fix a crash when flashing an non-whitelisted firmware while using Gadgetbridge in Spanish

#### Version 0.34.0
* Mi Band 1/2/3/Bip/Cor: Migrate many settings to per-device settings (new settings icon in device card in main activity)
* Mi Band 3: Fix setting menu items with 2.4 firmware and add support for the new timer menu
* Amazfit Bip/Cor, Casio: Add support for muting incoming calls
* ZeTime: Remove endless recursion in ZeTime settings
* Recognize FairEmail notifications as generic email notifications

#### Version 0.33.1
* Mi Band 3: Recognize "Xiaomi Band 3"
* Amazfit Bip: Add German, Italian, French and Turkish to language settings

#### Version 0.33.0
* BFH-16: Initial support
* Mi Band 2/3/Bip/Cor: Generate random per-device security keys when pairing, allow manual override to still support multiple android devices connecting to the same device
* Mi Band 3: Add Indonesian, Thai, Arabic, Vietnamese, Portuguese, Dutch, Turkish and Ukrainian to language settings
* Mi Band 3: Support flashing latest Japanese-Korean font
* Amazfit Cor 2: Initial experimental support (untested)
* Pebble: Add PebbleKit extension for reopening last app
* Casio: Bug fixes and improvements
* Lookup contacts also in work profile
* Fix searching in application name when blacklisting
* Remove misleading title from database management activity when no legacy database is available

#### Version 0.32.4
* Make VoIP call support optional (disabled by default)
* Amazfit Bip: GPX export corrections
* ZeTime: Fix setting alarms
* ZeTime: Fix wrong activity timestamps
* ZeTime: Set HR alarm limits when changed, not only on connect
* ZeTime: Sync preferences from the watch to Gadgetbridge settings

#### Version 0.32.3
* Fix a crash in charts due to a broken German translation
* Fix a crash when transliterating emoji
* Amazfit Bip/Cor: Support disconnect notification (must be configured in Bip settings for Cor also for now)

#### Version 0.32.2
* Fix setting alarms under some circumstances
* Support calls notifications for some VoIP apps
* Mi Band 3: Enable fetching sports activities (currently only useful for flushing activities)
* Casio: Improve stability
* Casio: Add explicit support for GB-6900B, GB-X6900B and GB-5600B

#### Version 0.32.1
* Fix db deadlock on alarm migration

#### Version 0.32.0
* Initial support for Casio GB-6900B
* Increase number of alarms and store them per-device 
* Support factory reset in debug activity (Mi Band 1/2/3, Bip, Cor)
* Filter out Unicode control sequences (fixes problems with Telegram and probably others)
* Fix endless loop resulting in OOM when RTL support is enabled
* Recognize p≡p as an email app
* No longer display Android paired devices in that were not a paired with Gadgetbridge
* Amazfit Bip: Allow flashing latest GPS firmware
* Pebble: Native support for M7S watch face
* No1 F1: Support for a Chinese clone

#### Version 0.31.3
* Pebble: Fix crash with DISMISS and OPEN actions

#### Version 0.31.2
* Pebble: Fix a regression that caused non-working mute, open and dismiss actions
* Fix setting language to Czech manually
* Ignore summary notification from K-9 Mail (caused notification spamming)

#### Version 0.31.1
* Pebble: Fix crash when no canned replies have been set
* Pebble: Let the firmware show localized default canned replies if none have been set
* Amazfit Bip: Fix importing GPS tracks that have been recorded with Firmware 1.1.5.02
* Display measured hr value in debug screen

#### Version 0.31.0
* Pebble: Send all wearable notification actions (not only reply)
* Pebble: Always allow reply action even if untested features are turned off
* Pebble: Temporarily disable broken auto remove notification feature
* Amazfit Bip: Allow flashing latest GPS firmware (Mili_dth.gps)
* Mi Band 3/Amazfit Bip/Amazfit Cor: Send Fahrenheit if units are set to imperial
* Roidmi 3: Fix and enable support
* Mi Band 3/Amazfit Bip: fix find phone crash
* Prevent re-sending old notifications to the wearable
* Enhancement and Fixes for Bengali Transliteration
* Disable excessive logging in RTL support

#### Version 0.30.0
* Amazfit Bip + Mi Band 3: Support for right to left display (configurable) (#976)
* Add Arabic, Bengali Farsi, Persian, Scandinavian transliteration
* Add support for some Roidmi FM receivers
* Mi Band 3: Allow enabling the "Workout" menu item
* Mi Band 3: Support for night mode configuration
* Huami devices: fix seldom activity/sports synchronization problem (#1264)
* Preferences: Make minimum heart rate configurable (lower values will be disregarded) 
* Preferences: Configure minimum time between notifications
* Preferences: Group language settings
* Attempt to fix BLE connection issues on Samsung S devices
* Week sleep and steps charts: display balance (actual value vs. desired value) 
* Live Activity: show current/maximum heart rate, display minute steps and total steps and more improvements
* Live Activity: fix discrepancy between number of steps in Gadgetbridge and wearable device
* Fix missing caller ID for incoming calls on Android 9
* Support for easy sharing of log files via the Debug screen
* Misc small bugfixes

#### Version 0.29.1
* Mi Band 3: Support setting language to to German, Italian, French, Polish, Japanese, Korean (read wiki)
* Mi Band 3: Support flashing latest RES files
* Mi Band 3: Fix notification text not being displayed
* Mi Band 3/Cor/Bip: Display app name when no app specific icon is available
* Teclast: add/improve H1 and H3 watch recognition
* Support transliteration for Lithuanian and Bengali
* Fix BLE reconnect issues in certain conditions
* Various fixes for display issues on small screens
* Fix some potential NPEs
* WIP: Display start and end of sleep in statistics

#### Version 0.29.0
* New Device: Initial support for ID115
* New Device: Initial support for Lenovo Watch9
* Show splash screen during startup
* Vertically align device icon in main activity
* Try to support the google clock application (untested)
* Amazfit Cor: Allow to configure displayed menu items
* Amazfit Cor: Support basic music control
* Amazfit Cor: Fix flashing font files
* Amazfit Bip: improved GPX export
* Amazfit Bip: Fix exported GPX file names for *FAT storage
* Amazfit Bip: Fix current weather not being displayed with later firmwares
* Amazfit Bip/Cor: Try to fix device being sometimes stuck in connecting state
* Mi Band 2: Put some device specific settings into its own settings category
* Mi Band 3: Support disabling of on-device menu items
* Mi Band 3: Support locking the Mi Band screen (swipe up to unlock)
* Mi Band 2/3: New icon
* NO1 F1: Set time during initialization

#### Version 0.28.1
* Fix wrong weather icon mapping in rare cases
* Fix device discovery on Android 4.4
* Amazfit Bip: Use UTC in gpx tracks for better compatibility with external software
* Amazfit Bip: Add the (localized) activity type to the gpx filename
* Amazfit Bip: Fix weather on latest firmwares

#### Version 0.28.0
* Initial support for ZeTime: time, weather and activity data sync, notification support and music playback control is working
* Amazfit Bip/Cor: Rework firmware detection to cope with new version scheme
* Amazfit Bip: Support setting language to Russian
* Amazfit Cor: Support language switching on newer firmwares
* Mi Band 3: support setting language (english and spanish tested)
* Mi Band 3: Fix pairing
* Mi Band 3: Send AQI to enable display of current temperature

#### Version 0.27.1
* Pebble: Change app store search to point to RomanPort's Pebble app store
* Mi Band 3: Allow flashing fonts (untested)
* Amazfit Bip: Allow flashing latest firmwares
* Amazfit Cor: Allow flashing Bip fonts (untested)
* Allow to limit auto fetch to a user configurable time interval

#### Version 0.27.0
* Initial support for Mi Band 3 (largely untested, needs to be connected to Mi Fit once)
* Option for automatic activity sync after screen unlock
* Allow hiding activity transfer notification on Android Oreo and above
* Allow blacklisting of PebbleKit notifications for individual apps
* Allow blacklisting all application at once
* Forward Skype notifications to wearable even if "local only" flag is set
* Show Gadgetbridge logo behind cards in main activity
* Always stop BT/BTLE discovery when exiting the discovery activity
* Amazfit Bip/Cor: Fix scheduled setting for "display on lift wrist" preference
* Amazfit Bip/Cor: add recent firmwares to whitelist
* Pebble: Fix a rare crash in WebView

#### Version 0.26.5
* Fix autoreconnect at boot on recent Android versions
* Bluetooth connection is more stable on Oreo
* Potentially fix the watch continuously vibrating after call pickup
* Amazfit Bip: Add setting to configure shortcuts (swipe to right from watchface)
* Recognize Q8 as a HPlus device

#### Version 0.26.4
* Fix a bug with Toasts appearing every time a notification arrives when bluetooth is disabled
* Pebble 2: Add optional GATT client only mode that might help with connection stability
* Amazfit Cor: Fix detection of newer firmwares
* Mi Band 2: Fix text notifications not appearing with short vibration patterns

#### Version 0.26.3
* Amazfit Bip: Add proper mime type to shared gpx files
* Amazfit Bip: allow to set displayed menu items
* Amazfit Bip: fix fetching logs from device via debug menu
* Amazfit Bip: Raise .res limit to 700000 bytes for modded files

#### Version 0.26.2
* Amazfit Bip: Time and timezone fixes for Android <=6 when exporting GPX

#### Version 0.26.1
* Fix crashes and connection problems on Android 6 and lower

#### Version 0.26.0
* Amazfit Bip: Initial support for GPS tracks
* Pebble: Wind speed/direction support and bugfixes for weather when using background javascript

#### Version 0.25.1
* Amazfit Cor: Try to send weather location instead of AQI
* Amazfit Bip: Support setting start end end time for background light when lifting the arm
* Pebble: various fixes and improvements for background javascript
* Explicitly ask for RECEIVE_SMS permission to fix problems with Android 8

#### Version 0.25.0
* Initial support for Xwatch
* Move the connected device to top in control center
* Add adaptive launcher icon for Android 8.x
* No longer plot heart rate graph when device was detected as not worn
* Pebble: Small fixes for background js (e.g. Pebble-Casio-WV58DE)
* Pebble: native (non bg js) support for weather in Simply Light watchface

#### Version 0.24.6
* Display the chat icon for notifications coming from Kontalk and Antox
* Pebble: Fix for background js which try to send floats (e.g. TrekVolle)
* Mi Band 2: Change the way vibration patterns work, also fixes problems with missing text on newer firmwares

#### Version 0.24.5
* Fix crash in settings activity with export location
* Fix notification deletion regression
* Add 'Ł' and 'ł' to transliteration map
* Omnijaws Weather: correctly pick today's min and max temperature
* Fix alarm details activity on small screen
* Pebble: mimic online check of TrekVolle when using background js

#### Version 0.24.4
* Amazfit Bip: Fix language setting on new firmwares

#### Version 0.24.3
* Charts: Try to fix another crash
* Pebble: Fix weather for some watchfaces when using background JS
* Amazfit Cor: Allow watchfaces to be flashed (untested)
* Amazfit Bip: Better detection for flashable font types
* Fix number only privacy option

#### Version 0.24.2
* Fix crash when changing the periodic database export interval
* Amazfit Bip: Allow fonts and new res format to be flashed
* Amazfit Cor: Allow new res format to be flashed
* Pebble: Background js fixes

#### Version 0.24.1
* Amazfit Bip: prevent menu icons from vanishing when using firmware 0.1.0.51
* Pebble: "find phone" feature for upcoming pebble helper app

#### Version 0.24.0
* Fix logs sometimes not containing stacktraces
* Support periodic database export
* Support transliteration for Arabic and Farsi
* Try to make alarm details scrollable (for small devices)
* Amazfit Bip: Implement find phone feature
* Amazfit Bip: Support flashing latest GPS firmware
* Amazfit Cor: Support flashing latest firmware
* Pebble: Fix crash with experimental background javascript
* Charts: Several fixes to the MPAndroidChart library

#### Version 0.23.2
* Mi Band 1S: Fix sync problem with firmware 4.16.11.15 (probably also Mi Band 1.0.15.0 and Mi Band 1A 5.16.11.15)
* Amazfit Cor: Fix problem with firmware >=1.0.6.27 being detected as Mi Band 2

#### Version 0.23.1
* Initial support for Omnijaws weather service
* Amazfit Bip: Allow installation of latest gps firmware
* Amazfit Cor: Fixes for installing newer firmware versions

#### Version 0.23.0
* Initial support for LineageOS/CyanogenMod weather provider
* Amazfit Bip/Cor: Support for current weather temperature
* Amazfit Bip/Cor: Display firmware version and type also for non-whitelisted firmware files

#### Version 0.22.5
* Unlock Teclast H10 support using the same code as H30
* Amazfit Bip: Fix installation of 0.1.0.11 Firmware
* Amazfit Bip/Cor: Send three days of weather forecast including (untranslated) conditions
* Workaround for a crash on Android 4.4 when connecting

#### Version 0.22.4
* Mi Band 2/Bip/Cor: Whole day HR support
* Mi Band 2/Bip/Cor: Prevent writing a lot of HR samples to the database when not using the live activity feature
* Pebble: Fix some nasty crashes which occur since 0.22.0
* Workaround for non-working notifications from wechat and outlook

#### Version 0.22.3
* Amazfit Bip: Allow flashing watchfaces
* Amazfit Cor: Fix flashing new .res files
* Mi Band 2/HRX/Bip/Cor: Try to fix stuck activity sync

#### Version 0.22.2
* Charts: Add setting to disable swiping charts left/right and some UI changes
* Pebble: Use the configured unit system also for system weather app
* Mi Band 2: Fix HR being absent in charts
* Amazfit Bip: Allow manual language selection in settings
* Amazfit Cor: Fix firmware update

#### Version 0.22.1
* Mi Band 2: Fix being detected as Amazfit Bip which lead to various problems especially on newly paired devices

#### Version 0.22.0
* Pebble: Experimental support for background javascript, allows weather and other features for watchapps without special Gadgetbridge support
* Add experimental support for Amazfit Cor and Mi Band HRX (no firmware update on the latter)
* Mi Band 2: Support more icons and textual notifications for more apps
* Add some quick action buttons to Gadgetbridge's notification
* Add transliteration support for ukrainian cyrillic characters
* Fix annoying toast in Mi Band settings

#### Version 0.21.6
* Amazfit Bip: Fix non-working notifications from Outlook, Yahoo Mail and GMail
* HPlus: Fix Unicode encoding
* No.1 F1: Alarms support
* No.1 F1: Show data fetching progress

#### Version 0.21.5
* Mi2/Bip: Support setting distance units (metric/imperial)

#### Version 0.21.4
* Mi2/Bip: Fix sleep detection for newer firmwares
* Mi2/Bip: Fix ancient bug resulting in wrong activity data at the beginning in diagrams and aggregate data
* No.1 F1: Support setting time format and distance units (metric/imperial)
* Pebble: Support setting distance units to miles for Health (need to reactivate Health in App Manager after toggling)
* HPlus: Make changing distance unit system effective immediately on toggling

#### Version 0.21.3
* Amazfit Bip: Auto-switch language on connect (English, Simplified Chinese, Traditional Chinese), requires FW 0.0.9.14+

#### Version 0.21.2
* Amazfit Bip: Support flashing CEP and ALM files for AGPS
* Amazfit Bip: Initial experimental support for fetching logs from the watch
* Mi2/Bip: Send user info to the device (fixes calories and distance display)
* Mi2/Bip: Fix firmware update progressbar being stuck at the end
* Pebble/Bip: Support more notification icons
* Pebble: Automatically determine color for unknown notifications on Pebble Time

#### Version 0.21.1
* Initial support for EXRIZU K8 (HPLus variant)
* Amazfit Bip: fix long messages not being displayed at all
* Mi Band 2: Support multiple button actions
* NO.1 F1: Fetch sleep data
* NO.1 F1: Heart rate support
* Pebble: Support controlling the current active media playback application
* Fix suspended activities coming to front when rotating the screen

#### Version 0.21.0
* Initial NO.1 F1 support
* Initial Teclast H30 support
* Amazfit Bip: Display GPS firmware version
* Amazfit Bip: Fix E-Mail notifications
* Amazfit Bip: Fix call notification with unknown caller
* Amazfit Bip: Fix crash when weather is updated and device reconnecting
* Mi2/Bip: Fix crash when synchronizing calendar to alarms
* Pebble: Fix crash when taking screenshots on Android 8.0 (Oreo)
* Pebble: Support some google app icons
* Pebble: try to support spotify
* Mi Band 2: Support configurable button actions
* Fix language being reset to system default

#### Version 0.20.2
* Amazfit Bip: Various fixes regarding weather, add condition string support for FW 0.0.8.74
* Amazfit Bip: enable caller display in later firmwares
* Amazfit Bip: initial firmware update support (EXPERIMENTAL, AT YOUR OWN RISK)
* Re-enable improved speed zones tab
* Probably fix crash with certain music players
* Improve theme and add changelog icon

#### Version 0.20.1
* Amazfit Bip: Support icons and text body for notifications
* Mi Band: Fix setting smart alarms

#### Version 0.20.0
* Initial Amazfit Bip support (WIP)
* Various theming fixes
* Add workaround for blacklist not properly persisting
* Handle resetting language to default properly
* Pebble: Pass booleans from Javascript Appmessage correctly
* Pebble: Make local configuration pages work on most recent WebView implementation
* Pebble: Allow to blacklist calendars
* Add Greek and German transliteration support
* Various visual improvements to charts

#### Version 0.19.4
* Replace or relicense CC-NC licensed icons to satisfy F-Droid
* Mi Band 2: Make info to display on the Band configurable
* Mi Band 2: Support wrist rotation to switch info setting
* Mi Band 2: Support goal notification setting
* Mi Band 2: Support do not disturb setting
* Mi Band 2: Support inactivity warning setting 

#### Version 0.19.3
* Pebble: Fix crash when calendar access permission has been denied
* Pebble: Fix wrong timestamps with Morpheuz running on Firmware >=3
* Mi Band 2: Improve reliability when fetching activity data
* HPlus: Fix intensity calculation without continuous connectivity
* HPlus: Fix Unicode handling
* HPlus: Initial not work detection
* Fix memory leak
* Only show Realtime Chart on devices supporting it

#### Version 0.19.2
* Pebble: Fix recurring calendar events only appearing once per week
* HPlus: Fix crash when receiving calls without phone number
* HPlus: Detect unicode support on Zeband Plus
* No longer quit Gadgetbridge when bluetooth gets turned off

#### Version 0.19.1
* Fix crash at startup
* HPlus: Improve reconnection to device
* Improve transliteration

#### Version 0.19.0
* Pebble: allow calendar sync with Timeline (Title, Location, Description)
* Pebble: display calendar icon for reminders from AOSP Calendar
* HPlus: try to fix latin characters showing as random Chinese text
* Improve reconnection with BLE devices
* Improve generic notification reliability by trying to restart the notification listener when stale/crashed
* Other small bugfixes

#### Version 0.18.5
* Applied some material design guidelines to Charts and Pebble app management
* Changed colours: deep sleep is now dark blue, light sleep is now light blue
* Support for exporting and importing of preferences in addition to the database
* Visual improvements of the pie charts
* Add filter by name in the App blacklist activity
* Pebble: improve compatibility with watch app configuration pages
* Pebble: display battery percentage (will only update once an hour)
* HPlus: users can now decide whether they want to pair the device or not, hopefully fixing some connection problems (#642)
* HPlus: display battery state and warn on low battery

#### Version 0.18.4
* Mi Band 2: Display realtime steps in Live Activity
* Mi Band: Attempt to recognize Mi Band model with hwVersion = 8
* Alarms activity improvements and fixes
* Make Buttons in the main activity easier to hit

#### Version 0.18.3
* Fix bug that caused the same value in weekly charts for every day on Android 6 and older

#### Version 0.18.2
* Mi Band 2: Fix crash on "chat" or "social network" text notification (#603)

#### Version 0.18.1
* Pebble: Fix Firmware installation on Pebble Time Round (broken since 0.16.0)
* Start VibrationActivity when using "find device" button with Vibratissimo
* Support material fork of K9

#### Version 0.18.0
* All new GUI for the control center
* Add Portuguese pt_PT and pt_BR translations
* Add Czech translation
* Add Hebrew translation and transliteration
* Consistently display device specific icons already during discovery
* Add sleep chart displaying the last week of sleep
* Huge speedup for weekly charts when changing days
* Drop support for importing pre Gadgetbridge 0.12.0 database
* Pebble: allow configuration web pages (clay) to access device location
* Mi Band 2: Initial support for text notifications, caller ID, and icons (requires font installation) (#560)
* Mi Band 2: Support for flashing Mili_pro.ft* font files
* Mi Band 2: Improved firmware/font updated
* Mi Band 2: Set 12h/24h time format, following the Android configuration (#573)
* Improved BLE discovery and connectivity

#### Version 0.17.5
* Automatically start the service on boot (can be turned off)
* Pebble: PebbleKit compatibility improvements (Data logging)
* Pebble: Display music shuffle and repeat states for some players
* Pebble 2/LE: Speed up data transfer

#### Version 0.17.4
* Better integration with android music players
* Privacy options for calls (hide caller name/number)
* Send a notification to the connected if the Android Alarm Clock rings (com.android.deskclock)
* Fixes for Cyrillic transliteration
* Pebble: Implement notification privacy modes
* Pebble: Support weather for Obsidian watchface
* Pebble: add a dev option to always and immediately ACK PebbleKit messages to the watch
* HPlus: Support alarms
* HPlus: Fix time and date sync and time format (12/24)
* HPlus: Add device specific preferences and icon
* HPlus: Support for Makibes F68

#### Version 0.17.3
* HPlus: Improve display of new messages and phone calls
* HPlus: Fix bug related to steps and heart rate
* Pebble: Support dynamic keys for natively supported watchfaces and watchapps (more stability across versions)
* Pebble: Fix error Toast being displayed when TimeStyle watchface is not installed
* Mi Band 1+2: Support for connecting without BT pairing (workaround for certain connection problems)

#### Version 0.17.2
* Pebble: Fix temperature unit in Timestyle Pebble watchface
* Add optional Cyrillic transliteration (for devices lacking the font)

#### Version 0.17.1
* Pebble: Fix installation of some watchapps
* Pebble: Try to improve PebbleKit compatibility
* HPlus: Fix bug setting current date

#### Version 0.17.0
* Add weather support through "Weather Notification" app
* Various fixes for K9 mail when using the generic notification receiver
* Add a preference to hide the persistent notification icon of Gadgetbridge
* Pebble: Support for build-in weather system app (FW 4.x)
* Pebble: Add weather support for various watchfaces
* Pebble: Add option to disable call display
* Pebble: Add option to automatically delete notifications that got dismissed on the phone
* Pebble: Bug fix for some PebbleKit enabled 3rd party apps (TCW and maybe other)
* Pebble 2/LE: Improve reliability and transfer speed
* HPlus: Improved discovery and pairing
* HPlus: Improved notifications (display + vibration)
* HPlus: Synchronize time and date
* HPlus: Display firmware version and battery charge
* HPlus: Near real time Heart rate measurement
* HPlus: Experimental synchronization of activity data (only sleep, steps and intensity)
* HPlus: Fix some disconnection issues

#### Version 0.16.0
* New devices: HPlus (e.g. Zeblaze ZeBand), contributed by João Paulo Barraca
* ZeBand: Initial support: notifications, heart rate, sleep monitoring, user configuration, date+time
* Pebble 2: Fix Pebble Classic FW 3.x app variant being prioritized over native Pebble 2 app variant
* Charts (Live Activity): Fix axis labels color in dark theme
* Mi Band: Fix ginormous step count when using Live Activity
* Mi Band: Improved performance during activity sync
* Mi Band 2: Fix activity data missing after doing manual hr measurements or live activity
* Support sharing firmwares/watchapps/watchfaces to Gadgetbridge
* Support for the "Subsonic" music player (#474)

#### Version 0.15.2
* Mi Band: Fix crash with unknown notification sources

#### Version 0.15.1
* Improved handling of notifications for some apps
* Pebble 2/LE: Add setting to limit GATT MTU for debugging broken BLE stacks
* Mi Band 2: Display battery status

#### Version 0.15.0
* New device: Liveview
* Liveview: initial support (set the time and receive notifications)
* Pebble: log pebble app logs if option is enabled in pebble development settings
* Pebble: notification icons for more apps
* Pebble: Further improve compatibility for watchface configuration
* Mi Band 2: Initial support for firmware update (tested so far: 1.0.0.39)

#### Version 0.14.4
* Pebble 2/LE: Fix multiple bugs in re-connection code, honor reconnect tries from settings
* Mi Band 2: Experimental support for activity recognition
* Mi Band 2: Fix time setting code

#### Version 0.14.3
* Pebble: Experimental support for pairing and using all Pebble models via BLE
* Mi Band 1: Fix regression causing display of wrong activity data (#440)
* Mi Band 2: Support for continuous heart rate measurements in live activity view

#### Version 0.14.2
* Pebble 2: Fix a bug where the Pebble got disconnected by other unrelated LE devices

#### Version 0.14.1
* Mi Band 2: Initial experimental support for activity data
* Mi Band 2: Send the fitness goal (steps) to the band
* Pebble 2: Work around firmware installation issues (tested with upgrading 4.2 to 4.3)
* Pebble: Further improve compatibility for watchface configuration
* Pebble: add Kickstart watch face to app manager on FW 4.x
* Charts: display the total time range, not just the range with available data

#### Version 0.14.0
* Pebble 2: Initial experimental support for P2/PT2 using BLE
* Pebble: Special support in device discovery activity (MUST be used to get Pebble 2 working)
* Pebble: Improve compatibility for watchface configuration
* Mi Band 2: support for heart rate measurement during sleep
* Mi Band 2: configuration option to activate the display on lift
* Mi Band 2: configuration option to display the time + date or just the time
* Mi Band 2: honor the wear location configuration option

#### Version 0.13.9
* Pebble: use the last known location for setting sunrise and sunset
* Pebble: fix Health disappearing forever when deactivating through app manager (and get it back for affected users)
* Mi Band 2: More fixes for connection issues (#408)

#### Version 0.13.8
* Mi Band 2: fix connection issues for users of Mi Fit (#408, #425)
* Mi Band 1A: fix firmware update for certain 1A models

#### Version 0.13.7
* Pebble: Fix configuration of certain pebble apps (eg. QR Generator, Squared 4.0)
* Pebble: Add context menu option in app manager to search a watchapp in the Pebble app store
* Mi Band: allow to delete Mi Band address from development settings
* Mi Band 2: Initial support for heart rate readings (Debug activity only)
* Mi Band 2: Support disabled alarms
* Attempt to fix spurious device discovery problems
* Correctly recognize Toffeed, Slimsocial and MaterialFBook as Facebook notification sources 

#### Version 0.13.6
* Mi Band 2: Support for multiple alarms (3 at the moment)
* Mi Band 2: Fix for alarms not working when just one is enabled

#### Version 0.13.5
* Mi Band 2: Support setting one alarm
* Pebble: Health compatibility for Firmware 4.2
* Improve support for K9 when generic notifications are used (K9 notifications set to never)

#### Version 0.13.4
* Mi Band: Initial support for recording heart and displaying rate values
* Mi Band: Support for testing vibration patterns directly from the preferences
* Mi Band: Clean up vibration preferences
* Possibly fix logging to file on certain devices (#406)
* Mi Band 2: Possibly fix weird connection interdependence between Mi 1 and 2 (#323)
* Mi Band 1S: White list firmware 4.16.4.22
* Mi Band: try application level pairing again, in order to support data sharing with Mi Fit (#250)
* Pebble: new icons and colors for certain apps
* Debug-screen: added button to test "new functionality", currently live sensor data for Mi Band 1

#### Version 0.13.3
* Fix regressions with missing bars and labels in charts
* Allow to set notification type in Debug activity
* Move "Disconnect" back to the bottom of the context menu
* Mi Band 2: Display Message and Phone icons

#### Version 0.13.2
* Support deleting devices (and their data) in control center
* Sort devices lexicographically in control center
* Do not forward group summary notifications (could fix some duplicate notifications)
* Pebble: Support for health on FW 4.1
* Mi Band: Fix offline charts not displaying heartrate for Mi 1S

#### Version 0.13.1
* Improved BLE scanning for Android 5.0+
* Pebble: try to work around duplicate Telegram messages and support Telegram icon
* Pebble: fix some incompatibilities with certain PebbleKit Android apps

#### Version 0.13.0
* Initial working Mi Band 2 support (only notifications, no activity and heart rate support)
* Experimental support for Vibratissimo devices

#### Version 0.12.2
* Fix for user attribute database table getting spammed and store sleep and steps goals properly

#### Version 0.12.1 (release withdrawn)
* Pebble: Fix activity data being associated with the wrong device and/or user in some cases causing them to invisible in charts
* Remove special handling for Conversations notifications since upstream dropped special pebble support

#### Version 0.12.0 (release withdrawn)
* NB: User action needed to migrate existing data! 
* Store activity data per device and provider to allow multiple devices of the same kind with separate data. Migration is available, except for Pebble Misfit data. Existing data from multiple devices of the same kind (eg. multiple Mi Bands) will get merged while importing.
* In Control Center, display known devices even when Bluetooth is off
* In Control center, new menu point to launch the new "Database management" activity
* Pebble: Support for Pebble Health on Firmware 4.0
* Pebble: Optionally allow raw Pebble Health data to be stored in database completely (for later interpretation, when we are able to decode it)
* Mi Band: fix displaying of deep sleep vs. light sleep (was inverted)

#### Version 0.11.2
* Mi Band: support for devices that cannot pair with the band (#349)

#### Version 0.11.1
* Various fixes (including crashes) for location settings
* Pebble: Support Pebble Time 2 emulator (needs recompilation of Gadgetbridge)
* Fix a rare crash when, due to Bluetooth problems, when a device has no name
* Fix activity fetching getting stuck when double tapping (#333)
* Mi Band: in the Device Discovery activity, do not display devices that are already paired
* Mi Band: only allow automatic re-connection on disconnect when the device was previously fully connected
* Mi Band: fix a rare crash when reading data fails due to Bluetooth problems
* Mi Band: log full activity sample to help deciphering activity kinds (#341)
* Mi Band 2: improved discovery mechanism to not rely on MAC addresses (#323)
* Charts: only display heart rate samples on devices that support that
* Add more logging to detect problems with external directories (#343)

#### Version 0.11.0
* Pebble: new App Manager (keeps track of installed apps and allows app sorting on FW 3.x)
* Pebble: call dismissal with canned SMS (FW 3.x)
* Pebble: watchapp configuration presets
* Pebble: fix regression with FW 2.x (almost everything was broken in 0.10.2)

#### Version 0.10.2
* Pebble: allow to manually paste configuration data for legacy configuration pages
* Pebble: various improvements to the configuration page
* Pebble: Support FW 4.0-dp1 and Pebble2 emulator (needs recompilation of Gadgetbridge)
* Pebble: Fix a problem with key events when using the Pebble music player

#### Version 0.10.1
* Pebble: set extended music info by dissecting notifications on Android 5.0+
* Pebble: various other improvements to music playback
* Pebble: allow ignoring activity trackers individually (to keep the data on the pebble)
* Mi Band: support for shifting the device time by N hours (for people who sleep at daytime)
* Mi Band: initial and untested support for Mi Band 2
* Allow setting the application language

#### Version 0.10.0
* Pebble: option to send sunrise and sunset events to timeline
* Pebble: fix problems with unknown app keys while configuring watchfaces
* Mi Band: BLE connection fixes
* Fixes for enabling logging at without restarting Gadgetbridge
* Re-enable device paring activity on Android 6 (BLE scanning needs the location preference)
* Display device address in device info

#### Version 0.9.8
* Pebble: fix more reconnect issues
* Pebble: fix deep sleep not being detected with Firmware 3.12 when using Pebble Health
* Pebble: option in AppManager to delete files from cache
* Pebble: enable pbw cache and watchface configuration for Firmware 2.x
* Pebble: allow enabling of Pebble Health without "untested features" being enabled
* Pebble: fix music information being messed up
* Honour "Do Not Disturb" for phone calls and SMS

#### Version 0.9.7
* Pebble: hopefully fix some reconnect issues
* Mi Band: fix live activity monitoring running forever if back button pressed
* Mi Band: allow low latency firmware updates, fixes update with some phones
* Mi Band: initial experimental and probably broken support for Amazfit
* Show aliases for BT Devices if they had been renamed in BT Settings
* Do not show a hint about App Manager when a Mi Band is connected

#### Version 0.9.6
* Again some UI/theme improvements
* New preference to reconnect after connection loss (defaults to true)
* Fix crash when dealing with certain old preference values
* Mi Band: automatically reconnect when back in range after connection loss
* Mi Band 1S: display heart rate value again when invoked via the Debug view

#### Version 0.9.5
* Several UI Improvements
* Easier First-time setup by using a FAB
* Optional Dark Theme
* Notification App Blacklist is now sorted
* Gadgetbridge Icon in the notification bar displays connection state
* Logging is now configurable without restart
* Mi Band 1S: Initial live heartrate tracking
* Fix certain crash in charts activity on slower devices (#277)

#### Version 0.9.4
* Pebble: support pebble health datalog messages of firmware 3.11 (this adds support for deep sleep!)
* Pebble: try to reconnect on new notifications and phone calls when connection was lost unexpectedly
* Pebble: delay between re-connection attempts (from 1 up to 64 seconds)
* Fix crash in charts activities when changing the date, quickly (#277)
* Mi Band: preference to enable heart rate measurement during sleep (#232, thanks computerlyrik!)
* Mi Band: display measured heart rate in charts (#232)
* Mi Band 1S: full support for firmware upgrade/downgrade (both for Mi Band and heart rate sensor) (#234)
* Mi Band 1S: fix device detection for certain versions

#### Version 0.9.3
* Pebble: Fix Pebble Health activation (was not available in the App Manager)
* Simplify connection state display (only connecting->connected)
* Small improvements to the pairing activity
* Mi Band 1S: Fix for mi band firmware update

#### Version 0.9.2
* Mi Band: Fix update of second (HR) firmware on Mi1S (#234)
* Fix ordering issue of device info being displayed

#### Version 0.9.1
* Mi Band: fix sporadic connection problems (stuck on "Initializing" #249)
* Mi Band: enable low latency connection (faster) during initialization and activity sync
* Mi Band: better feedback for firmware update
* Device Item is now clickable also when the information entries are visible
* Fix enabling log file writing #261

#### Version 0.9.0
* Pebble: Support for configuring watchfaces/apps locally (clay) or though web browser (some do not work)
* Pebble: hide the alarm management activity as it's unsupported
* Mi Band: Improve firmware detection and updates, including 1S support
* Mi Band: Display HR FW for 1S
* FW and HW versions are only displayed after tapping on the "info" button in Control Center
* Do not display activity samples when navigating too far in the past
* Fix auto connect which was broken under some circumstances

#### Version 0.8.2
* Fix database creation and updates (thanks @feclare)
* Add experimental widget to set the alarm time to a configurable number of hours in the future (thanks @0nse)
* Use ckChangeLog to display the Changelog within Gadgetbridge
* Workaround to fix logfile rotation (bug in logback-android)

#### Version 0.8.1
* Pebble: install (and start) freshly-installed apps on the watch instead of showing a Toast that tells the user to do so. (only applies to firmware 3.x)
* Pebble: fix crash while receiving Health data
* Mi Band 1S: support for synchronizing activity data (#205)
* Mi Band 1S: support for reading the heart rate via the "Debug Screen" #178

#### Version 0.8.0
* Pebble: Support Pebble Health: steps/activity data are stored correctly. Sleep time is considered as light sleep. Deep sleep is discarded. The pebble will send data where it seems appropriate, there is no action to perform on the watch for this to happen.
* Pebble: Fix support for newer version of morpheuz (>=3.3?)
* Pebble: Allow to select the preferred activity tracker via settings activity (Health, Misfit, Morpheuz)
* Pebble: Fix wrong(previous) contact being displayed on the pebble 
* Mi Band: improvements to pairing and connecting
* Fix a problem related to shared preferences storage of activity settings
* Very basic support Android 6 runtime permission
* Fix layout of the alarms activity

#### Version 0.7.4
* Refactored the settings activity: User details are now generic instead of Mi Band specific. Old settings are preserved.
* Pebble: Fix regression with broken active reconnect since 0.7.0
* Pebble: Support activation and deactivation of Pebble Health. Activation uses the User details as seen above. Insights are NOT activated.
  Please be aware that deactivation does NOT delete the data stored on the watch (but it seems to stop the tracking), and we do not know how to switch to metric length units.

#### Version 0.7.3
* Pebble: Report connection state to PebbleKit companion apps via content provider. NOTE: Makes Gadgetbridge mutual exclusive with the original Pebble app.
* Ignore generic notification when from SMSSecure when SMS Notifications are on

#### Version 0.7.2
* Pebble: Allow replying to generic notifications that contain a wearable reply action (tested with Signal)
* Pebble: Support setting up a common suffix for canned replies (defaults to " (canned reply)")
* Mi Band: Avoid NPEs when aborting an erroneous sync #205
* Mi Band: Fix discovery of Mi Band 1S
* Add a confirmation dialog when performing a db import
* Sort blacklist by package names

#### Version 0.7.1
* Pebble: allow re-installation of apps in pbw-cache from App Manager (long press menu)
* Pebble: Fix regression which freezes Gadgetbridge when disconnecting via long-press menu

#### Version 0.7.0
* Read upcoming events (up to 7 days in the future). Requires READ_CALENDAR permission 
* Fix double SMS on Sony Android and Android 6.0
* Pebble: Support replying to SMS form the watch (canned replies)
* Pebble: Allow installing apps compiled with SDK 2.x also on the basalt platform (Time, Time Steel)
* Pebble: Fix decoding strings in appmessages from the pebble (fixes sending SMS from "Dialer for Pebble")
* Pebble: Support incoming re-connections when device returns from "Airplane Mode" or "Stand-By Mode"
* Pebble: Fix crash when turning off Bluetooth when connected on Android 6.0
* Mi Band: reserve some alarm slots for alerting when upcoming events begin. NB: the band will vibrate at the start time of the event, android reminders are ignored
* Mi Band: Display unique devices Names, not just "MI"
* Some new and updated icons

#### Version 0.6.9
* Pebble: Store app details in pbw-cache and display them in app manager on firmware 3.x 
* Pebble: Increase maximum notification body length from 255 to 512 bytes on firmware 3.x
* Pebble: Support installing .pbl (language files) on firmware 3.x
* Pebble: Correct setting the timezone on firmware 3.x (pebble expects the "ID" eg. Europe/Berlin)
* Pebble: Show correct icon for activity tracker and watchfaces in app installer (language and fw icons still missing)
* Pebble: Fix crash when trying to install files though a file manager which are located inside the pbw-cache on firmware 3.x
* Support for deleting all activity data (in the 'Debug' screen)
* Don't pop up the virtual keyboard when entering the Debug screen
* Remove all pending notifications on quit
* Mi Band: KitKat: hopefully fixed showing the progress bar during activity data synchronization (#155)
* Mi Band 1S: hopefully fixed connection errors (#178) Notifications probably do not work yet, though

#### Version 0.6.8
* Mi Band: support for Firmware upgrade/downgrade on Mi Band 1A (white LEDs, no heartrate sensor)
* Pebble: fix regression in 0.6.7 when installing pbw/pbz files from content providers (eg. download manager)
* Pebble: fix installation of pbw files on firmware 3.x when using content providers (eg. download manager)   
* Pebble: fix crash on firmware 3.x when pebble requests a pbw that is not in Gadgetbridge's cache 
+ Treat Signal notifications as chat notifications
* Fix crash when contacts cannot be read on Android 6.0 (non-granted permissions)

#### Version 0.6.7
* Pebble: Allow installation of 3.x apps on OG Pebble (FW will be released soon)
* Fix crashes on startup when logging is enabled or when entering the app manager on some phones
+ Fix Pebble being detected as MI when unpaired and auto-connect is enabled
* Fix Crash when not having K9 Mail permissions (happens when installing K9 after Gadgetbridge) (#175)

#### Version 0.6.6
* Mi Band: Huge performance improvement fetching activity data
* Mi Band: attempt at fixing connection problems (#156)
* Pebble: Try to interpret sleep data from Misfit data
* Fix exporting the activity database on devices with read-only external storage (#153)
* Fix totally wrong sleep time in the sleep chart

#### Version 0.6.5
* Mi Band: Support "Locate Device" with Mi Band 1A (and Mi Band 1 with new firmware)
* Pebble: Support syncing steps from Misfit (untested features must be turned on to see them), intensity=steps, no sleep support yet
* Disable activity fetching when not supported
* Small improvements to live activity charts

#### Version 0.6.4
* Support pull down to synchronize activity data (#138)
* Display tabs in the Charts activity (#139)
* Mi Band: initial support for Mi Band 1a (the one with white LEDs) (thanks @sarg) (#136)
* Mi Band: Attempt at fixing problem with never finishing activity data fetching (#141, #142)
* Register/unregister BroadcastReceivers instead of enabling/disabling them with PackageManager (#134)
  (should fix disconnection because the service is being killed)

#### Version 0.6.3
* Pebble: support installation of language files (.pbl) on FW 2.x
* Try to prevent service being killed by disallowing backups

#### Version 0.6.2
* Mi Band: support firmware version 1.0.10.14 (and onward?) vibration
* Mi Band: get device name from official BT SIG endpoint
* Mi Band: initial support for displaying live activity data, screen stays on

#### Version 0.6.1
* Pebble: Allow muting (blacklisting) Apps from within generic notifications on the watch
* Pebble: Detect all known Pebble Versions including new "chalk" platform (Pebble Time Round)
* Option to ignore phone calls (useful for Pebble Dialer)
* Mi Band: Added progress bar for activity data transfer and fixes for firmware transfer progress bar
* Bug fix for app blacklist (some checkboxes where wrongly drawn as checked)

#### Version 0.6.0
* Pebble: WIP implementation of PebbleKit Intents to make some 3rd party Android apps work with the Pebble (eg. Ventoo)
* Pebble: Option to set re-connection attempts in settings (one attempt usually takes about 5 seconds)
* Support controlling all audio players that react to media buttons (can be chosen in settings)
* Treat SMS as generic notification if set to "never" (can be blacklisted there also if desired)
* Treat Conversations messages as chat messages, even if arrived via Pebble Intents (nice icon for Pebble FW 3.x)
* Allow opening firmware / app files from the download manager "app" (technically a content provider)
* Mi Band: whitelisted a few firmware versions

#### Version 0.5.4
* Mi Band: allow the transfer of activity data without clearing MiBand's memory
* Pebble: for generic notifications use generic icon instead of SMS icons on FW 3.x (thanks @roidelapluie)
* Pebble: use different icons and background colors for specific groups of applications (chat, mail, etc) (thanks @roidelapluie)
* In settings, support blacklisting apps for generic notifications

#### Version 0.5.3
* Pebble: For generic notifications, support dismissing individual notifications and "Open on Phone" feature (OG & PT)
* Pebble: Allow to treat K9 notifications as generic notifications (if notification mode is set to never)
* Ignore QKSMS notifications to avoid double notification for incoming SMS
* Improved UI of Firmware/App installer
* Device state again visible on lock screen
* Date display and navigation now working properly for all charts

#### Version 0.5.2
* Pebble: support "dismiss all" action also on Pebble Time/FW 3.x notifications
* Mi Band: show a notification when the battery is below 10%
* Graphs are now using the same theme as the rest of the application
* Graphs now show when the device was not worn by the user (for devices that send this information)
* Remove unused settings option in charts view
* Build target is now Android SDK 23 (Marshmallow)

#### Version 0.5.1
* Pebble: support taking screenshot from Pebble Time
* Fix broken "find lost device" which was broken in 0.5.0

#### Version 0.5.0
* Mi Band: fix setting wear location
* Pebble: experimental watchapp installation support for FW 3.x/Pebble Time
* Pebble: support Pebble emulator via TCP connection (needs rebuild with INTERNET permission)
* Pebble: use SMS/EMAIL icons for FW 3.x/Pebble Time
* Pebble: do not throttle notifications
* Support going forward/backwards in time in the activity charts
* Various small bugfixes to the App/FW Installation Activity

#### Version 0.4.6
* Mi Band: Fixed negative number of steps displayed (#91)
* Mi Band: fixed (re-) connection problems after band getting disconnected
* Pebble: new option to enable untested code (enable only if you like bad surprises)
* Pebble: always enable 2.x notifications with "dismiss all" action on FW 2.x (except for K9)
* Fixed slight steps graph distortion through black text labels
* Fixed control center activity and notification showing different device connection state
* Small firmware installation improvements
* Various refactoring and code cleanups

#### Version 0.4.5
* Enhancement to activity graphs: new graph showing the number of steps done today and in the last week
* New preference to set the desired fitness goal (number of steps to walk in one day)
* Mi Band: support for setting the fitness goal (the band will show the progress to the goal with the LEDs and vibrates when the goal is reached)
* Mi Band: send the wear location (left / right hand) to the device
* Mi Band: support for flashing firmware from .fw files (upgrades and downgrades are possible)
* Fixed crash when synchronizing activity data in the graphs activity and changing device orientation

#### Version 0.4.4
* Set Gadgetbridge notification visibility to public, to show the connection status on the lock screen
* Support for backup up and restoring of the activity database (via Debug activity)
* Support for graceful upgrades and downgrades, keeping your activity database intact
* Enhancement to activity graphs: new graphs for sleep data (only last night) accessible swiping right from the main graph
* Enhancement to graphs activity: it is now possible to fetch the activity data directly from this activity
* Pebble: experimental support for dismissing (all) notifications via actionable notifications (disabled by default)
* Pebble: make FW 3.x notifications available by default
* Mi Band: Set the graphs activity as the default action available with a single tap on the connected device

#### Version 0.4.3
* Mi Band: Support for setting alarms
* Mi Band: Bug fix for activity data synchronization

#### Version 0.4.2
* Material style for Lollipop
* Support for finding a lost device (vibrate until cancelled)
* Mi Band: Support for vibration profiles, configurable for notifications
* Pebble: Support taking screenshots from the device context menu (Pebble Time not supported yet)

#### Version 0.4.1
* New icons, thanks xphnx!
* Improvements to Sleep Monitor charts
* Pebble: use new Sleep Monitor for Morpheuz (previously Mi Band only)
* Pebble: experimental support for FW 3.x notification protocol
* Pebble: dev option to force latest notification protocol

#### Version 0.4.0
* Pebble: Initial Morpheuz protocol support for getting sleep data
* Pebble: Support launching of watchapps though the AppManager Activity
* Pebble: Support CM 12.1 default music app (Eleven)
* Pebble: Fix firmware installation when all 8 app slots are in use
* Pebble: Fix firmware installation when Pebble is in recovery mode
* Pebble: Fix error when reinstalling apps, useful for upgrading/downgrading
* Mi Band: Make vibration count configurable for different kinds of Notifications
* Mi Band: Initial support for fetching activity data
* Support rebooting Mi Band/Pebble through the Debug Activity
* Add highly experimental sleep monitor (accessible via long press on a device)
* Fix Debug activity (SMS and E-Mail buttons were broken)
* Add Turkish translation contributed by Tarik Sekmen

#### Version 0.3.5
* Add discovery and pairing Activity for Pebble and Mi Band
* Listen for Pebble Message Intents and forward notifications (used by Conversations)
* Make strings translatable and add German, Italian, Russian, Spanish and Korean translations
* Mi Band: Display battery status

#### Version 0.3.4
* Pebble: Huge speedup for app/firmware installation.
* Pebble: Use a separate notification with progress bar for installation procedure
* Pebble: Bug fix for being stuck while waiting for a slot, when none is available
* Mi Band: Display connection status in notification (previously Pebble only)

#### Version 0.3.3
* Pebble: Try to reduce battery usage by acknowledging datalog packets
* Mi Band: Set current time on the device (thanks to PR by @danielegobbetti)
* More robust connection state handling and display

#### Version 0.3.2
* Mi Band: Fix for notifications only working after manual connection
* Mi Band: Display firmware version
* Pebble: Display hardware revision
* Pebble: Check if firmware is compatible before allowing installation

#### Version 0.3.1
* Mi Band: Fix for notifications only working in Debug

#### Version 0.3.0
* Mi Band: Initial support (see README.md)
* Pebble: Firmware installation (USE AT YOUR OWN RISK)
* Pebble: Fix installation problems with certain .pbw files
* Pebble: Volume control
* Add icon for activity tracker apps (icon by xphnx)
* Let the application quit when in reconnecting state

#### Version 0.2.0
* Experimental pbw installation support (watchfaces/apps)
* New icons for device and app lists
* Fix for device list not refreshing when Bluetooth gets turned on
* Filter out annoying low battery notifications
* Fix for crash on some devices when creating a debug notification
* Lots of internal changes preparing multi device support

#### Version 0.1.5
* Fix for DST (summer time)
* Option to sync time on connect (enabled by default)
* Opening .pbw files with Gadgetbridge prints some package information
  (This was not meant to be released yet, but the DST fix made a new release necessary)

#### Version 0.1.4
* New AppManager shows installed Apps/Watchfaces (removal possible via context menu)
* Allow back navigation in ActionBar (Debug and AppManager Activities)
* Make sure Intent broadcasts do not leave Gadgetbridge
* Show hint in the Main Activity (tap to connect etc)

#### Version 0.1.3
* Remove the connect button, list all supported devices and connect on tap instead
* Display connection status and firmware of connected devices in the device list
* Remove quit button from the service notification, put a quit item in the context menu instead

#### Version 0.1.2
* Added option to start Gadgetbridge and connect automatically when Bluetooth is turned on
* stop service if Bluetooth is turned off
* try to reconnect if connection was lost

#### Version 0.1.1
* Fixed various bugs regarding K-9 Mail notifications.
* "Generic notification support" in Setting now opens Androids "Notification access" dialog.

#### Version 0.1.0
* Initial release
