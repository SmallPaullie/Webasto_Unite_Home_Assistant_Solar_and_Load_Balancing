The Webasto Unite charging station acts as a slave device in Modbus TCP/IP communication.
Charging station should have (routed) IP connection with Home Assistant.
Each charging station should have a different IP address. There can only be one active Modbus master connection at any time.
Supports dynamic load balancing, solar charging in combination with home battery.
 
1. Copy the 'packages/modbus_webasto.yaml' file to the 'homeassistant/packages' folder (create folder if not yet exists)
2. Fill in your sensors for the grid power measurement in the code lines at top of package file
3. Add the lines in the secrets.yaml file to your existing secrets.yaml file
4. Add the lines in the configuration.yaml file to the configuration.yaml file
5. If wanted/needed (I recomment!) use supplied example HA View (TAB) 'views/view_webasto.yaml' for managing EV charger
6. Enjoy using solar power for EV charging, with load balancing to prevent grid overload, solar charging and home battery support
