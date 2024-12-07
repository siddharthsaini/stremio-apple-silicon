# stremio-apple-silicon
compiled app from stremio-shell source code for apple silicon for native performance, the official app requires rosetta which isn't battery eficient and lacks the performance

steps to get this running:
1. run `xcode-select --install`
2. install homebrew with either command line or pkg file -> `visit brew.sh`
3. after installing homebrew run -> `eval "$(/opt/homebrew/bin/brew shellenv)"` to add `brew` to path
4. run `brew install mpv node qt@5 ffmpeg openssl@3` this installs the required dependencies since the packages are not bumndled with the stremio.dmg as of now (WIP)
5. install `Stremio 4.4.168.dmg`
