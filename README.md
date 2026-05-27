# Aim: 
Measurement of Displacement using LVDT
## Objective:-
Study the relation between core displacement and output of LVDT
Understand the effect of change in supply frequency on LVDT performance
Understand the effect of change in excitation (supply) voltage on LVDT performance.

## Procedure:
First you need to configure the LVDT. Click on ' Show panel' tab at the right bottom For making the circuit, drag and drop the primary coil, Armature and secondary coils at the loactions shown on left hand side.
Now select No of Turns, peak to peak supply volatge and frequency from the drag and drop menu, available below LVDT diagram. Click on configure block to configure LVDT.
Now click on the black rectangular core placed between primary and secondary windings.
Drag the core to left hand side and observe the effect on the output magnitude. This can be observed on the time vs output volatge waveform and on the Distance vs output voltage graph. The core displacement is indicated in the square box below the diagram
Drag the core to right hand side and observe the effect on the output magnitude. Also observe the change in the phase.
Repeat steps 2 to 4 by changing supply volatge keeping frequency and no of turns constant.
Study the effect on the output voltage. For this click on blue color 'Configure' tab in the right side panel. You need to select required parameter value from drop down menu. After selecting the values click on green ' Configure' tab to set the parameter values.
Repeat steps 2 to 4 by changing supply frequency keeping and no of turns constant. Study the effect on the output voltage. Now keep supply voltage and frequency constant. Change the no of turns and observe the effect on the output voltage by repeating steps 2 to 4.

## Circuit Diagram of LVDT
<img width="368" height="654" alt="{D15DCC72-1096-474E-B75D-BD23AF13D6B5}" src="https://github.com/user-attachments/assets/31e0c712-268d-479d-9ab0-bdc3bde0f882" />


## NOTE
The Supply Voltage range is 5V to 15V
The Supply Frequency range is 1KHz to 10KHz
For simulation purpuse ,the Supply Voltage is restricted to 10V and Supply Frequency is restricted to 5 KHz

## Measuremnt:
Number of Turns : 
Supply Voltage :
Supply Frequency :


## Formula Used :
Vout=fIp(4πNpNsµ0bx/3mlog(ro/ri))(1-(x2/2b2))
Where,
f =supply frequency (user selectable)

Ip=primary current = Vin/R

Where Vin (Vrms) is user selectable and R is the coil resistance ( 10 K Ohm)

Np=number of primary turns (user selectable)

Ns=number of secondary turns ( half of primary turns)

ro/ri=Ratio of outer and inner radii of the coil system ( = 2)

x=displacement of the core form null (from actual core postion)

µ0=permeability of space (4π10^-7h/m)

b = length of primary winding (= 20mm)

m = length of secondary winding (= 10 mm)


## Output waveforms:
<img width="691" height="449" alt="{0C4E4247-8A52-479B-A3B4-29C08959B8CE}" src="https://github.com/user-attachments/assets/75917317-5a2f-4c1a-a69a-50a61e838330" />   <img width="237" height="440" alt="{63B4E7B1-5184-42F8-AF40-B3BA650F83AF}" src="https://github.com/user-attachments/assets/f9f1320a-449d-4191-9abb-3194ac98e216" />


## Result:
The displacement of the movable core was successfully measured using the linear variable differential transformer.


