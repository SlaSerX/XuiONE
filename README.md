# XuiONE
Update 1.5.13 Released

[CRITICAL] Patched an exploit in the System API that could allow for remote read and write if leveraged correctly.</br>
[Core] Reverted EPG system to previous MySQL based system to fix a bug where EPG wasn't being retained.</br>
[Core] Fixed EPG API calls and images</br>

New Install:</br>
https://update.xui.one/XUI_1.5.13.zip

Upgrade:</br>
https://update.xui.one/XUI_1.5.13_UPDATE.zip</br>

When you've installed this, update your load balancers from the Servers page. Once all load balancers are updated or reinstalled, click the red Lock icon in the top right and then select Regenerate Security Key. This will increase security and ensure nobody can replicate your streaming key and do anything malicious.</br>

cd /tmp ; wget https://update.xui.one/XUI_1.5.13_UPDATE.zip</br>
apt-get install unzip</br>
unzip XUI_1.5.13_UPDATE.zip</br>
./update</br>

Update for Proxy:</br>
Download proxy.tar.gz here:</br>
https://update.xui.one/proxy.tar.gz</br>

And overwrite the version in:</br>
/home/xui/bin/install/
