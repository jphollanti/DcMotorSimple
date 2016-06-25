# Simple Arduino DC motor

# Notes for platform io: 

install with: sudo python -c "$(curl -fsSL https://raw.githubusercontent.com/platformio/platformio/master/scripts/get-platformio.py)"

build: platformio run

upload: platformio run -t upload

clean: platformio run -t clean

serial monitor: platformio serialports monitor 

picks up the ports etc from ini file (i guess)

external libraries are put in: .pioenvs/due/
see more: http://docs.platformio.org/en/latest/userguide/cmd_serialports.html#platformio-serialports-monitor
