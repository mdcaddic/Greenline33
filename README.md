Greenline33 manuals for original equipment

json files for node red dashboards 

- 48v Power
- RPi Control - borrowed from https://pysselilivet.blogspot.com/
- 12v Power
- Navigation Data - Use lat/long to update the boats-near-us html page.
Link opens a new tab with vesselfinder.com web site using current lat/long and sets zoom to 13 

Sun Chi configuration
VW TDI150-5
Iskra 7kw/5kw electric
6 x solar panels in two strings of three
aircon
Victron 48/3000/35 inverter charger
Victron 12v charger

1 x Raspberry Pi 4 - 8GB (PowerPi) running Venus OS Large
connected via VeDirect to MPPT 150/35
connected via VeDirect to BMV602S
connected via Mk3 cable to the inverter

1 x Raspberry Pi 4 - 8GB (NavPi) running openplotter
Also running docker and containers with
filebrowser
kapacitor
chronograf
lms
grafana
mosquitto
heimdall
influxdb
dozzle
