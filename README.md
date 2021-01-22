# meari-camera-cli
Resources about how to interact with meari based cameras

There're plenty of chinese battery cameras on the market, with different brands, who make use of the mobile app CloudEdge to work. 
According to the Android App, it seems that the software is developed by Mearitek https://www.meari.com/products/
The camera's firmware has the setup url coded into it, because in order to configure it, the app generates a QR code that contains the wifi network name, password, and some kind of token associated to the user account.

Urls:
- https://www.reddit.com/r/hacking/comments/dhqlbb/help_me_hack_my_web_cameras/
- Firmware https://github.com/AMoo-Miki/homebridge-tuya-lan/issues/4#issuecomment-731443424
- https://github.com/LiteOS/LiteOS (LiteOS seems what this cameras use)
- FCC documentation https://fccid.io/2AT5D-ZS-GX5/
- https://apis-eu-frankfurt.meari.com.cn/ then endpoint that the mobile app uses (and it seems it runs https://openresty.org/en/)
- http://www.o.hisilicon.com/-/media/Hisilicon/pdf/Surveillance_mobilecam/Hi3516EV200.pdf image sensor used
