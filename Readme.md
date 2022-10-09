# Awesome List of “Data Not Collected” Apps for iOS/iPadOS

Go to [the awesome list](#the-awesome-list).

Do you want to contribute? Please [submit a pull request](https://github.com/lifepillar/awesome-data-not-collected-ios/pulls)!

## FAQ

- **Why does this list exist?**

Because I couldn't find a similar list anywhere. And it is not possible to search the App Store based on privacy criteria. And because most of the apps in the world should fall into the «data not collected» category—but, alas, they are likely a scant minority, so this list will never be too hard to maintain (although I wish it eventually will, especially full with games and education apps).

- **Apple is collecting your data anyway: isn't this effort a contradiction and a waste of time?**

Answering this would require more words than I wish to spend for a FAQ. It is a legitimate question, though, for which you are encouraged to find an answer by yourself.

- **How do you decide whether an app can appear in this list?**

I look at the App Privacy section in the App Store. It is not ideal (see, for instance, [this paper](https://arxiv.org/abs/2206.06274)), but that is my compromise. Apps that do not collect any data are whitelisted by default. Apps that collect data linked to an identity are off-limits. For apps that collect data *not* linked to an identity, they can be accepted in any of the following circumstances:

- the data they collect is limited to diagnostics;
- it is reasonable to assume that the data collection is opt-in (e.g., an RSS reader that collects email and password only if the user signs in to a remote service rather than using a self-hosted server or the local storage);
- the source code of the app is publicly available.

- **How the hell are the apps classified? For instance, why are some password managers under Utilities and others under Productivity?**

Apps are classified according to the category they are assigned in the App Store. That is an inconsistent taxonomy, of course, but I do not have to think where to file each app.

- **If an app is listed here, does it mean that it does not track you?**

No. I only report what is in the App Privacy section of the App Store, which is a statement by the app's developer. Unless otherwise specified, I have not independently *verified* (say, by monitoring network connections or by static code analysis) that the apps listed below do not collect any data, or that they collect only the data they declare to collect. It is up to you whether to trust the developer and Apple. This list serves only as a reference to make it easier to find apps that are, in theory, the most privacy respecting.

- **Are the apps listed on this page free?**

In general, no, in no sense of the word. I do not care whether an app is open-source or not, I do not care whether an app is a free or paid download, and I do not care whether it has in-app purchases or it is based on a subscription model. The only requirement for an app to be eligible to be listed is that its developer declares that the app does not collect any data, or collects only a moderate amount of data (e.g., diagnostics), in any case *not* linked to an identity, as explained before.

- **Are the apps listed on this page open-source?**

In general, no. However, if I know that an app is open-source, a link to the source code is provided.

- **Why isn't `<PUT YOUR APP>` listed here? It doesn't collect any data! And it's awesome!**

Please [submit a pull request](https://github.com/lifepillar/awesome-data-not-collected-ios/pulls) to extend this list! But keep in mind that, although “Data-Not-Collected” apps are whitelisted by default, that does not mean that *any* such app can make it into this list. If an app looks fishy—say, an obscure “we-do-not-store-your-IP” VPN app—I prefer not to include it, no matter what the privacy section in the App Store says.

- **I know for sure that `<PUT YOUR APP>` is a privacy-conscious app, even if it must declare that it collects data due to the absurd rules imposed by Apple.**

This is going to lead to endless discussions, and we must have a clear way to draw a line. The rule I have chosen is simple and fast. There are undoubtedly lots of good privacy-respecting apps that do not appear in this list, which does not aim to be exhaustive by any means (rather, the opposite—see previous question). Feel free to make your own list! I'll be happy to link to it.

- **`<PUT YOUR APP>` must collect data linked to an identity by design (say, a banking app), but it respects your privacy anyway! Why won't you list it?**

Well, go ahead and use it: I am not saying that you shouldn't. But I do not list it here because it violates my fast and simple rule—that is, that app is off-topic.

- **Do you use all the apps listed here?**

- No, no one is (most likely) using all these apps.


## The Awesome List

### Board

- [**Mahjong!!**](https://apps.apple.com/app/mahjong/id347878114) Classic oriental puzzle
  - App privacy: Data Not Collected
  - Last version checked: 7.3

- [**SmallFish Chess for Stockfish**](https://apps.apple.com/app/smallfish-chess-for-stockfish/id675049147)
  - App privacy: Data Not Collected
  - Last version checked: 16.9.0

### Developer Tools

- [**Blink Shell: Mosh & SSH Client:**](https://apps.apple.com/app/blink-shell-code/id1594898306)
  - App privacy: Data Not Collected
  - Last version checked: 14.0.7
  - [Source code](https://github.com/blinksh/blink)

- [**iSH:**](https://apps.apple.com/app/ish-shell/id1436902243) Linux in your pocket
  - App privacy: Data Not Collected
  - Last version checked: 1.2.3
  - [Source code](https://github.com/ish-app/ish)


### Education

- [**Unwrap:**](https://apps.apple.com/app/unwrap/id1440611372) Learn coding with Swift
  - App privacy: Data Not Collected
  - Last version checked: 1.5


### Health & Fitness

- [**Ananda - PREMIUM:**](https://apps.apple.com/app/ananda-premium/id740204574) Meditate, Focus & Relax
  - App privacy: Data Not Collected
  - Last version checked: 1.3.0

- [**GymBook - Strength Training:**](https://apps.apple.com/app/gymbook-strength-training/id650113307) Workout diary
  - App privacy: Data Not Collected
  - Last version checked: 6.1.37

- [**Streaks Workout:**](https://apps.apple.com/app/streaks-workout/id1044950341) For all fitness levels
  - App privacy: Diagnostics (crash data)
  - Last version checked: 6.0.4


### Navigation

- [**Magic Earth Navigation & Maps:**](https://apps.apple.com/app/magic-earth-navigation-maps/id1007331679) Offline maps, traffic
  - App privacy: Data Not Collected
  - Last version checked: 7.6.7


### News

- [**NetNewsWire: RSS Reader:**](https://apps.apple.com/app/netnewswire-rss-reader/id1480640210) More news, less junk.
  - App privacy: Identifiers (User ID)
  - Last version checked: 6.0.2
  - [Source code](https://github.com/Ranchero-Software/NetNewsWire)

- [**Reeder 5:**](https://apps.apple.com/app/reeder-5/id1529445840) News reader
  - App privacy: Data Not Collected
  - Last version checked: 5.1

- [**tiny Reader RSS**](https://apps.apple.com/app/tiny-reader-rss/id689519762)
  - App privacy: Data Not Collected
  - Last version checked: 2.1.4


### Photo & Video

- [**VLC for Mobile**](https://apps.apple.com/app/vlc-for-mobile/id650377962)
  - App privacy: Diagnostics (crash data, performance data)
  - Last version checked: 3.2.13
  - [Source code](https://www.videolan.org/vlc/download-ios.html)


### Productivity

- [**Joplin:**](https://apps.apple.com/app/joplin/id1315599797) Note taking and to-do app
  - App privacy: Data Not Collected
  - Last version checked: 12.6.2
  - [Source code](https://github.com/laurent22/joplin/)

- [**KeePass Touch:**](https://apps.apple.com/app/keepass-touch/id966759076) The password manager
  - App privacy: Diagnostics (crash data, performance data, other diagnostic data)
  - Last version checked: 1.12.3

- [**KeePassium**](https://apps.apple.com/app/keepassium-keepass-passwords/id1435127111)
  - App privacy: Data Not Collected
  - Last version checked: 1.30

- [**MDNotes:**](https://apps.apple.com/app/mdnotes/id1471287219) A minimum markdown notes app
  - App privacy: Data Not Collected
  - Last version checked: 3.4

- [**miMind:**](https://apps.apple.com/app/mimind/id1385633717) Easy mind mapping
  - App privacy: Data Not Collected
  - Last version checked: 3.13

- [**Nextcloud:**](https://apps.apple.com/app/nextcloud/id1125420102) a safe home for all your data
  - App privacy: Data Not Collected
  - Last version checked: 4.2.1
  - [Source code](https://github.com/nextcloud/ios)

- [**Obsidian - Connected Notes**](https://apps.apple.com/app/obsidian-connected-notes/id1557175442)
  - App privacy: Data Not Collected
  - Last version checked: 1.0.5

- [**ProtonMail - Encrypted Email:**](https://apps.apple.com/app/protonmail-encrypted-email/id979659905) Fast, private & secure
  - App privacy: Diagnostics (crash data)
  - Last version checked: 1.15.11
  - [Source code](https://github.com/ProtonMail/ios-mail)

- [**Strongbox - KeePass & PwSafe:**](https://apps.apple.com/app/strongbox-keepass-pwsafe/id897283731) The Premium KeePass manager
  - App privacy: Data Not Collected
  - Last version checked: 1.54.7
  - [Source code](https://github.com/strongbox-password-safe/Strongbox)

- [**System Activity Monitors**:](https://apps.apple.com/app/system-activity-monitors/id386118145) Memory, Battery, CPU…
  - App privacy: Data Not Collected
  - Last version checked: 3.15

### Puzzle

- [**Able Black:**](https://apps.apple.com/app/able-black/id1085908608) A story driven puzzle game
  - App privacy: Data Not Collected
  - Last version checked: 4.0.1

- [**Klocki:**](https://apps.apple.com/app/klocki/id1105390093) Minimal puzzle game
  - App privacy: Data Not Collected
  - Last version checked: 1.02

- [**Zip-Zap:**](https://apps.apple.com/app/zip-zap/id1146138135) Stuff that moves. Anyhow.
  - App privacy: Data Not Collected
  - Last version checked: 2.11


### Reference

- [**Mactracker**](https://apps.apple.com/app/mactracker/id311421597)
  - App privacy: Data Not Collected
  - Last version checked: 4.6.1


### Social Networking

- [**FluffyChat:**](https://apps.apple.com/app/fluffychat/id1551469600) Matrix messenger
  - App privacy: Diagnostics (Crash Data)
  - Last version checked: 1.3.1


### Travel

- [**Organic Maps:**](https://organicmaps.app/)  free offline maps app
  - App privacy: Data Not Collected
  - Last version checked: 2022.08.23
  - [Source code](https://github.com/organicmaps/organicmaps)

### Utilities

- [**a-Shell:**](https://apps.apple.com/app/a-shell/id1473805438) Local interactive terminal
  - App privacy: Data Not Collected
  - Last version checked: 1.8.3
  - [Source code](https://github.com/holzschu/a-shell)

- [**File Browser - Document Manager**](https://apps.apple.com/app/filebrowser-document-manager/id364738545)
  - App privacy: Data Not Collected
  - Last version checked: 20.33

- [**Hamm Seismograph**](https://apps.apple.com/app/hamm-seismograph/id704450894)
  - App privacy: Data Not Collected
  - Last version checked: 2.2

- [**IOSKeePass:**](https://apps.apple.com/app/ioskeepass/id1516678863) MiniKeePass fork
  - App privacy: Data Not Collected
  - Last version checked: 2.3.4

- [**iVim:**](https://apps.apple.com/app/ivim/id1266544660) *The* text editor!
  - App privacy: Data Not Collected
  - Last version checked: 2.47
  - [Source code](https://github.com/terrychou/iVim)

- [**NIOSH Sound Level Meter**](https://apps.apple.com/app/niosh-sound-level-meter/id1096545820)
  - App privacy: Data Not Collected
  - Last version checked: 1.2.5

- [**Onion Browser:**](https://apps.apple.com/app/onion-browser/id519296448) Secure, anonymous web with Tor
  - App privacy: Data Not Collected
  - Last version checked: 2.7.7
  - [Source code](https://github.com/onionbrowser/onionbrowser)

- [**OpenVPN Connect:**](https://apps.apple.com/app/openvpn-connect/id590379981)
  - App privacy: Data Not Collected
  - Last version checked: 3.2.3

- [**PCalc Lite:**](https://apps.apple.com/app/pcalc-lite/id300311831) The Best Calculator
  - App privacy: Diagnostics (analytics, app functionality)
  - Last version checked: 3.11.1

- [**Raivo OTP:**](https://apps.apple.com/app/raivo-otp/id1459042137) OTP management done right!
  - App privacy: Data Not Collected
  - Last version checked: 1.3.2
  - [Source code](https://github.com/raivo-otp/ios-application)

- [**Tofu:**](https://apps.apple.com/app/tofu-authenticator/id1082229305) Two-factor authentication
  - App privacy: Data Not Collected
  - Last version checked: 1.11
  - [Source code](https://github.com/calleluks/Tofu)

- [**TouchPad:**](https://apps.apple.com/app/touchpad/id297623931) Mobile keyboard and trackpad
  - App privacy: Diagnostics (crash data)
  - Last version checked: 6.3.2

- [**Wallabag 2 official:**](https://apps.apple.com/app/wallabag-2-official/id1170800946) Wallabag client
  - App privacy: Diagnostics
  - Last version checked: 6.0.4
  - [Source code](https://github.com/wallabag/ios-app)

- [**WireGuard:**](https://apps.apple.com/app/wireguard/id1441195209) Fast, modern secure VPN
  - App privacy: Data Not Collected
  - Last version checked: 1.0.15
  - [Source code](https://www.wireguard.com/repositories/)


