README for power-profiles-daemon-scripts

Small scripts to take advantage of power-profiles-daemon on linux computers, meant to be run on power-related events such as plugging or unplugging the laptop charger.


Make them executable by
`cd power-profiles-daemon-scripts`
`sudo chmod 555 *e.sh`

To use automatically in KDE Plasma:
1. go to power saving settings
2. set the power-save.sh script to execute when battery power is detected
3. set the performance.sh script to execute when charging is detected
