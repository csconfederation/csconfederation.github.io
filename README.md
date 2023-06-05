### CSC Signature Generator
- Modified from [Source Code](https://github.com/DrKain/csgo-sticker-signature-generator) for CSC

### Preview
  
![1](https://i.imgur.com/tauslP6.gif)

### How to update teams

Open assets/csc/csc.xcf in Gimp or equivalent.  Make all the team logos invisible if needed, then add layer of a new team (should be transparent png).  Scale layer to 400x400 or whatever looks good.  Export as png.  Repeat as needed.  Commit and push to assets/csc/<short team name>.png

Open js/script.js and add short team names to L39 Generator.events CSC array
