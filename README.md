# Sublime Text Editor Setup for Competitive Programming

## For Mac and Linux Users

- Download `Sublime Text Editor` [link](https://www.sublimetext.com/download)
- Create 3 files called `input.txt`, `output.txt` and `mms.cpp` in the same directory as your source code file.
- Open this directory in Sublime Text Editor.
- Go to `View` --> `Layout` --> `Columns: 3`
- Go to `View` --> `Groups` --> `Max Columns: 2`
- Open `mms.cpp` in the left column and `input.txt` and `output.txt` in the right column.
- Open system terminal and run `sudo apt install nautilus-admin` to install nautilus-admin.
- Go to `File System` --> `usr/local/include`. Right click and select `Open as Root`.
- Again go to the same directory `usr/local/include` and create a folder inside it called `bits` and inside it create a file called `stdc++.h`.
- Copy paste the contents of [this file](./bits/stdc++.h) in `stdc++.h` and save it.
- Go to `.config/sublime-text-3/Packages/User` and copy paste those [3 files] in this directory.
- Go to `Tools` --> `Build System` and select `C++14`.
- Now you can compile and run your code using `Ctrl + B`.
