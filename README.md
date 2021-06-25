# Musical Armband 
A haptic synthesizer inspired by the roland TB303, designed for cochlear implant users

Current Status can be seen @ **https://youtu.be/LC58CtU7uzo**

https://2021.worldhaptics.org/sic/

## Authors

### Team

<!-- For each team member, duplicate this following subsection and update Name, biography, pronouns and website. Please store pictures under images/portraits/ and use only Name in CamelCase for filenames. -->

#### Razvan Paisa

<img alt="Picture of Razvan" src="images/portraits/Razvan New.png" width="100px" height="auto"/>

I am currently a PhD studen at Aalborg University in Copenhagen, Denmark, working on integrating vibrotactile stimuli into music listening for cochlear implant users. For up-to-date information on what i do, visit our lab's page: [Multisensory Experience Lab](https://melcph.create.aau.dk/)

#### Anders Bargum (He/Him)

<img alt="Picture of Anders" src="images/portraits/Anders.png" width="100px" height="auto"/>

My name is Anders Bargum. I am an audio nerd and HCI interested student at the 'Sound and Music Computing' masters degree at Aalborg University in Copenhagen, Denmark. 
 
Find more information about the topics we are passionate about at <!-- update pronouns--> [SMC AAU](https://www.smc.aau.dk/).

<!-- ### Advisor -->

<!-- Uncomment this section title and add a #### Name subsection if your team appointed an advisor. -->

### Chairs

#### Christian Frisson

<img alt="Christian Frissons's picture" src="images/portraits/ChristianFrisson.jpg" width="100px" height="auto"/>

Christian Frisson is an associate researcher at the Input Devices and Music Interaction Laboratory (IDMIL) (2021), previously postdoctoral researcher at McGill University with the IDMIL (2019-2020), at the University of Calgary with the Interactions Lab (2017-2018) and at Inria in France with the Mjolnir team (2016-2017). He obtained his PhD at the University of Mons, numediart Institute, in Belgium (2015); his MSc in “Art, Science, Technology” from Institut National Polytechnique de Grenoble with the Association for the Creation and Research on Expression Tools (ACROE), in France (2006); his Masters in Electrical (Metrology) and Mechanical (Acoustics) Engineering from ENSIM in Le Mans, France (2005). 
Christian Frisson is a researcher in Human-Computer Interaction, with expertise in Information Visualization, Multimedia Information Retrieval, and Tangible/Haptic Interaction. Christian creates and evaluates user interfaces for manipulating multimedia data. Christian favors obtaining replicable, reusable and sustainable results through open-source software, open hardware and open datasets. 
With his co-authors, Christian obtained the IEEE VIS 2019 Infovis Best Paper award and was selected among 4 finalists for IEEE Haptics Symposium 2020 Most Promising WIP.

Find more information on his [website](https://frisson.re).

#### Jun Nishida

<img alt="Jun Nishida's picture" src="images/portraits/JunNishida.jpg" width="100px" height="auto"/>

Jun Nishida is **Currently** Postdoctoral Fellow at University of Chicago & Research Fellow at Japan Society for the Promotion of Science (JSPS PDRA) / **Previously** JSPS Research Fellow (DC1), Project Researcher at Japanese Ministry of Internal Affairs and Communications, SCOPE Innovation Program & PhD Fellow at Microsoft Research Asia / Graduated from Empowerment Informatics Program, University of Tsukuba, Japan. 

I’m a postdoctoral fellow at University of Chicago. I have received my PhD in Human Informatics at University of Tsukuba, Japan in 2019. I am interested in designing experiences in which all people can maximize and share their physical and cognitive capabilities to support each other. I explore the possibility of this interaction in the field of rehabilitation, education, and design. To this end, I design wearable cybernic interfaces which share one’s embodied and social perspectives among people by means of electrical muscle stimulation, exoskeletons, virtual/augmented reality systems. Received more than 40 awards including Microsoft Research Asia Fellowship Award, national grants, and three University Presidential Awards. Review service at ACM SIGCHI, SIGGRAPH, UIST, TEI, IEEE VR, HRI.

Find more information on their [website](https://junis.sakura.ne.jp/wp).

#### Heather Culbertson

<img alt="Heather Culbertson's picture" src="images/portraits/HeatherCulbertson.jpg" width="100px" height="auto"/>

Heather Culbertson is a Gabilan Assistant Professor of Computer Science at the University of Southern California. Her research focuses on the design and control of haptic devices and rendering systems, human-robot interaction, and virtual reality. Particularly she is interested in creating haptic interactions that are natural and realistically mimic the touch sensations experienced during interactions with the physical world. Previously, she was a research scientist in the Department of Mechanical Engineering at Stanford University where she worked in the Collaborative Haptics and Robotics in Medicine (CHARM) Lab. She received her PhD in the Department of Mechanical Engineering and Applied Mechanics (MEAM) at the University of Pennsylvania in 2015 working in the Haptics Group, part of the General Robotics, Automation, Sensing and Perception (GRASP) Laboratory. She completed a Masters in MEAM at the University of Pennsylvania in 2013, and earned a BS degree in mechanical engineering at the University of Nevada, Reno in 2010. She is currently serving as the Vice-Chair for Information Dissemination for the IEEE Technical Committee on Haptics. Her awards include a citation for meritorious service as a reviewer for the IEEE Transactions on Haptics, Best Paper at UIST 2017, and the Best Hands-On Demonstration Award at IEEE World Haptics 2013.

Find more information on her [website](https://sites.usc.edu/culbertson/).

## Contents

Generated with `npm run toc`, see [INSTALL.md](INSTALL.md).

Once this documentation becomes very comprehensive, the main file can be split in multiple files and reference these files.

<!-- Table of contents generated by running from repository root: npm run toc -->

<!-- toc -->

- [Abstract](#abstract)
- [Introduction](#introduction)
  * [Documentation](#documentation)
    + [Hardware](#hardware)
      - [Wiring](#Wiring)
    + [Software](#software)
- [Acknowledgements](#acknowledgements)
- [License](#license)

<!-- tocstop -->

## Abstract
<!-- Summarize your project: for now copy the short pitch from your proposal -->
Musical Armbrand is a multi-actuator vibrotactile wearable device, designed to augment the music listening experience for persons using  cochlear implants. We constructed the device on the principle of \textit{multisensory integration} that describes how humans form coherent, valid, and robust perception of reality, by processing sensory stimuli from various modalities. Multisensory integration suggests that enhancement  can occur only for stimuli that are temporally coincident and propose that enhancement is strongest for those stimuli that individually are least effective - in our case, the auditory one.
## Introduction
<!-- Explain your project: for now copy the 300-word description from your proposal -->
Studies focusing on the psychological, emotional and social benefits associated with music listening propose that it provides a platform for multi faceted  self-related thoughts focusing on emotion and sentiments, escapism, coping, solace and meaning of life. Unfortunately, not everybody is allowed access to these benefits for different reasons, but one category of people in particular are affected: the hearing impaired. According to the World Health Organization (WHO), almost half a billion people suffer from disabling hearing loss, with a predicted 900 million by the year 2050.

In order to enhance their music listening experience we propose a musical haptic wearable device that is based on the principle of multisensory integration - a documented phenomena that occurs at very early stages of cognition, resulting in supra-additive integration of touch and hearing. This translates to a robust synergy between the two sensory apparatuses, that can be exploited to synthesize experiences impossible to achieve by unisensory means - especially for the hearing impaired community, where the hearing mechanism is (partially) faulty. 

Our proposed device is composed from an array of actuators placed on the top side of the forearm representing musical notes from a diatonic scale. The transducers will be following a note-to-position mapping scheme, with the lowest note closest to the wrist, and it's higher octave counterpart closest to the elbow. The device is expected to be used in combination with headphones/speakers by users with residual hearing or cochlear implants, and will use MIDI encoding to generate the haptic stimuli. The same protocol will be used to play a custom software synthesizer.
### Documentation
These are the tools necessary for the hardware: scissors, pliers, flat head screwdriver(provided in the kit), wire cutters, wirre stripper, permanent marker, office tape(the stickier the better), 6 rubber bands (not shown in the picture), soldering tin and an 2x8 Pin 16 Pin IDC Female Header(optional). 
<img alt="Tools necessary" src="images/Building Process/Tools.jpg" width="1024x" height="auto"/>
#### Hardware
<!-- Describe your hardware components -->
The hardware is composed from an array of 6 actuators placed on the top side of the forearm representing musical notes from a pentationic scale + the octave of the lowest one. Each transducer can reproduce only one note and the array is following a note-to-position mapping scheme, with the lowest note closest to the elbow, and the higher one closest to the wrist. The project runs on a Raspberry Pi  with an Audio Injector Octo sound card cape, that is connected to a Mahi Syntacts Amp 3.1 for the necessary amplification. The amplifier board is getting powered by the USB 3.0 port on the RPi. Below you can see a picture of the whole setup.
<img alt="Final Setup" src="images/Building Process/Final.jpg" width="1024x" height="auto"/>

##### Wiring
The wiring is very simple since most of the connectors provided in the kit are already made - thank you for making our job easier. The only thing that needs to be wired manually is the actuators themselves. We used channels 2-8 of the amplifier, to connect one actuator/channel. To do this, we are using a 12 wire multi-wire ribbon with a pitch of 2.54(not part of the kit, but the one provided should be just as good). 
First step is to allign and mark down ribbon according to the distance between the actuator sockets, as the figures below show.

<img alt="Ribbon Alignment" src="images/Building Process/Ribbon Alligned.jpg" width="425x" height="auto"/> <img alt="Ribbon markings" src="images/Building Process/Ribbon Marked.jpg" width="425x" height="auto"/>

Step 2 is to cut pairs of wires according to the markings, strip the ends, and apply a little solder tin on the each exposed wire. It is not necesary to strip the ends more than 2-3mm.

<img src= "images/Building Process/Ribbon Cut.jpg" width="500x" height="auto"/> <img src="images/Building Process/Splits Soldered.jpg" width="450x" height="375x"/>

Step 3 is to make solder one actuator for each pair of wires, and test the fitting as shown below.
<img alt="Actuators Installed" src="images/Building Process/Actuators installed.jpg" width="1024x" height="auto"/>
Last step is to create the IDC connector.
TBA
#### Software
The software is runs in Pure Data v5.0.3 , on the Patchbox OS RPi distro, and it's split between an haptic synthesizer, and an audio synthesizer. More TBA
<!-- Describe your software components -->

- hello
- hello


## Acknowledgements

<!-- Describe your software components -->

SIC chairs would like to thank Evan Pezent, Zane A. Zook and Marcia O'Malley from [MAHI Lab](http://mahilab.rice.edu) at Rice University for having distributed to them 2 [Syntacts](https://www.syntacts.org) kits for the [IROS 2020 Intro to Haptics for XR Tutorial](http://iros-haptics-tutorial.org/). 
SIC co-chair Christian Frisson would like to thank Edu Meneses and Johnty Wang from [IDMIL](http://idmil.org) at McGill University for their recommendations on Raspberry Pi hats for audio and sensors.

## License

This documentation is released under the terms of the Creative Commons Attribution Share Alike 4.0 International license (see [LICENSE.txt](LICENSE.txt)).
