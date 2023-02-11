
***

<div align="center">
   <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/>
  <H1>Bliss Browser OSMode</H1>
  <p>🌳️🌐️💻️ The OS mode for Bliss Browser lets you turn your computer into a netbook for as much time as you choose. A privacy-focused alternative to ChromeOS/ChromiumOS</p>
</div>

***

## Intro

OS Mode for Bliss Browser is a framework for the browser that turns the interface into a graphical shell similar to FirefoxOS, ChromeOS, and other netbook operating systems. **The OSMode shell is not an operating system**, it runs on top of one. It is designed to make a computer into a Netbook, until the user decides to disable it (via Bliss Browser settings) and have it just be a browser application within their operating system once more.

### Netbook definition

I may be outspoken here, but I believe that Netbook is still the relevant term for a computer that only runs a web browser.

### Similar projects

> **Note** This list is in A-Z order. Also, these projects are listed because they have similar aspects to Bliss Browser OSMode, but are mostly completely different in design.

- ChromeOS/ChromiumOS - A netbook operating system that is mainly a web browser operating system, although with a very bad privacy record
- FirefoxOS - A discontinued privacy friendly netbook operating system that was replaced by Google ChromeOS/Google ChromiumOS
- Windows 1.x, 2.x, 3.x, and 3.1x (Windows 1.0 - Windows 3.11) - a graphical shell that ran on top of MS-DOS
- Windows 9x (Windows 95, 98, ME) - a graphical shell that ran on top of MS-DOS

***

## Challenges

### Mobile variants

On 2023, Tuesday, February 7th, I began to deal with a new problem in the design of the browser: I have designed it for desktops, and I never considered making a mobile variant. I am trying to figure out how the browser will have to be changed to get it to run on mobile operating systems. It is also an interesting idea to have a netPDA/netPhone, opposed to a NetBook.

### iOS/iPadOS engine problem

Due to Apple Incs rule on using third party engines in iOS/iPadOS, the iOS/iPadOS versions of the browser will be severely limited, as the project will be forced to use WebKit for these variants, opposed to other engines. Maybe a rooted variant can support other engines?

***

## OS ports

OSMode repositories aren't just for turning the browser into a net operating system, they also contain fine-tuned tools and libraries required to port the browser to different operating systems. The tuned tools will work alongside the Bliss Browser core. The core will interpret the changes for each operating system and its port.

***

## Questions and answers

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

1. Question 1

**Q:** Will Bliss Browser ever support ChromeOS/ChromiumOS?

**A:** No, there is no point. If a user wants a netbook operating system other than ChromeOS, they can switch over. It isn't feasible to port the browser to this platform for many reasons.

2. Question 2

**Q:** What is Meadows Linux and WacOS, and why have I never heard of them before?

