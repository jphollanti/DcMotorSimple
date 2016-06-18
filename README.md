# Simple Arduino DC motor

# Notes for platform io: 

build: platformio run
upload: platformio run -t upload
clean: platformio run -t clean

serial monitor: platformio serialports monitor 
picks up the ports etc from ini file (i guess)
http://docs.platformio.org/en/latest/userguide/cmd_serialports.html#platformio-serialports-monitor
