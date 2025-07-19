# Inverter-RP6048E-to-Home-Assistant

# Home Assistant integration of Inverter RP6048E with Modbus TCP Hex String on rs485 serial port.

To make the integration work, you must replace the following values in the code:

- converter IP address
- converter port

To make the inverter efficiency sensor work, you need to replace the following unique IDs in the code:

- sensor mppt power 1 ( or more )
- sensor battery power out
- sensor battery power in

# example code:

<img width="899" height="461" alt="example_1" src="https://github.com/user-attachments/assets/efaf16db-fce7-4053-98b2-02b694463cc4" />

<img width="1151" height="516" alt="example_2" src="https://github.com/user-attachments/assets/6579bd54-45c7-472d-b11a-63c371993708" />


# rs485 to eth or wifi converter

I recommend using this one, but you can use any similar device:

<img width="572" height="562" alt="elfin" src="https://github.com/user-attachments/assets/4d469038-2bab-48d5-91bc-66994577c552" />

https://a.aliexpress.com/_EzQiFGI


# settings :

<img width="955" height="872" alt="serial_settings" src="https://github.com/user-attachments/assets/ebdf3813-08b1-4d9f-a5e7-44e16bf9fb63" />


<img width="946" height="875" alt="communication_settings" src="https://github.com/user-attachments/assets/dc22de72-1ae1-4385-af00-9f1b14c9a5c6" />


# Inverter communication port :

<img width="629" height="917" alt="inverter_port" src="https://github.com/user-attachments/assets/e4737eea-9201-488f-8bf1-bdecc0e39a5d" />


# The converter can be powered directly from the inverter's communication port by connecting correctly as shown in the diagram.










