# Characteristic Curves Tracer for diode, bipolar and field-effect transistors

# Required apparatus

* NI myDAQ;
* Diode (N4001), BJT (2N3904), JFET (2N5457);
* OP AMP (LM741CN);
* LabView application for characteristics curve tracer;
* Resistors: 1k Ohms, 1M Ohms;
* Digital multimeter;
* Electric component kit;
* Bread board and conductors

# Reference textbook

Electronic Devices and Circuit Theory, R. L. Boylestad, L. Nashelsky

# Semiconductor diode

A diode is a two-terminal element, usually made by using a p-n junction (the operation of which is
explained in detail in ROBT204 class).
The symbol for a diode is shown in Fig.1 (a). Which terminal is which matters very much in a diode.
Usually, the terminal indicated by a horizontal line in Fig. 1 (a), called the cathode, is marked on a real
diode; see, for example, Fig. 1(b). We define the voltage (vD) and the current (iD) of a diode as shown in
the figure. These two quantities are related, as shown in Fig. 1(c). When the 2 voltage vD is positive, the
diode is said to be forward-biased; a large current can then flow, and the diode is said to conduct. When
the voltage vD is negative, the diode is said to be reverse-biased; the diode current is extremely small, and
for our purposes it is assumed to be zero; the diode is then said to be turned off. Thus, the diode
effectively conducts current in only one direction (downward in Fig. 1); it “refuses” to conduct current in
the other direction. This property turns out to be very useful, as you will find out in this experiment.

<p align="center"> 
<img src="https://github.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/blob/master/illustrations/diode.JPG?raw=true"/>
</p>
<p align="center">
Fig. 1 – Symbolic representation of diodes (a), diode (b), diode IV characteristic (c)
</p>

<p align="center"> 
<img src="https://github.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/blob/master/illustrations/1N4001.JPG?raw=true"/>
</p>
<p align="center">
1N4001 diode
</p>

# BJT Transistor

Transistors fall into two categories (bipolar junction or bipolar and field-effect) and are also classified
according to the semiconductor material employed (commonly silicon, others are germanium, gallium
arsenide, etc.) and to their field of application (e.g. general purpose, switching, high frequency, etc.).
Various classes of transistor are available according to the application concerned.
Bipolar transistors generally comprise NPN or PNP junctions of either silicon (Si) or germanium (Ge)
material. (See Figs. 1 and 2). The junctions are produced in a single slice of silicon by diffusing
impurities through a photographically reduced mask (in course Integrated Circuit Design). Germanium
devices are rarely encountered and are ignored here. Figures 1 and 2, respectfully, show a simplified
representation of NPN and PNP transistors together with circuit symbols.

<p align="center"> 
<img src="https://raw.githubusercontent.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/master/transistor_kinds.JPG"/>
</p>

In either case the electrodes are labelled collector, base and emitter. Note that each junction within the
transistor, whether it be collector-base or base-emitter, constitutes a P-N junction.

<p align="center"> 
<img src="https://raw.githubusercontent.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/master/illustrations/transistor_kinds2.JPG"/>
</p>

Two sets of characteristics are again necessary to describe fully the behavior of the common-emitter
configuration: one for the input or base–emitter circuit and one for the output or collector–emitter circuit.
Both are shown in Fig. 5.
The emitter, collector, and base currents are shown in their actual conventional current direction. Even
though the transistor configuration has changed, the current relations developed earlier for the common-
base configuration are still applicable. That is, IE = IC + IB and IC = aIE.
For the common-emitter configuration the output characteristics are a plot of the output current ( I C )
versus output voltage ( V CE ) for a range of values of input current ( I B ). The input characteristics are a
plot of the input current ( I B ) versus the input voltage ( V BE ) for a range of values of output voltage (
V CE ).

<p align="center"> 
<img src="https://raw.githubusercontent.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/master/illustrations/BJT_curves.JPG"/>
</p>

# Construction and characteristics of JFET

JFET’s are of two types, namely N-channel JFETs and P-channel JFETs. Generally N-channel JFETs are more
preferred than P-channel. N-channel and P-channel JFETs are shown in the figures below.

