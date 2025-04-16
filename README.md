# Stargazer Tool
A simple tool, to help extract, track, and format data for the 'Star Caller' bot on the [Star Find](https://starfind.net/) Discord Server.
From the [telescope](https://runescape.wiki/w/Telescopes) [dialog box](https://runescape.wiki/w/Transcript:Portable_telescope) to the format the bot requires.
 
From: 
> `39; You see a shooting star! The star looks like it will land in
> Kandarin in the next 34 to 58 minutes. The star looks to be big.`

To:
> `/call world: 39 region: Kandarin size: Big relative-time: 34`

## Setup and prerequisites
### Latest release
Go to the latest [releases page][github-release-link] and click on `Assets` at the bottom to show the files available in the release.
Simply download and open the `.html` file in your web browser.

<!-- item that may need to be updated release to release -->
[github-release-link]:https://github.com/infrequent/stargazer-tool/releases/latest

### Text Extraction utilities
- **Windows:**
  - Microsoft PowerToys for inbuilt text-extractor: [https://learn.microsoft.com/en-us/windows/powertoys/](https://learn.microsoft.com/en-us/windows/powertoys/)
  - Joe Finney's Text Grab: [https://github.com/TheJoeFin/Text-Grab](https://github.com/TheJoeFin/Text-Grab)

- **Untested options for macOS:**
  - TRex for macOS? [https://github.com/amebalabs/TRex](https://github.com/amebalabs/TRex)
  - Text Sniper? [https://github.com/TheJoeFin/Text-Grab?tab=readme-ov-file#pssst-on-a-mac](https://github.com/TheJoeFin/Text-Grab?tab=readme-ov-file#pssst-on-a-mac)

**Disclaimer:**
I cannot vouch for any of these utilities, 
I have personally used Microsoft PowerToys, as a nice minimalist text extractor, and tested Joe Finney's Text Grab, which is what the PowerToys module is based on, it is more featured. (Has an option to 'Copy Last Region Selection'.)
For macOS I have **NOT** used or tested TRex or Text Sniper, they are options that looked promising.

## License
Stargazer Tool is licensed under the [MIT license.](https://github.com/infrequent/stargazer-tool/blob/master/LICENSE)
