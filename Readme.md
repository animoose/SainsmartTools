# Sainsmart Tools Library For Carbide Create

Carbide Create comes with a library of tool settings for Shapeoko and Nomad CNCs. You can add new tools from a CSV file. This project contains a file for the tools sold by Sainsmart for their 3018 CNC.

I have not done very much testing on these. The feedrate and depth of cut settings seem to work OK for MDF. For acrylic, halving the speed might work better.

Tested so far: SF17; C08 1.0, 2.0, 2.4 and 3.0mm.

## Installation

* Find the Carbide Create tools directory from Help > About > Open data directory, then drill down until you find the tools directory. On Windows, it will be something like c:\User\\*username*\AppData\Local\Carbide 3D\Carbide Create\tools.

* Exit Carbide Create.

* Copy the CSV file to the Carbide Create tools directory.

* Restart Carbide Create. You should now see *Davids-Sainsmart-MDF* in the tools database. 

## Notes

* Cut length and number of flutes are not used for anything. See [this forum post](https://community.carbide3d.com/t/adding-tool-to-library-flutes-and-cutting-length/19066/6).

* All of the entries use metrics settings.

* The 3D settings are a complete guess.

* The CSV contains links to the Sainsmart product pages, but they don't show up in Carbide Create.
