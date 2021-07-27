# Dwarf-Fortress-Termux

Dwarf Fortress for termux android- first i like to thanks to user Zhymabek Roman
for his work to put exagear on android https://github.com/ZhymabekRoman
DF for android works for rooted and no rooted android users
Currently DF 0.47.05v2 with DF hack 0.47.05r2 are supported

Requirements
install:
https://play.google.com/store/apps/details?id=com.termux or newer F-droid version
https://play.google.com/store/apps/details?id=com.termux.widget or newer F-droid version
optional:
https://play.google.com/store/apps/details?id=x.org.server

DF works with termux in two different way -with graphical and sound output via xserver XSDLand
,or in native termux window.

Download
https://drive.google.com/file/d/1KxYY9uN1xWXz9bIvHZ0hG56xDGnUpSFy/view?usp=drivesdk

In termux type:

apt-get install proot

termux-setup-storage
#accept all requirements

am start -a android.intent.action.VIEW -d "content://com.android.externalstorage.documents/root/primary"
#copy df.tgz to termux folder via native android file manager

#unpack archive with command
tar -zxf df.tgz --recursive-unlink --preserve-permissions

on your phone launcher create termuz widget and launch df txt or df graphics
(if you want sound or sound and graphics launch xserver xsdl app, when you see blue screen minimize app and launch termux
widget then wait a moment, and return to xsdl app.)