**A:** [:octocat: Meadows](https://github.com/seanpm2001/qMeadows/) and [:octocat: WacOS](https://github.com/seanpm2001/WacOS/) are operating systems by [:octocat: @seanpm2001](https://github.com/seanpm2001/) that are currently under development. As of 2023, Friday, February 10th, neither of them are functional, but support for them is planned. They are currently obscure, and don't have their own Wikipedia pages, as they aren't notable enough yet. WacOS is an Apple replacement, Meadows is a Quantum Computer operating system that is my dream operating system, being developed since 2013. The Meadows operating system is part of the same software family that the Bliss Browser is part of.

3. Question 3

**Q:** Why is Windows XP still supported?

**A:** Windows XP is supported out of tradition. The Meadows project that this project is part of took heavy inspiration from my past experience with Windows XP. The Windows XP edition is heavily modified, and is only recommended for use in a virtual machine, or an old computer you are willing to format if something goes wrong.

4. Question 4

**Q:** Why C? Why Python? Why other languages?

**A:** One of the goals in Bliss Browser development is for maximum portability with minimum dependencies. Since most systems support C, C is one of the languages the browser is written in. When a system comes with Python pre-installed, and has good Python support, Python is used as a backup language, as the project is supposed to be written in Python as a majority language. For other languages, it depends on what is pre-installed. Windows Vista and onward are written in C# due to that language being supported (also software diversity) the Android port is written in Java, due to the prevalance of Java in Android development, and and so on.

**List is incomplete**

5. Question 5 (obsolete, as of 2023, Friday, February 10th)

**Q:** The images appear stretched. Are you aware of this?

**A:** Yes. I was aware. When preparing and writing this Q&A, I decided to fix it. There were no excuses left for not doing so.

6. Question 6

**Q:** Why are you using old logos?

**A:** Some older logos look better to me than the newer ones, and are more recognizable. I also strongly favor skeuomorphism or gradient over flat design

7. Question 7

**Q:** Why do none of these projects work?

**A:** As of 2023, Friday, February 10th, all Bliss Browser projects are in the Pre-Alpha stage, and are currently being planned. Development hasn't fully began yet, it hasn't even reached the Alpha stage yet.

8. Question 8

**Q:** Some images have white boxes around them. Are you aware of this?

**A:** Yes I am. I am hoping to replace all non-transparent images with tranparent versions, but it is a slow process, as I have a small community, and I am dedicating this as an up-for-grabs community goal. You can open a pull request if you have the necessary files to fix one or more images. Please make sure to give the files an appropriate name, and follow the file structure rules if you are to do this.

</details>

***

## Variants

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

> **Note** Links marked with the :octocat: Emoji are indicators that the links are to GitHub-based repositories.

<!-- > **Note** For developers: Keep each table row limited to 4 entries. !-->

### Linux

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

Special Linux builds of Bliss Browser OSMode are available for:

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

<table>
  <!-- Row 1 !-->
  <!-- Linux !-->
  <tr>
     <td align="center"><p>Linux (row 1)</p></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_Debian-Shell/"><img src="/Graphics/Linux/D/Debian/SVG/Debian_Logo.svg" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Debian</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_Fedora-Shell/"><img src="/Graphics/Linux/F/Fedora/SVG/Fedora_logo.svg" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Fedora</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_RedHat-Shell/"><img src="/Graphics/Linux/R/RedHat/SVG/Red_Fedora.svg"/" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Red Hat</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_Ubuntu-Shell/"><img src="/Graphics/Linux/U/Ubuntu/PNG/Ubuntu-Legacy-logo.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Ubuntu</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode-Arch-Shell/"><img src="/Graphics/Linux/A/Arch-Linux/PNG/Arch-linux-logo.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Arch Linux</b></sub></a></td>
  </tr>
  <tr>
     <td align="center"><p>Linux (row 2)</p></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_Gentoo-Shell/"><img src="/Graphics/Linux/G/Gentoo-Linux/PNG/gentoo-3d-Logo.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Gentoo</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode-LFS-Shell/"><img src="/Graphics/Linux/L/Linux-From-Scratch/PNG/Linux-From-Scratch_LQ_Logo.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Linux From Scratch (LFS)</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode-Meadows-Shell/"><img src="/Graphics/Linux/M/Meadows/JPEG/Meadows_LowRes_PlaceholderLogo.jpeg" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Meadows</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_Raspberry-Pi-OS-Shell/"><img src="/Graphics/Linux/R/Raspberry-Pi-OS/PNG/RPI_Logo_400px.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Raspberry Pi OS</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_NixOS_Shell/"><img src="/Graphics/Linux/N/NixOS/PNG/NixOS_Logo1.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for NixOS</b></sub></a></td>
  </tr>
  <tr>
     <td align="center"><p>Linux (row 3)</p></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_WacOS_Shell/"><img src="/Graphics/Linux/W/WacOS/PNG/MacOSIcon.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for WacOS</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_Android_Shell/"><img src="/Graphics/Linux/A/Android/SVG/Android_logo_2019_(stacked).svg" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Android</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_FireOS_Shell/"><img src="/Graphics/Linux/F/FireOS/PNG/Amazon-Fire-Logo.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for FireOS</b></sub></a></td>
    <td align="center"><a href="https://example.com"><img src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="100px;" alt=""/><br /><sub><b>Coming soon</b></sub></a></td>
    <td align="center"><a href="https://example.com"><img src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="100px;" alt=""/><br /><sub><b>Coming soon</b></sub></a></td>
  </tr>
</table>

</details>

> **Note** Add to list: Kubuntu, Lubuntu, Xubuntu, ~~Gentoo~~, Manjaro, ~~Arch,~~ Alpine, Puppy, ~~Raspberry Pi OS~~, RaspbianOS, OpenSUSE, ElementaryOS, etc.

</details>

### *Nix

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

Special builds for other UNIX-like operating systems with Bliss Browser OSMode are available for:

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

<table>
  <!-- Row 1 !-->
  <!-- *Nix !-->
  <tr>
     <td align="center"><p>*Nix (row 1)</p></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_POSIX-Shell/"><img src="/Graphics/-Nix/P/POSIX/JPEG/POSIX-3799444896.jpeg" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for POSIX-compliant systems</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode-DragonflyBSD-Shell/"><img src="/Graphics/BSD/DragonFly/PNG/105_dragonfly-bsd-icon.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for DragonFly BSD</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_MacOS_Shell/"><img src="/Graphics/-Nix/M/MacOS/PNG/MacOS_Logo1.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for MacOS (10.10 and up)</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_iOS_Shell/"><img src="/Graphics/-Nix/I/iOS/PNG/iOS_Logo2.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for iOS</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_iPadOS_Shell/"><img src="/Graphics/-Nix/I/iPadOS/PNG/iPadOS_Logo_LQ.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for iPadOS</b></sub></a></td>
  </tr>
</table>

</details>

> **Note** Add to list: ~~MacOS 10.10 and newer~~, FreeBSD, OpenBSD, NetBSD, etc.

</details>

### Other

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

Special builds for other operating systems with Bliss Browser OSMode are available for:

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

<table>
  <!-- Row 1 !-->
  <!-- OtherOS !-->
  <tr>
     <td align="center"><p>OtherOS (row 1)</p></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_Windows-XP_Shell/"><img src="/Graphics/Other/Windows-XP/PNG/Windows-XP_WordmarkLogo.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Windows XP</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode-Windows-NT-Shell/"><img src="/Graphics/Other/Windows-NT/PNG/Windows_NT_5.1_Logo_XP.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Windows NT (5.1 and up)</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_Windows-10_Shell/"><img src="/Graphics/Other/Windows-10/PNG/Windows-10-logo_Square.png" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Windows 10</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_Windows-11_Shell/"><img src="/Graphics/Other/Windows-11/JPEG/Windows-11-Logo_Square.jpeg" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for Windows 11</b></sub></a></td>
    <td align="center"><a href="https://github.com/seanpm2001/Bliss_Browser_OSMode_ReactOS_Shell/"><img src="/Graphics/Other/ReactOS/JPEG/ReactOS_Logo_800px_Opaque.jpeg" width="100px;" alt=""/><br /><sub><b>:octocat: Bliss Browser OSMode for ReactOS</b></sub></a></td>
  </tr>
</table>

</details>

> **Note** Add to list: ~~Windows XP, Windows 10, Windows 11 and newer~~ , ~~ReactOS~~, etc.

</details>

</details>

</details>

</details>

</details>

***

### File info

<details open><summary><p lang="en"><b><u>Click/tap here to expand/collapse this section</u></b></p></summary>

**File type:** `Markdown (*.md *.mkd *.mdown *.markdown)`

**File version:** `8 (2023, Friday, February 10th at 6:14 pm PST)`

**Line count (including blank lines and compiler line):** `411`

**Current article language:** `English (EN_USA)` / `Markdown (CommonMark)` / `HTML5 (HyperText Markup Language 5.3)`

**Encoding:** `UTF-8 (Emoji 12.0 or higher recommended)`

**All times are UTC-7 (PDT/Pacific Time)** `(Please also account for DST (Daylight Savings Time) for older/newer entries up until it is abolished/no longer followed)`

> **Note** _On 2022, Sunday, March 13th at 2:00 am PST, the time jumped ahead 1 hour to 3:00 am._

> **Note** **You may need special rendering support for the `<details>` HTML tag being used in this document**

***

<details><summary><p><b>Click/tap here to expand/collapse the file history for this file</b></p></summary>

<details><summary><p><b>Version 1 (2023, Friday, January 27th at 4:25 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Started the file
- [x] Added the title section
- - [x] Added the browser logo
- - [x] Added a centered description
- [x] Added the `Intro` section
- - [x] Added the `NetBook definition` subsection
- - [x] Added the `Similar projects` subsection
- - [x] Added the `Variants` section
- - - [x] Added the `Linux` subsection
- - - [x] Added the `*Nix` subsection
- - - [x] Added the `Other` subsection
- [x] Added the file version stamp
- [ ] No other changes in version 1

</details>

<details><summary><p><b>Version 2 (2023, Thursday, February 2nd at 11:05 pm PST)</b></p></summary>

- [x] ...
- - [x] Updated the `Variants` section
- - - [x] Updated the `Linux` subsection
- - - [x] Updated the `*Nix` subsection
- - - [x] Updated the `Other` subsection
- [x] Updated the file version stamp
- [ ] No other changes in version 2

</details>

<details><summary><p><b>Version 3 (2023, Monday, February 6th at 4:27 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Updated the `Variants` section
- - [x] Updated the `*Nix` subsection, adding in MacOS
- [x] Removed the file version stamp in place of a file info section
- [x] Added the `file info` section
- - [x] Added the version number
- - [x] Added the version date
- - [x] Added the line count
- [x] Added the `file history` section
- - [x] Added an entry for version 1
- - [x] Added an entry for version 2
- - [x] Added an entry for version 3
- [x] Added the footer 
- [ ] No other changes in version 3

</details>

<details><summary><p><b>Version 4 (2023, Monday, February 6th at 4:30 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Minor fix: added a missing `</details>` tag to the `file history` section
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 4
- [ ] No other changes in version 4

</details>

<details><summary><p><b>Version 5 (2023, Tuesday, February 7th at 6:06 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- ...
- - [x] Updated the `*Nix` subsection, adding in iOS and iPadOS
- [x] Added the `Challenges` section
- - [x] Added the `Mobile variants` subsection
- - [x] Added the `iOS/iPadOS engine problem` subsection
- [x] Added the `OSPorts` section
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 5
- [ ] No other changes in version 5

</details>

<details><summary><p><b>Version 6 (2023, Wednesday, February 8th at 3:36 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- ...
- - [x] Updated the `Linux` subsection, adding in NixOS and WacOS
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 6
- [ ] No other changes in version 6

</details>

<details><summary><p><b>Version 7 (2023, Thursday, February 9th at 1:50 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Added the `Questions and answers` section
- ...
- - [x] Updated the `Linux` subsection, adding in Android and FireOS
- - [x] Updated the `OtherOS` subsection, adding in Windows 10 and Windows 11
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 7
- [ ] No other changes in version 7

</details>

<details><summary><p><b>Version 8 (2023, Friday, February 10th at 6:14 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Updated the `Questions and answers` section, adding 7 questions, and converting the list into a dropdown section
- ...
- - [x] Updated the `Linux` subsection, reformatting the table, and switching from 4 to 5 columns per row, converted to dropdown
- - [x] Updated the `*Nix` subsection, reformatting the table, and switching from 4 to 5 columns per row converted to dropdown
- - [x] Updated the `OtherOS` subsection, reformatting the table, switching from 4 to 5 columns per row, and adding support for Windows XP and ReactOS converted to dropdown
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 8
- [ ] No other changes in version 8

</details>

</details>

***

<!-- TEMPLATE

| <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> | <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> | <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> | <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> |
|---|---|---|---|
| Coming soon | Coming soon | Coming soon | Coming soon |

!-->
