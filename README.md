# runxel/uses
Specifics about the software (and some hardware) equipment I use. The page is part of the [uses.tech](https://uses.tech/) project. None of the links are affiliate.  


🏁 = Windows, 🍎 = Mac, 🐧 = Linux  
If not other specified it runs on Windows and Mac.

Last updated: June 2022

---

## 💻 Software
- [Firefox](https://www.mozilla.org/de/firefox/new/): Best browser.  
	<details markdown="1">
	<summary>Firefox add-ons used …</summary>

	- [Add custom search engine](https://addons.mozilla.org/de/firefox/addon/add-custom-search-engine/)
	- [Bloody Vikings!](https://addons.mozilla.org/de/firefox/addon/bloody-vikings/)
	- [Brief](https://addons.mozilla.org/de/firefox/addon/brief/)
	- [Decentraleyes](https://addons.mozilla.org/de/firefox/addon/decentraleyes/)
	- [DjVu.js Viewer](https://addons.mozilla.org/de/firefox/addon/djvu-js-viewer/)
	- [DownThemAll!](https://addons.mozilla.org/de/firefox/addon/downthemall/)
	- [Firefox Multi-Account Containers](https://addons.mozilla.org/de/firefox/addon/multi-account-containers/)
	- [Livemarks](https://addons.mozilla.org/de/firefox/addon/livemarks/)
	- [Multi-touch Zoom](https://addons.mozilla.org/de/firefox/addon/multi-touch-zoom/)
	- [Reddit Enhancement Suite](https://addons.mozilla.org/de/firefox/addon/reddit-enhancement-suite/)
	- [Regex Search](https://addons.mozilla.org/de/firefox/addon/regexsearch/)
	- [Search by Image](https://addons.mozilla.org/de/firefox/addon/search_by_image/)
	- [SingleFile](https://addons.mozilla.org/de/firefox/addon/single-file/)
	- [Smart Referer](https://addons.mozilla.org/de/firefox/addon/smart-referer/)
	- [SponsorBlock](https://addons.mozilla.org/de/firefox/addon/sponsorblock/)
	- [Stylus](https://addons.mozilla.org/de/firefox/addon/styl-us/)
	- [uBlock Origin](https://addons.mozilla.org/de/firefox/addon/ublock-origin/)
	</details>
- [Thunderbird](https://www.thunderbird.net/): This is how I read my emails 📧.
- "Dot File"-able settings are in a special repo.

### 👨🏻‍💻 Development
- [VSCode](https://code.visualstudio.com/): Fantastic editor.
	<details markdown="1">
	<summary>VSCode plugins used …</summary>

	_(default plugins not listed)_
	- Apache Conf
	- Auto Close Tag
	- Bookmarks
	- Calculate
	- Change Color Format
	- Dotfiles Syntax Highlighting
	- Duplicate action
	- EditorConfig for VS Code
	- Excel Viewer
	- gitignore
	- Gruvbox Material
	- Hex Editor
	- language-stylus
	- Markdown Links
	- Markdown Notes
	- Material Icon Theme
	- Nim
	- Open in Applicatoin
	- open in browser
	- Open in Github
	- Polacode
	- PrintCode
	- SonarLint
	- Sort lines
	- Spell Right
	- TODO Highlight
	</details>
- [Sublime Text](http://www.sublimetext.com/) – Redefined the way we look at text editors, and what they should be able to do. Sadly lost it's mojo a couple of years ago. Slow development. Was more or less replaced by VSCode for me... 
- [Windows Terminal](https://github.com/microsoft/terminal) [🏁 only]: Finally a nice terminal for Windows! Even steers Linux (WSL). Together with its SSH functionality (install via Windows' "Optional Features") it also replaced _putty_ for me.  Did you know you can start the new Terminal by typing in "wt" in the adress bar of the Explorer? (Same for "cmd" and "wsl")    
- [WSL](https://docs.microsoft.com/de-de/windows/wsl/install-win10):: Windows Subsystem for Linux. What a great thing – finally use `makefile`s and other nifty Linux stuff. At the moment _Ubuntu_ on WSL1 is running for me well.
- [XAMPP](https://www.apachefriends.org/de/index.html): Run a local server. Nice for some web projects. However using VSCode with its remote server access was a relevation.
- [Cyberduck](https://cyberduck.io/) [🏁 only] – FTP client. Not great, not terrible. But all FTP clients on Windows are a dumpster fire. 🤷‍♂️  


### 📁 Productivity
- [Vuescan](https://www.hamrick.com/): Best scanning solution out there. Can be calibrated with an [IT8 target][it8]. I got mine from [Wolf Faust](http://www.targets.coloraid.de/). How the calibration is done can be read [here](https://www.photoinfos.com/Fotosoftware/Vuescan/vuescan-kalibrierung.htm). <a name="scan"></a>
- [Notion](https://www.notion.so/): Best notekeeping tool. Used as a small Wiki for me. Not fond of the way they abstracted the files away, tho. I also tried [_Roam_](https://roamresearch.com/) and liked the idea, but it's by far overpriced and I don't want my data lying around on their servers. (Also they lost a lot of those data, so I wouldn't trust them at all.) I tried using VSCode with plugins to achieve the same, but offline on my own device. Hasn't made the cut albeit.  
- [KeePass](https://keepass.info/) [🏁] / [KeePassXC](https://keepassxc.org/) [🍎] – Stores my passwords. Can be set-up to use on an own cloud for syncing.
- [Everything](https://www.voidtools.com/downloads/) [🏁 only] – Actually finds _everything_ on your PC AND on your networkshare; can be fed with RegEx, too!  
- [Bulk Rename Utility](https://www.bulkrenameutility.co.uk/) [🏁 only] – Great, vast powerful software (even tho the UI is a bit _cluttered_), but I use it less since the advent of PowerToys.  
- [PowerToys](https://github.com/microsoft/PowerToys) [🏁 only] – Filled with goodies! It does so much and boosted my productivity. Replaced many different utilities for me (color picker, window layout manager, image resizer (via context menu), keyboard manager, file renamer, PT Run (like Mac's Spotlight)) 
- [Quicklook](https://github.com/QL-Win/QuickLook) [🏁 only] – 
This gives Windows users the same quicklook feature as known from the Mac. (The only thing I'm missing in Win compared to Mac)  
- [Backblaze](https://secure.backblaze.com/r/02fga9)– <sup>$$$</sup> The easiest way to backup, and cheap compared to other solutions too. I like how once you've set it up you can just forget about it. I sleep better since I know every bit of data is secured and recoverable. 


### ✒ Design
- [DisplayCAL](https://displaycal.net/) – To calibrate your display, make dispay profiles, and autoload them. The profiles were done with an older [Color Munki Smile][Color Munki Smile][munki].
- [fstl](https://github.com/mkeeter/fstl) [🏁 / 🍎 only self-built] – [.stl file](http://en.wikipedia.org/wiki/STL_\(file_format\)) viewer.
- [Solvespace](http://solvespace.com/) – A parametric 2D/3D CAD. It has a constraint-based modeler and makes a lot of fun to play with.
- [Meshroom](https://alicevision.org/) [🏁+🐧, BUT needs CUDA!] – 
Photo to 3D model.  
- [Blender](https://www.blender.org/) – With plugins: 
	- [Import Rhino files](https://github.com/jesterKing/import_3dm)
	- [MRMO Halftone emulation](https://mrmotarius.itch.io/mrmo-halftone)
- [CloudCompare](https://www.danielgm.net/cc/) – 3D point cloud and mesh processing software.
- [Inkscape](https://inkscape.org/) – Create and edit vector images.


### 🛠 Utilities
- [Twinkle Tray](https://twinkletray.com/) [🏁 only] – Does one thing and does it well: Set the display brightness per monitor.
- [MysticThumbs](https://mysticcoder.net/mysticthumbs) [🏁 only] <sup>$$$</sup> – Get thumbnails for a lot of additional file formats on Windows, like `.psd` and `.ai`.
- [DisplayFusion Pro](https://www.displayfusion.com/) [🏁 only] <sup>$$$</sup> – Invaluable when dealing with multiple monitors. Great to have for the "Multi-taskbar with programs pinned on the right one"-thing alone.
- [CDBurnerXP](https://cdburnerxp.se/) [🏁 only] – Sometimes you still need to burn CDs...  
- [7-Zip](https://www.7-zip.org/download.html) – The best way to (un)zip.  
- [IrfanView](https://www.irfanview.de/) [🏁 only] – For the more esoteric image formats.  
- [MPC-HC](https://github.com/clsid2/mpc-hc) [🏁 only] – Best video player out there.  


### 🔊 Audio
- [Spotify](https://www.spotify.com/)
- [MediaMonkey](https://www.mediamonkey.com/) [🏁 only] – Neat way to organize and playback of your music collection.
- [Audacity](https://www.audacityteam.org/) – In the case I need to crop some mp3's, basically. Also you can do picture manipulation with it!
- [Caustic](https://singlecellsoftware.com/caustic) – Make some music!  
- [Exact Audio Copy](http://www.exactaudiocopy.de/) [🏁 only] – Rip those CDs.
- [CUE Splitter](http://www.medieval.it/cuesplitter-pc/menu-id-71.html) – Split single audio files into independent audio tracks.
- [LameXP](http://www.muldersoft.com/#lamexp) [🏁 only] – Audio encoder frontend for ffmpeg.  


## Other
- [WebMCam](https://github.com/michaelmob/WebMCam) [🏁 only] – Capture frames in real-time and save them as WebM.
- [OBS Studio](https://obsproject.com/de) – More sophisticated tool for screen capturing and streaming.
- [Handbrake](https://handbrake.fr/) – Popular video transcoder. Rips DVDs, too.
- [MediathekView](https://mediathekview.de/download/) – For downloading an viewing the "Öffentlich-Rechtlichen" in Germany. Putting my monthly 17,50 € to great use.


## 🛠 Hardware
- [Roccat](https://de.roccat.com/) Kone Aimo
- [Keychron](https://www.keychron.com/) K6 – with Gateron Browns
- Keychron K3 (ultra slim) – with Gateron Browns
- [Color Munki Smile][munki]
- [IT8 Target][it8] from Wolf Faust for color corrected scanning
- < tbc >




[it8]: https://en.wikipedia.org/wiki/IT8#/media/File:IT8_color_target_by_EGM_Laboratories.jpg "IT8 Target"

[munki]: https://www.amazon.de/gp/product/B0055MBQOW/ref=as_li_tl?ie=UTF8&tag=beckeluc-21&camp=1638&creative=6742&linkCode=as2&creativeASIN=B0055MBQOW&linkId=a091febdd6fbdecfe4f8c358589c024d "Color Munki Smile"
