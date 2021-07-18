# php7-arm7
Downgrade PHP cli on termux in device arm7

This repo can help you to downgrade php 8 to php 7 on termux in device armv7
<br>
Make sure your device is armv7 by typing<br>
<b>uname -m</b>
# Usage
git clone https://github.com/dbgid/php7-arm7<br>
apt install p7zip<br>
cd php7-arm7<br>
7z e php7-arm7.7z<br>
cd php7-arm7<br>
sh php7.sh<br>
or you can download release file below and extract to your internal storage<br>
then open termux and fill command below<br>
cd /sdcard/php7-arm7<br>
sh php7.sh
# Credits
Termux-pod (https://github.com/Termux-pod)
