# DeckOfSixty
A simple console application for performing RP astrologian readings in FF14

## Requirements
You may have to install the .net core runtime in order for this app to work. To do so, simply go here: [install it](https://dotnet.microsoft.com/download/dotnet-core/thank-you/runtime-desktop-3.1.10-windows-x64-installer)

## Using the app
1. Click the Code button at the top right corner of this window
1. Click "Download Zip"
1. Extract to a folder wherever you want it to go
1. Run the .exe

That's it!

## Making Your Own Spreads
If you want more options for spreads (I only did the ones found in the Encyclopedia Eorzea book) you can add your own just by adding a json file.

Here's an example that you can copy:
`
{
  "Name": "Sample Name"
  "Places": [{
    Meaning: "This is the first place"
  },{
    Meaning: "This is the second place"
  }]
}
`
Please note where the brackets and quotes are!

You can place your new spread in the /Records/Spreads folder and it will be picked up automatically by the app.

## Modifying Card Definitions
You can change what certain cards mean (or even add your own!) by changing their respective JSON files under the Records folder
MajorArcana.json : The named cards, such as the Bole and the Ewer
MinorArcana.json : The NUMBERS associated with the minor arcana cards
Suits.json : The minor arcana suits

Minor arcana definitions are created by combining what's in the MinorArcana.json file with what's in the Suits.json file.
