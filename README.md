# FlipperZero-HelloWorld
"Hello, World!" tutorial designed exclusively for Flipper Zero enthusiasts.

# Summary
This repository contains a simple "Hello, World!" program written in C that uses the Furi library to display a message on the screen. The program creates a graphical user interface (GUI) with a canvas and renders the text "Hello, World!" on it.

# Step 1
Clone this repository to your local machine:
` git clone https://github.com/nenomg/FlipperZero-HelloWorld.git `

# Step 2
You need to clone the firmware from the repository, for this case I'm using Rogue Master Firmware.
`git clone --recursive https://github.com/RogueMaster/flipperzero-firmware-wPlugins.git`

# Step 3
Paste the helloworld folder inside `./flipperzero-firmware-wPlugins/applications/external `

# Step 4
Compile the firmware using ` ./fbt updater_package ` inside ` ./flipperzero-firmware-wPlugins `, once it finishes you will see the following message:
![image](https://github.com/nenomg/FlipperZero-HelloWorld/assets/105873794/55c9eed0-958b-418e-96b4-5f29ec2fc287)

# Step 5
Paste the compiled firmware to the update directory inside the flipper zero
![image](https://github.com/nenomg/FlipperZero-HelloWorld/assets/105873794/154b8e85-1552-4a3d-a572-b723ba1815fd)
![image](https://github.com/nenomg/FlipperZero-HelloWorld/assets/105873794/543c9da9-dfb7-49df-896e-80914cf3e132)

# Step 6
Run the update from the flipper zero
![image](https://github.com/nenomg/FlipperZero-HelloWorld/assets/105873794/098427b0-a180-4f83-829c-c1785500d72c)
![image](https://github.com/nenomg/FlipperZero-HelloWorld/assets/105873794/820574d3-a4ed-4e6f-873d-ae37be77a0c4)

# Final Step
Go to the games folder and find hello world app, run it to see the results.
Note: You dont have to compile the firmware every time, just go to the build folder and paste the .fap into the flipper.
![image](https://github.com/nenomg/FlipperZero-HelloWorld/assets/105873794/41113b78-bde0-4fd8-a796-81e280d07362)
![image](https://github.com/nenomg/FlipperZero-HelloWorld/assets/105873794/d093ca93-2afc-4f6f-9510-bb54781eb4e2)




