<p align="center"><img src="http://www.openworm.org/img/OpenWormLogo.png" alt="OpenWorm"/></p>

# OpenWorm updates August 2022

[**OpenCollective as a new funding stream**](#1-opencollective-as-a-new-funding-stream)

[**OpenWorm Studentships - first successful project completed**](#2-openworm-studentships---first-successful-project-completed)

[**NeuroPAL**](#3-neuropal)

[**Electrophysiological data from worm neurons**](#4-electrophysiological-data-from-worm-neurons)

[**DevoWorm updates**](#5-devoworm-updates)

[**OpenWorm simulation stack updates**](#6-openworm-simulation-stack-updates)


[**Other announcements**](#7-other-announcements)

## 1) OpenCollective as a new funding stream

<p align="center"><img src="img/opencollective.png" alt="OpenWorm" width="400"/></p>

We have added [OpenCollective](https://opencollective.com/openworm) as a new and easy way to donate to OpenWorm. Regular contributions to the project (monthly/yearly) are possible through this funding stream. See https://openworm.org/donate for more details.

One of the first uses of these funds will be to support **OpenWorm Studentships** (see below).

## 2) OpenWorm Studentships - first successful project completed

OpenWorm Studentships are a new way to incentivize contribution to the OpenWorm project, offering small stipends and recognition to junior researchers who want to spend time bringing their research into OpenWorm and making it more accessible for the wider community. See [here](https://openworm.org/studentships.html) for more information.

The first person to complete an OpenWorm Studentship project has been **Tyson Wheelwright**. He has made significant updates to the [Blender 2 NeuroML](https://github.com/openworm/Blender2NeuroML/) subproject.

<p align="center"><img src="https://github.com/openworm/Blender2NeuroML/raw/master/images/ADAL.png" height="300"/></p>
<p align="center"><sup><i>Figure showing images of a single cell (<a href="https://www.wormatlas.org/neurons/Individual%20Neurons/ADAframeset.html">ADAL</a>) taken from the original
<a href="https://github.com/openworm/Blender2NeuroML/blob/master/src/Data/Virtual_Worm_March_2011.blend">3D Blender file</a> (from the
<a href="http://caltech.wormbase.org/virtualworm">Virtual Worm Project</a>) on the left, and the corresponding image of the cell in
<a href="https://docs.neuroml.org/Userdocs/NeuroMLv2.html">NeuroML 2</a> format on the right (which is being used in our
<a href="https://github.com/openworm/c302">biophysical model of the worm nervous system</a>). See
<a href="src/NeuroMLImages/README.md">here</a> for more examples.</i></sup></p>

More Studentships will be offered to the community in late 2022.


## 3) NeuroPAL

The recent paper <a href="https://www.sciencedirect.com/science/article/pii/S0092867420316822">NeuroPAL: A Multicolor Atlas for Whole-Brain Neuronal Identification in <i>C. elegans</i></a> described a groundbreaking new technique to create a genetic strain of the worm where each neuron
is labelled with a fluorescent marker of a specific color, allowing easy identification of neurons across experiments and animals.

We have converted one of these datasets containing positions of cell bodies and the expressed NeuroPAL colors to NeuroML, to allow it to be used in OpenWorm models and associated applications. Full details can be found [here](https://github.com/openworm/NeuroPAL).

<p align="center"><kbd><img src="https://raw.githubusercontent.com/openworm/NeuroPAL/main/NeuroML2/Screenshot_Canonical.png" alt="NeuroPAL" width="550"></kbd></p>

<p align="center"><sup><i>The above image shows the canonical positions and colors of a NeuroPAL dataset which has been <a href="https://github.com/openworm/NeuroPAL/tree/main/NeuroML2">converted into NeuroML</a>, allowing it to be <a href="https://www.opensourcebrain.org/projects/neuropal/repository/revisions/main/show/NeuroML2?explorer=https%253A%252F%252Fraw.githubusercontent.com%252Fopenworm%252FNeuroPAL%252Fmain%252FNeuroML2%252FNeuroPAL_Canonical.net.nml">visualised on Open Source Brain</a>.</i></sup></p>


## 4) Electrophysiological data from worm neurons

Electrical recordings from individual neurons in <i>C. elegans</i> are crucial experimental data required for creating biologically realistic computational models of the worm.

Electrophysiological recordings of the activity of the [ASH neuron](https://www.wormatlas.org/neurons/Individual%20Neurons/ASHframeset.html) made by the [Wormsense Lab](https://med.stanford.edu/goodmanlab.html) of Miriam Goodman were converted to open, standardized [Neurodata Without Borders](http://nwb.org) format as part of a [Google Summer of Code](https://summerofcode.withgoogle.com/) project in 2021 by Steph Prince. Further details, as well as all of the converted datasets, can be found [here](https://github.com/openworm/WormsenseLab_ASH).

<p align="center"><img src="https://raw.githubusercontent.com/openworm/WormsenseLab_ASH/main/images/example_goodman_lab_file.png" width=600/></p>
<p align="center"><sup><i>A view of the
<a href="http://nwbexplorer.opensourcebrain.org/">NWB Explorer</a> interface showing one of the converted electrophysiological datasets. Click
<a href="https://github.com/openworm/WormsenseLab_ASH/blob/main/test_data/README.md">here</a> to explore other datasets and get direct links to NWB Explorer to browse them.</i></sup></p>


## 5) DevoWorm updates

<p align="center"><img src="https://github.com/OREL-group/GSoC/blob/main/Media/DW.png" height="150"/></p>

Over the past year, [DevoWorm](https://devoworm.weebly.com/) has been involved in a number of initiatives. DevoWorm hosted four [Google Summer of Code](https://summerofcode.withgoogle.com/) students in 2022: Karan Lohaan and Harikrishna Pillai worked on the Digital Microspheres project (a spherical platform for embryo data), while Jiahang Li and Wataru Kawakami worked on developing a Graph Neural Network pipeline for the DevoLearn platform.  

DevoWorm also had a presence at [NetSci 2022](https://netsci2022.net/) (virtual conference hosted in Shanghai). Bradly Alicea presented on the group's Embodied Hypernetworks work in the main conference, as well as serving to represent the group at the Network Neuroscience satellite session as a presenter and participant.  

Our [weekly meetings](https://www.youtube.com/playlist?list=PLJ8ZcBZeKeci2ACwfllCDFn_eZAXlbGQN) are a continuing success. We cover a number of technical topics and a wide variety of topical reviews spanning biophysics, developmental biology, computational analysis, and more. Join us on Mondays at 2pm UTC (1pm UTC in winter) to get involved.  

## 6) OpenWorm simulation stack updates

<p align="center"><img src="https://raw.githubusercontent.com/openworm/OpenWorm/master/img/worm-crawling.gif" alt="Worm Crawling" width="550"></p>

Dockerfile

## 7) Other announcements

Poster at C elegans last year??
More...
