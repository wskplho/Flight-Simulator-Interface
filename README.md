### FlightSimulatorInterface: The P&P Homecockpit Interface

FlightSimulatorInterface (**FSI**) manages the connection between your [Arduinos](https://github.com/arduino/Arduino) and Flight Simulator

Currently FSI only supports Prepar3D and the PMDG 737 NGX. Future support for FS9/FSX and other airplanes is planned. However, I'm only focusing on PMDG support for now.

## Project Goals

FSI aims to drastically decrease the required amount of work you need to make your self-built homecockpit parts pretty much Plug & Play. These goals drive the development of FSI:

- [x] Establishing a connection between flight simulator and an Arduino
- [ ] Graphical User Interface
  - [ ] Select from a list of all connected devices (possibly the Arduino could register itself first)
  - [ ] ...
- [ ] Configuring mode and transmitted control states
- [ ] More to come...

## Homecockpit

I've been fascinated with flying for several years. I almost started the training towards a Private Pilot License, but the lack of enough money stopped me. Instead I'm now trying with a couple of friends to build a complete Boeing 737-800 homecockpit so we can simulate aviation as real as it gets.

I didn't want to just buy every piece of hardware for hundreds or thousands of Euros and figured we should be able to build most of the hardware ourselves. After all, our group includes someone with a degree in mechanical engineering and an electrical engineer - I myself am a professional web developer with some experience in C++, C# and Java. So instead we wanted to do our own research and figure out what works best.

All of our R&D is being documented on my (German) blog at [padarom.de](http://www.padarom.de).
