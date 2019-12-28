# MQTT-SN_802.15.4_DeviceT1_THR_RLP
MQTT-SN 802.15.4 Net - End device Type 1 RLP THR (Temp/Humidity/Reed)

An up to date MQTT-SN Client implementation based on MRF24J40 and Arduino

Visit project website at https://sites.google.com/view/hobbyiot/projects/mqtt-sn-802-15-4

Twitter: @sivanovbg

This is the End device Type 1 THR Real Low power Arduino code. Work is still in progress...

Type 1 stands for Sensor node and THR means Temperature, Humidity and Reed sensors within.

The implementation is based ot MQTT-SN Specification Version 1.2. Arduino board used is Arduino Pro Mini @ 3.3 V. The 3.3V regulator has to be removed or disconnected as shown on the schematic.

Topics should be predefined on the client and gateway sides and are fixed to 2 positions alpha-numeric string.

Messages supported:

CONNECT

CONNACK

PINGREQ

PINGRESP

PUBLISH
