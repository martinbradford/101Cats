
# 101Cats

This is the distribution point for 101Cats deliverables. It will typically contain a zip file called "setup.zip" and one or more documents giving installation instructions and release notes.
No source code is included here. The source code is stored in a private GitHub repository which is made available to interested parties subject to some rules. Ping me a message if you want access.

**101Cats** is a CAT control program written specifically for the Yaesu FTdx101 series of radios. These are complex radios with many functions and controls. The author had been a long-time user of other CAT programs including HRD and Win4Yaesu - both very competent pieces of software - but when I upgraded to the FTdx101D, I came to the conclusion that there was no generic CAT application that could really do it justice, so I started to write my own. That has developed into 101Cats.


**A Wiki is slowly under construction - follow this [link](https://github.com/martinbradford/101Cats/wiki) for access. At the moment, edit access to the wiki is limited to registered collaborators - if you are willing and able to contribute, ping me a message to ask to be added to the collaborators list.  Use this [link](mailto:one.oh.onecats@outlook.com) to address me.**

Please note that this software is distributed free of charge and with absolutely no guarantee at all. I developed it for my own use and there are a number of active users. I do try to fix bugs though I accept no commitment to do so. If you find a bug or have a suggestion for an improvement, please raise an [issue](https://github.com/martinbradford/101Cats/issues) or start a [discussion thread](https://github.com/martinbradford/101Cats/discussions). 

**While I don't ask for any payment, assistance will be very welcome! The most obvious way you can help is to contribute to the doumentation... 101Cats has become a large and complex application and a detailed instruction manual will be a significant task. If you are using it and have gained experience in configuring or operating it, please consider contributing towards the Wiki! At the moment, it is not publically editable because I want to retain some degree of control over it but if you feel able to contribute to it, please ping me a message [at this link](mailto:one.oh.onecats@outlook.com) and I'll add you to the collaborators list. Help with the coding would also be welcome - though, obviously, that requires some fairly advanced programming skills.**

# Hold Off!!! My latest update seems to have done some serious damage to some installations! I am investigating and will issue a fix later today...

The installation image for the latest version (1.0.9.10) of the application can be obtained via the following [link](https://github.com/martinbradford/101Cats/raw/refs/heads/main/setup%201.0.9.10.zip). Earlier releases can be downloaded directly from GitHub [here](https://github.com/martinbradford/101Cats).

Version 1.0.9.10 fixes a bug in the XSD validation of the config file

Version 1.0.9.9 fixes several bugs and introduces some new features:

- Frequencies can be entered through the keyboard. If the Keypad dialogue is displayed, then pressing any numeric key, the period key, the backspace key or the enter key has the same effect as clicking the corresponding button. If the Keypad dialogue box is not open, then pressing any numeric key while the main window has focus will open the Keypad dialogue box and enter the corresponding digit.
- The configuration dialogue box has been tidied up. The number of controls had grown beyond what could reasonably be displayed on a single screen, so it has now been converted into a tabbed format. New tabs will be added over time to cover further configuration options.
- The Modulation Sources dialogue box is now fully live. It is opened with the "Modulation Sources" button in the lower pane.

**In an effort to be a bit more professional, I'm trying to keep some release notes running - [check here for them](https://github.com/martinbradford/101Cats/blob/main/docs/ReleaseNotes.md)**

**Coming Next**
I still have several additional featured planned as a result of suggestions and requests from users. The DXCluster window will be a focus in the coming days - it is useful, but quite limited at the moment. Remembering the antenna selection by band is also on the plan. Another focus is going to be integration with the Elgato Stream Deck. These devices have interested me for a while, but I've been too mean to buy one... Elgato are running a promotion right now and I was able to get a top-of-the-range Stream Deck XL at £40 off, so I gave it a try - and it is very impresive. I've started getting it set up to simplify the operation of the shack. I still have a long way to go, but the exercise has highlighted several enhancements to 101Cats that will make it a lot easier.


**Click [here](https://www.101cats.co.uk/Diversity%20Reception%20with%20an%20RSPDuo%20and%20FTdx101D.pdf) for my notes on configuring diversity reception with an FTdx101 and an SDRPlay RSPDuo.**

# 991Cats and other radios

There is a very early version of 991Cats [here](https://github.com/martinbradford/FT991Cats/releases/download/V0.0.0.0/991CatsSetup1.zip) - it is still very rough, but you are welcome to experiment if you are brave enough!

Several people have asked if 101Cats will support other (Yaesu) radios. The answer is a highly qualified yes... The Yaesu CAT command set has stayed broadly the same for many years - they just add more commands as the radios become more complex. The FTdx101 series are currently the most complex Yaesu production models and 101Cats is designed to drive them fully. If you point 101Cats at an FTdx10, an FT-710 (or, even, an FT-991A), then it will attempt to control them. It will succeed for those functions that the target radio shares with the FTdx101D and should not actually error for the rest. As I said above, the source code is available subject to a few simple conditions and I would love to see other versions developed. If you have an FTdx10 or FT-710 and enough experience with C# and Visual Studio, please contact me on the link above and I'll assist you in the development of a targeted version.

