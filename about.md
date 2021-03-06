---
layout: page
title: About
permalink: /about/
---


The COSMO (Csound On Stage Musical Operator) project is an open source project providing the software and hardware instructions to make a DIY effect pedal based on the [Raspberry PI](https://www.raspberrypi.org) computer and [Csound](https://csound.com).

![alt text](/images/Live_01.png "Live")

### Background

[Csound](https://csound.com) is a powerful, multi-platform, real-time sound-processing environment that allows musicians to design their own instruments and audio-effects by writing a few lines of [Csound](https://csound.com) code. The initial aim of the “Csound On Stage Music Operator” (COSMO) project was to run [Csound 6](https://csound.com) on a standalone musical device specifically designed for live performance [1].

![alt text](/images/3_COSMO_designs.JPG "3 different COSMO designs")

### COSMO Workshops 

The basic scheme proposes a guitar pedal design with regular quarter jack-in and jack-outputs, 3 footswitches and 5 knob potentiometers. Csound 6 (Csound Python API) is running on a Raspberry Pi micro-computer, equipped with an additional sound card for low latency audio input and audio output. The advantage of such a design is the straightforward inclusion of individual designed digital audio-effects (like granular frequency modulation) into a regular live-electronics setup and provide direct haptic control of [Csound](https://csound.com) to the performing musician. Such a musical device may also enable non-programming instrumentalists to use [Csound](https://csound.com) in their analog live-performance setups. 

Do-it-yourself (DIY) build instructions for the pedal-box and a SD-card image with all required software installed and preconfigured, will be provided on the [COSMO project github page] (http://cosmoproject.github.io). 

Additionally, we are giving [workshops](http://cosmoproject.github.io/workshop) were we assist in building these devices and show how easy it is to design custom audio-effects with [Csound](https://csound.com). This may result in a [Csound](https://csound.com) live-performer community, sharing sound modification [Csound](https://csound.com) patches, developed for such stand alone musical devices [2].

### Project Core Developers
* [Bernt Isak Wærstad](https://www.ntnu.no/ansatte/bernt.warstad): Software development, workshop presenter
* [Alex Hofmann](http://iwk.mdw.ac.at/hofmann.htm): Software development, workshop presenter
* [Kristoffer Koch](http://www.kristofferkoch.com): Hardware development, circuit design

Former Members:

* Kim Ervik: Hardware development

### Contact us

[csoundonstage@gmail.com](mailto:csoundonstage@gmail.com)

The project is funded by the [Arts Council Norway](http://www.kulturradet.no/)

![alt text](images/logos/kulturraadet_sort_liten.png)

[1] Ervik, Kim; Hofmann, Alex, and Waerstad, Bernt I. (2013)
"COSMO - Csound On Stage Musical Operator,"
at 2nd International Csound Conference (Boston, USA).

[2] Hofmann, Alex and Waerstad, Bernt I. (2015)
"COSMO 2.0 - Csound on Stage Musical Operator,"
at The 3rd International Csound Conference (St. Petersburg, Russia).

[3] Hofmann, Alex; Waerstad, Bernt I. and Koch, Kristoffer E. (2016) 
"Csound Instruments On Stage" 
at New Interfaces for Musical Expression 2016 (Brisbane, Australia)

[4] Hofmann, Alex; Waerstad, Bernt I.; Balasubramanian, Saranya and Koch, Kristoffer E. (2017)
"From interface design to the software instrument - Mapping as an approach to FX-instrument building"
at New Interfaces for Musical Expression 2017 (Copenhage, Denmark)



