###### ALPHA ACCEPTANCE TEST

```sh
 Localization Test
 Usability & UX Test
 User Interface Test
```

| Test Suite | Test Case | Prerequisite | Test Data | Test Procedure | Expected Result | Actual Result |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| A | B | C | D | E | F | G |


LOCALIZATION  
allow to test mobile app adaptation for specific target audience in accordance with cultural specifics

###### TS1: verifications
- [ ] ID1: determine languages supported by app
- [ ] ID1: ensure the correctness of translation
- [ ] ID1: verify correctness of translation in accordance with theme of app
- [ ] ID1: date formats
- [ ] ID1: delimiters in numbers



USABILITY testing (reflector, loop)		
ensure convenience of using app
intuitive interface with accepted standards
fast and easy-to-use app
quick and easy step app with less functionality is better than slow and difficult application with many features

###### TS1: satisfaction/efficiency/effectiveness
- [ ] ID1: buttons are of normal size and placed in one area of screen
- [ ] ID1: app works in multitasking mode
- [ ] ID1: navigation of important app modules
- [ ] ID1: icons and pictures look natural
- [ ] ID1: color of buttons that perform same function is the same
- [ ] ID1: text is simple, clear and visible to users
- [ ] ID1: short sentences and paragraphs are possible to read
- [ ] ID1: optimal font size
- [ ] ID1: app components are synchronized with users' actions
- [ ] ID1: speed of response of element is high enough
- [ ] ID1: ensure buttons have required size and be suitable to big fingers
- [ ] ID1: ensure buttons are placed in same sanction of the screen to avoid confusion
- [ ] ID1: ensure icons are natural and consistent with the app
- [ ] ID1: ensure that buttons which have same function also have same color
- [ ] ID1: ensure validation for tapping zoom-in and zoom-out facilities should be enabled
- [ ] ID1: ensure keyboard input is minimized
- [ ] ID1: ensure app provides a method for going back and undoing action within an acceptable duration
- [ ] ID1: ensure that contextual menu is not overloaded because it has to be used quickly
- [ ] ID1: ensure that text is kept simple and clear to be visible to users
- [ ] ID1: ensure that short sentences and paragraphs are readable and not too big or too small
- [ ] ID1: validate app prompts users whenever the user starts downloading large amount of data
- [ ] ID1: ensure that all strings are converted into proper languages whenever a language translation facility is available
- [ ] ID1: ensure that app items are always synchronized according to users' actions



UI TESTING (loadui, jubula, fitnesse)		
ensure graphic user interface meets specifications

###### TS1: verifications
- [ ] ID1: compliance with standards of ui
- [ ] ID1: check app ui with standard screen resolution
- [ ] ID1: responsiveness of app on different devices
- [ ] ID1: test main design element: buttons, icons, colors, links, fonts, font sizes, layout, text boxes, text format, label, caption, list
- [ ] ID1: correct display of various elements on retina and non-retina screen
- [ ] ID1: all elements display with portrait and landscape page orientation



FUNCTIONAL testing (appium, robotium, ranorex)		
black-box test focusing on user requirements and interactions
ensure app works as defined requirements
ensure app performs expected functions
testing user interaction
testing transactions

###### TS1: installation and running app
- [ ] ID1: installation should take place without errors
- [ ] ID1: app should start correctly
###### TS1: business functionality
- [ ] ID1: basic flows should run properly
###### TS1: interruption test
- [ ] ID1: incoming, outgoing calls, sms
- [ ] ID1: battery discharge/removal
- [ ] ID1: disconnect, connect network/wifi
- [ ] ID1: disconnect, connect sd-card
###### TS1: constant user feedback
- [ ] ID1: progress bard
- [ ] ID1: proper button reaction on pressing
- [ ] ID1: network access error message
- [ ] ID1: attemp to delete important information
- [ ] ID1: availability and syncronization of sound, vibration, visual notifications
###### TS1: update test
- [ ] ID1: all user data is saved after updates
- [ ] ID1: update progress is displayed properly
- [ ] ID1: test various ways to install updates (wifi, bluetooth, usb)
###### TS1: device resource test
- [ ] ID1: lack of space to install or run app
- [ ] ID1: memory leaks
- [ ] ID1: install/replace app on sd-card
- [ ] ID1: absence of functions supported by app (sd-card, camera etc.)
###### TS1: others
- [ ] ID1: information error messages are correct on time
- [ ] ID1: verify social networks function
###### TS1: others 2
- [ ] ID1: validate whether all required mandatory fields are working as required
- [ ] ID1: validate whether mandatory fields are displayed in the screen differently from optional fields
- [ ] ID1: validate whether app works as requirement when app starts/stops
- [ ] ID1: validate whether app goes into minimized mode whenever of incoming phone call
- [ ] ID1: validate whether phone is able to store, process, receive sms when app is running
- [ ] ID1: validate whether phone is able to perform multitasking requirement when it needs
- [ ] ID1: validate app allows necessary social network options
- [ ] ID1: validate app supports payment gateway transactions as required by app
- [ ] ID1: validate that the page scrolling scenarios are being enabled in app as necessary
- [ ] ID1: validate navigation between relevant modules in app are as required
- [ ] ID1: validate that truncation errors are absolutely to an affordable limit
- [ ] ID1: validate that users receive proper error message
- [ ] ID1: validate that app resumes at last operation in case of hard reboot or crash
- [ ] ID1: validate whether installation of app can be done smoothly
- [ ] ID1: validate that app performs auto start facility according to the requirements
- [ ] ID1: validate whether app provides available user guide for those who are not familiar to app
