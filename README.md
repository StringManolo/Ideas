# Ideas
Ideas for future projects, pending projects or projects i been working on for a long time.

## New

### NeuroBlade
Agetic hacking tool

### GoogleSearchCLI
CLI tool for google search

### NextGenPanther
Privacy/Security oriented Browser from scratch for powerusers with AI, scripting and a lot of features.

### RealtimeAudioAnonymizer
ATT -> TTS -> Loopback audio hijacking (bluethoot or male to male jack)

### RogueLike Autochess
Android game

### SecurityNoticeTGBot
TelegramBot that alerts you instally as soon as a vulnerability is public. 

### WebAI2CLI 
Scripts to use web version of chats from different AI tools but from the terminal.

### ServerlessWebs
Just some random stuff for my fullstack portfolio

### TermuxBasedApps
Fork and strip and edit Termux code to autorun and execute a set if hardcoded/dynamic instructions. 

### DumpGithub
Extract everything from an account and make a backup (track changes and report on them)

### AndroidExploitKit
An exploit kit that checks for vulns on Android devices and generate reports.

### LinuxDroid
Linux distro ported to NDK to run directly on Android to improve performance over proot solutions

### PuppeteerQJS
Port puppeter to QJS (qjsNetworkSockets based, need C SSL support first)

### BashTestingLib
Library for professional testing of bash apps

### CLIGUI
Study all the possible approachs to generate rich native UI interfaces ran from terminal apps (Probably needs a Termux fork and api fix to port to desktop with Electron, Kivi, QT, or Web)

### SocialNetwork
A free social network based on P2P

### SIMPLE2026
Redesign of the programming language to compile to other languages

### GithubHostedComponents
- Host modules and other stuff directly on github and import them locally (json?, no idea how this will work on node and browser (tainted DOM))

### AndroidUnroot
- API that garants max Android control possible without root.

### DebianBasedDistro
- Designed for Proot / qemu
- Make it main system
- Installer with ncursesw or raw bash to select default packages when installed (this way i can chose between installing a "hacking, dev, user, minimal, ..." distro version.

### ChromiteCLI
- Control Android Chromite from terminal (test how bypass security without root to control the browser)
- Ideas on how to:
  - UserScript that exposes API (can't bind locally no?)
  - Chrome protocol (is it even available)
  - Browser extensions (can extensions bind ports? does rev shell works fine here? This might be most solid approach for close to full browser control)
  - Proxy (can a local proxy do this? i don't think so)
  - UserScript that connects to local service (this should work to have control of a single webpage? But context will be lost. Maybe acting as a push and pull server and loading the script in every single webapage will do the trick, but i will have no control over the full browser, only webpages context, but might be enought for lot of usages like simple navigation).

### TelegramMinimalWeb
- Create a web client to run Telegram (purpouse to create automation, cli control, etc without security/privacy problems). 

### TelegramWebManager
- UserScripts like TamperMonkey to automatize telegram tasks
- Make estable core with modules so it can be extended with AI support, etc
- Check how to load everything with CLI so UserScript can expose an API to control it from CLI.

----------

## Features / Updates

### AutoPwn
- Start writting simple demo modules that can be improved later

### qjsNetworkSockets
- Add native support for SSL
- Add hook to replace node server by qjs while keeping logic and modules running in node (shared memory?)
- Benchmark real prod express apps in quickjs

### SelfControl
- Port to Kotlin
- Workflow to compile
- Add E2E testing with different Android versions

### DarkMeseenger & DarkMessengerAndroid
- Rewrite (need to swap design logic, modularize more and chose better language choices). 
> I don't have the proficence yet to code such complex design in Kotlin/Java, better to think about C++ or Javascript (web assembly?) designs.

### Puppeteer
- Fix puppeteer ARM / Musl support if no one else does

### DotEnvCleaner
- Add testing (and try usage on real project NeuroBlade)

### CLIPI
- Keep using CLIPI in real pentesting to find missing features

### BAHAMUT
- Make repo private before pushing local hacking modules

### Vulnera
- Keep adding new vulns
- Make repo less ugly

### AGENT
- Keep Working locally with different models 
- Backup 

### TCP
- Keep adding to the documentation

### SteelSpellScale
- Port files to web friendly formats to reduce download size of resources
- Add a good map
- Add level/combat system
- Add loading screen (or check to load resources on the background)
- Add the menus for characters, options, save, etc.

### SpamStorm
- Port to puppeteer

### 02heroLLMShacking 
- Keep investigating

### FloatingVolumeControl
- Add workflow to compile using github actions
- Improve battery usage

### MothSignal
- Remake with a more solid approach (maybe needs ffmpeg fork or hook)

### user-lookup
- Update to 2026
- Improve patterns
- Add testing

### HackingTermux
- Keep Working on it (find first revenue sources for the project)
- Swap ngrok references for new hosting mobile (book revision n°2)

### OP5
- Make a modern GUI
- Add more sources

### Pidgeon
- Port to serverless
- Improve crypto
- Add Android frontend (maybe webview based for simplicity)

### Methodology
- Make a cli tool that allows to check mark vulns checked in research (also web version with localstorage) to keep track of vulns non/tested
- Update it to include AI vulns, and new vulns

### nbmxbsf 
- Add testing.
- Make more public modules

### stop
- Improve subdomain takeover tool

### email
- Update to 2026 (probably not working anymore)

### Panther (v2)
- Paid version (not full open source)
- Autoupdates
- Tabs
- Background videos in floating window
- Fullscreen support for videos
- scriptable.sleep
- AI support (uses demo api for free / guides user how to get their own key / 100% automated on first run?) 
- AI support APIs fallback (different free apis and lastly, local llm + llama.cpp as NDK)
- Improve UI (modern design and new images)
- Allow to config start screen
- Fix http support (allowed by default, option to config)
- New settings menu
- Improve userAgent change on UI
- Allows to run as a floating window like Termux:Float
- User Scripts
- User Automation (manage automation "workflows")
- Port to Kotlin?



