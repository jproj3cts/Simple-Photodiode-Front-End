# Simple-Slow-Photodiode-Front-End (Work in progress)
This project aims to provide a very simple slow (~15KHz) but low noise photodiode front end, for the use in building scientific instrumentation.

<img src="Media/pdCircuit.PNG" width=30% height=30% alt = "pdCircuit.png" title="pdCircuit.png">

The general scheme of this device is shown below. As can be seen, it is formed of three sections: a capacitance multiplier, a 3.3V regulator, and the OPT101 itself. The first two stages function to minimise input noise as much as possible, with the capacitance multiplier functioning to almost entirely remove mains ripple. The OPT101 is a monolithic photodiode and single-supply transimpedance amplifier, so conveniently amplifies the photodiode output without . The disadvantage of course is that it has a relatively limited bandwidth of ~15KHz, but this should be good enough for applications that require only a slow response time such as a spectrophotometer.

<img src="Media/pdDiagram.PNG" width=100% height=100% alt = "pdDiagram.png" title="pdDiagram.png">



## BILL OF MATERIALS
  ```
  Raspberry Pi Pico W
  28BYJ-48 stepper motor, 1/16th reduction (or equivalent)
  A suitable stepper motor driver board (this guide references the driver board in this pack: https://thepihut.com/products/stepper-motor-driver-pack)
  A suitable plastic project box (metal cannot be used as it will block wifi connectivity)
  USB A to Micro USB 2.0 cable
  20 mm diameter heat shrink
  ```
  
 ## Assembly


