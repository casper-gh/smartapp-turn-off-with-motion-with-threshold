# smartapp-turn-off-with-motion-with-threshold

This is an enhanced version of `smartapp-turn-off-with-motion` from https://github.com/KristopherKubicki.

Now users can specify how many alerts before execute the old workflow (Turn off motion_detect/lights/switches and turn on after wait time)

***Parameters explained:***
  - `motions`   : motion detector device
  - `minutes1`  : Time delay from when switch is turned off and then turned on again
  - `switches`  : The switch you want to trigger
  - `alertThreshold`  : Alert threshold before triggering "turn off with motion"
  - `waitSeconds` : Alert threshold timeout. For example: If threshold is reached within timeout, app is trigger, if there are multiple alerts but not within timeout, alert count is reset. 

Derived from:
---
https://github.com/KristopherKubicki/smartapp-turn-off-with-motion
