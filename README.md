# XuiONE
Update 1.5.13 Released

[CRITICAL] Patched an exploit in the System API that could allow for remote read and write if leveraged correctly.
[Core] Reverted EPG system to previous MySQL based system to fix a bug where EPG wasn't being retained.
[Core] Fixed EPG API calls and images

New Install:
https://update.xui.one/XUI_1.5.13.zip

Upgrade:
https://update.xui.one/XUI_1.5.13_UPDATE.zip

When you've installed this, update your load balancers from the Servers page. Once all load balancers are updated or reinstalled, click the red Lock icon in the top right and then select Regenerate Security Key. This will increase security and ensure nobody can replicate your streaming key and do anything malicious.

cd /tmp ; wget https://update.xui.one/XUI_1.5.13_UPDATE.zip
apt-get install unzip
unzip XUI_1.5.13_UPDATE.zip
./update
