# Neptune 1.0 (Convert-png-to-jpg_GUI)

This tool convert png file to jpg file not only change name but also file format completely.
And this will help you change jpg Data set files name to recongnize easily.

# HOW TO USE
First click Load button, and load png or jpg files to use Data set for DL.
And then write Target Name you want to change (e.g. hammer, 망치...)
Finally Press Start Button.

If you reset current configuration, press reset button.

Neptune's file name changing code is made similarly under this line.

And you can convert color image files(3 channels) to gray scale(1 channel) or rotate images.

# save format
./result/'targetName'_'i'.jpg

# Make exe
pyinstaller --noconsole --add-binary "jpgConverter.ui";"." --onefile "Neptune(jpgNameConverter).py"
