@@ -2,8 +2,8 @@

#In case of Older OS use this commans (export LC_ALL=C)

#In case pid does not work
sudo apt-get remove --purge python-pip <br>
#In case pid does not work<br>
sudo apt-get remove --purge python-pip<br>
sudo apt-get autoremove<br>
sudo rm -f /usr/local/bin/pip<br>
sudo easy_install pip==20.3.4<br>
