# Raspberry Pi Airplay Bash Script

## Setup:

1. Create a directory called `Dev` inside Home directory
2. When prompted, clone into the directory above
3. Follow install instructions here: https://github.com/FD-/RPiPlay

## Instructions

1. Add the `airplay.sh` file on the desktop, this is the shortcut
2. In terminal, run `chmod +x airplay.sh` to make the file executable
3. Double click the script to run, choose "Execute in Terminal"
4. When done press `Control + C` to stop the AirPlay server

> NOTE: sometimes the AirPlay server will refuse to stop - this is a known bug. Try `sudo reboot`. If that doesn't work, do a hard shutdown.
