# PopupChat 

PopupChat is an open anonymous instant chat room.


PopupChat is an Arduino sketch that turns your ESP32 into an open wifi access
point that connects users to an anonymous chat room.  The user is (usually)
sent directly into a popup web browser with the software open as soon as they
connect to the wireless AP, because it acts like a Captive Portal (think "hotel
wifi").

## Ethics

PopupChat features impermanence. All data is temporary, and PopupChat maintains
no logs. The entire system is reset to its default state when power is cycled. 

