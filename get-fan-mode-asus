#!/bin/bash
 mod=$(cat  /sys/devices/platform/asus-nb-wmi/throttle_thermal_policy)
 if [[ $mod = 0 ]]; then
  echo "default mode"
elif [[ $mod = 1 ]]; then
  echo "overboost mode"
  elif [[ $mod = 2 ]]; then
  echo "silent mode"
fi
