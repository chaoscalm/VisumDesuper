Visum Desuper
========
![398807234-f7416e73-67ac-4104-aaa3-7787fc4d14f1](https://github.com/user-attachments/assets/2c339e8a-ccf2-44b9-a7d8-de8f3580495b)

**Visum Desuper** is a fork of [GMaps WV](https://f-droid.org/en/packages/us.spotco.maps/)
[GMaps WV Archived Repository](https://github.com/Divested-Mobile/Maps)

Changelog for Visum Desuper
---------
* Merged the latest translations from weblate that weren't merged
* Simplified the building logic
* Fixed the Cookie consent warning
* Added a basic black theming to the top bar

Overview
--------
Visum Desuper is a WebView wrapper for using Google Maps without exposing your device

Features
--------
- Clears private data on close
- Blocks access to Google trackers and other third-party resources
- Restricts all network requests to HTTPS
- Allows toggling of location permission

Downsides
-------
- Navigation is not available, only turn-by-turn direction list
- WebRTC isn't blocked due to WebView limitations
- Cache isn't cleared due to resource/data considerations, however could allow tracking without other data (cookies)
- Manually clear app cache if necessary, may be addressed in future

Developers Credit
-------
- @woheller69 for discovering that page loaded resources weren't being blocked
- @woheller69 for adding proper location support
- @woheller69 for adding location sharing to other map apps
- @woheller69 for disabling WebView telemetry
- @R Raj for the sharing intent support
  
Projects Credit
-------
- @Tavi DivestOS
- @Google/Android/AOSP for the icons, License: Apache 2.0, https://google.github.io/material-design-icons/

Translations
-------
- Arabic: jonnysemon
- Bulgarian: trunars
- Chinese (Simplified): Crit
- Croatian: lukapiplica
- Czech: Fjuro
- Estonian: Priit Jõerüüt
- Finnish: huuhaa
- French: cultrarius
- Galician: josé m
- German: thereisnoanderson
- Hindi: Shankh
- Indonesian: Adrien N
- Italian: Dark Space
- Malayam: Shankh
- Polish: Eryk Michalak, Marcin Mikołajczak
- Portuguese (Brazil): lucasmz-dev, ruanon
- Russian: gfbdrgng, maz1lovo, XblateX
- Spanish: Diego Sanguinetti, gallegonovato
- Tamil: TamilNeram
- Ukrainian: Fqwe1
