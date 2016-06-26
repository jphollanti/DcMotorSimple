# Simple Arduino DC motor

# Notes for PlatformIO:

install with: sudo python -c "$(curl -fsSL https://raw.githubusercontent.com/platformio/platformio/master/scripts/get-platformio.py)"

build: pio run

upload: pio run -t upload

clean: pio run -t clean

serial monitor: platformio serialports monitor

picks up the ports etc from ini file (i guess)

external libraries are put in: .pioenvs/due/

see more: http://docs.platformio.org/en/latest/userguide/cmd_serialports.html#platformio-serialports-monitor

# Notes for Atom

PlatformIO works nicely with Atom. Install platformio-ide: apm install platformio-ide

apm is Atom Package Manager

more about installing platformio-ide: http://docs.platformio.org/en/latest/ide/atom.html
more about installing Atoms plugins in general: http://joshbranchaud.com/blog/2014/02/27/Installing-Packages-In-Atom-Editor.html

## PlatformIO IDE Settings

After installing platformio-ide Atom plugin you can see PlatformIO menu item. Under settings you can customize different things. In particular it would be good to customize the CLI options (buffer size etc.). Also, it's probably worth it to enable automatic build whenever a file is saved.

## Install git-plus

It's also good to install git-plus. You can do it for example via Atom Settings > install and search for git-plus.