<p align="center"> 
<img src="https://raw.githubusercontent.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/master/illustrations/FET_transistors.JPG"/>
</p>

# Standard Notations in FET:

* Source – The terminal through which the majority carriers enter the channel, is called the sourceterminal S and
the conventional current entering the channel at S is designated as I g .
* Drain –  The terminal, througih which the majority carriers leave the channel, is called the drainterminal D
and the conventional current leaving the channel at D is designated as I D .
The drain-to- source voltage is called V DS , and is positive if D is more positive than source S
* Gate – There are two internally connected heavily doped impurity regions formed by alloying, by diffusion, or
by any other method available to create two P-N junctions. These impurity regions are called the gate G. A
voltage V GS  is applied between the gate and source in the direction to reverse-bias the P-N junction.
Conventional current entering the channel at G is designated as I G .
* Channel –  The region between the source and drain, sandwiched between the two gates is called
thechannel and the majority carriers move from source to drain through this channel.

<p align="center"> 
<img src="https://raw.githubusercontent.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/master/illustrations/FET_schema.JPG"/>
</p>

The graphical approach, however, will require a plot of Eq.1 to represent the device and a plot of the
network equation relating the same variables. The solution is defined by the point of intersection of the
two curves. It is important to keep in mind when applying the graphical approach that the device
characteristics will be unaffected by the network in which the device is employed.
The network equation may change along with the intersection between the two curves, but the transfer
curve defined by Eq. 1 is unaffected. In general, therefore:
The transfer characteristics defined by Shockley’s equation are unaffected by the network in which the
device is employed.

<p align="center"> 
<img src="https://raw.githubusercontent.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/master/illustrations/shockley_eq.JPG"/>
</p>

The transfer curve can be obtained using Shockley’s equation. In Fig. 6 two graphs are
provided, with the vertical scaling in milliamperes for each graph. One is a plot of I D versus V
DS , whereas the other is I D versus V GS . Using the drain characteristics on the right of the “y”
axis, we can draw a horizontal line from the saturation region of the curve denoted V GS 0 V to
the I D axis. The resulting current level for both graphs is I DSS . The point of intersection on
the I D versus V GS curve will be as shown since the vertical axis is defined as V GS 0 V.

<p align="center"> 
<img src="https://github.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/blob/master/illustrations/fet_characteristics.JPG?raw=true"/>
</p>

# LabView Application

In this lab experiment we are going to use application that made on LabView and NI myDAQ
tool to trace diode, BJT and JFET characteristics curves. All that we do in this experiment
building appropriate circuit, running application and analyzing result. Application itself is
LabView program that all necessary codings is already ready to work.

<p align="center"> 
<img src="https://github.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/blob/master/illustrations/UI_diode.JPG?raw=true"/>
</p>

<p align="center"> 
<img src="https://github.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/blob/master/illustrations/block_diagram.JPG?raw=true"/>
</p>

<p align="center"> 
Figure 8. Block diagram sample of application
</p>

NI myDAQ is a low-cost data acquisition (DAQ) device that gives students the ability to
measure and analyze live signals anywhere, anytime. We will use two voltage analog outputs,
two voltage analog inputs and constant voltages (+15 V, -15V).

<p align="center"> 
<img src="https://github.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/blob/master/illustrations/myDAQ.JPG?raw=true"/>
</p>

Application controls NI myDAQ tool to generate and acquire appropriate analog voltages through
pins(Fig 9).

<p align="center"> 
<img src="https://github.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/blob/master/illustrations/myDAQ2.JPG?raw=true"/>
</p>

<p align="center"> 
Figure 9. NI myDAQ pins
</p>

# Task 1

# Diode characteristic curve

V_AO 0 will generate analog DC voltage which will be increasing by V_AO 0 step which you write in
the application. NI myDAQ will read difference between V_AI 1+ and V_AI 1- and divide by R which is
our current through diode. Each iteration will be putted on the graph and make curve.

<p align="center"> 
<img src="https://github.com/BatyaGG/Characteristic-Curves-Tracer-for-diode-bipolar-and-field-effect-transistors/blob/master/illustrations/circuit1.JPG?raw=true"/>
</p>

