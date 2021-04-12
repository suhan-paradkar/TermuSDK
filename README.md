# TermuSDK
Android SDK with aapt2.. made 4 termux
Currently supports aarch64 devices only...
## Installation
Run the install script provided in the source code... it will automatically download from the releases section and install it
```
./install.sh
```
## Build locally
Copy the following into termux..
```
pkg update && pkg upgrade
pkg install git termux-create-package 
git clone https://github.com/suhan-paradkar/TermuSDK
cd TermuSDK/
termux-create-package manifest.json
```
