# MEMS_Microphone_SPU0410_PCB
A PCB design for prototyping the Knowles SPU0410 MEMS Ultrasonic Microphone

This is a PCB designed for the Knowles SPU0410LR5H MEMS Microphone [datasheet link](https://www.knowles.com/docs/default-source/model-downloads/spu0410lr5h-qb-revh.pdf).
The SPU0410 microphone has the characteristic of beeing sensitive well beyond the audible audio spectrum in the ultrasonic (up to 80kHz and probably above).
Sadly, the microphone is in really tiny package with solder pads beneath the package, which makes it highly unsuited for hobbyists or prototyping.
The PCB uses a special footprint that still allows to solder the microphone by hand, the idea for this comes from Alan Green, you can read more about it [here](https://hackaday.io/project/165081-blue-board-01/details).
The input port of the microphone is on the backside of the PCB.
The design additionally includes a dual opamp that provides a buffered virtual ground (Vcc/2) as well as +20dB of flat gain. The recommended power supply range is between 1.8V and 3.6V.
