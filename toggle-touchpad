#!/bin/bash
# Small script to enable/disable the touchpad
# Source https://askubuntu.com/questions/537002/how-to-quickly-enable-disable-touchpad-in-xubuntu-14-04-without-installing-other

if synclient | grep --quiet 'TouchpadOff             = 0'; then
  synclient TouchpadOff=1
  notify-send Touchpad Disabled
else
  synclient TouchpadOff=0
  notify-send Touchpad Enabled
fi
