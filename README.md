# BlinkingLeds_TivaC_Autosar
 Training Garraio Final project is implementation Dio and Port AUTOSAR drivers using Cordoba tool to lighten Tiva-C leds in sequence cw or ccw using state Machine.
# Description
Create 2 software components(swc), swc1 for checking either switch1 or switch2 in tiva c is
pressed and communicate with swc2 through sender/receiver to take decision and lightens leds
in sequence (Red Green Blue) or the reverse of the sequence based on switch. offcourse systick is used for
debouncing and intterupt for the switches. swc2 communicates with another swc in CDD
client/server communication through the RTE layer and the CDD calls the APIS from MCAL layer
where it contains all the registers needed from the static code.
