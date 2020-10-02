# NeuroTechEDU's Awesome List of BCI-related Resources 

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This list of resources is non-exhaustive. If you find something which you think should be included, please add it!If you have never worked with Markdown before, check out this [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).  

## Table of Contents

1. [Software](#Software)
   * [Stand Alone BCI Applications](#stand-alone-bci-applications)
   * [Matlab Toolboxes](#matlab-toolboxes)
   * [Python Toolboxes](#python-toolboxes)
   * [Android Toolboxes](#android-toolboxes)
   * [Brain Visualizations](#brain-visualizations)
   * [RaspberryPi Framework](#raspberrypi-framework)
   * [Communication Protocols](#communication-protocols)
2. [Hardware](#hardware)
   * [EEG](#eeg)
     * [Consumer and DIY EEG Devices](#consumer-and-diy-devices)
     * [Research EEG Devices](#research-devices)
     * [BCI Products](#eeg-bci-products)
     * [EEG Parts](#eeg-parts)
   * [NIRS Devices](#nirs-research-devices)
   * [Multimodal Neurotech](#multimodal-neurotech) 
   * [Upcoming NeuroImaging Tech](#upcoming-neuroimaging-tech)
3. [Brain Databases](#brain-databases)
4. [Consultants For Hire](#consultants-for-hire)
5. [Tutorials and Project Ideas](#tutorials-and-project-ideas)
6. [Communities and Blogs](#communities-and-blogs)
   * [Blogs](#blogs)
   * [Forum](#forums)
7. [Competitions](#competitions)
   * [Data Competitions](#data-competitions)  
   * [Brain Controlled Competitions](#brain-controlled-competitions)
8. [Conferences and Events](#conferences-and-events)
9. [Reading Material](#reading-material)
   * [Papers](#papers)
   * [Introductory Books](#introductory-books)
   * [Technical Books](#technical-books)
   * [Signal Processing](#signal-processing)
10. [Other Resources](#other-resources)


## Software


### Stand Alone BCI Applications

These applications do not require any form of dependencies for it to work. Essentially download the program, install it, and you are good to go!

* [OpenVibe](http://openvibe.inria.fr/)
* [BCI2000](http://www.schalklab.org/research/bci2000)
* [Brainstorm](http://neuroimage.usc.edu/brainstorm/)
* [BrainBay](http://www.shifz.org/brainbay/)
* [EventIDE](http://okazolab.com/)

### Matlab Toolboxes

* [EEGLab](http://sccn.ucsd.edu/eeglab/)
* [FieldTrip](http://www.fieldtriptoolbox.org/)
* [BCILab](http://sccn.ucsd.edu/wiki/BCILAB)
* [BBCI](https://github.com/bbci/bbci_public)
* [ERPLAB](http://erpinfo.org/erplab)
* [Psychtoolbox](http://psychtoolbox.org)

### Python Toolboxes

* [Thunder](https://github.com/thunder-project/thunder)
* [Pyff](https://github.com/bbci/pyff)
* [Mushu](https://github.com/bbci/mushu)
* [Wyrm](https://github.com/bbci/wyrm)
* [EEGrunt](https://github.com/curiositry/EEGrunt)
* [Cloudbrain](http://getcloudbrain.com/)
* [Python MNE](http://martinos.org/mne/stable/index.html)
* [OpenNFB](https://github.com/strfry/OpenNFB)
* [bcikit](https://github.com/octopicorn/bcikit)
* [PsychoPy](http://www.psychopy.org/)
* [BioSPPy](https://github.com/PIA-Group/BioSPPy)
* [Timeflux](https://timeflux.io)

### Android Toolboxes

* [EEG-101](https://github.com/NeuroTechX/eeg-101)
* [NeuroSky Android SDK](https://github.com/pwittchen/neurosky-android-sdk)

### Brain Visualizations

* [BrainBox](http://brainbox.pasteur.fr/)
* [BrainBrowser](https://brainbrowser.cbrain.mcgill.ca/)

### RaspberryPi Framework

* [IntelliPi](https://github.com/AtlantsEmbedded/IntelliPi)

### Communication Protocols

These are some of the commonly used Communication protocols 

* [Lab Streaming Layer](https://github.com/sccn/labstreaminglayer)
* [Open Sound Control](http://www.opensoundcontrol.org/)
 

## Hardware
This section is separated into different sections based on the type of technology. 

### EEG
[Electroencephalography](https://en.wikipedia.org/wiki/Electroencephalography) is the most commonly used form of Neurotechnology. There are many options out there meaning that you can easily find a device that matches your needs and price.

#### Consumer and DIY Devices
* [OpenBCI](http://openbci.com)
* [icibici](https://icibici.github.io/site/)
* [Emotiv EPOC](https://emotiv.com/epoc.php) & [Insight](https://emotiv.com/insight.php)
* [Emotiv Insight](https://www.emotiv.com/insight/)
* [Neurosky](http://neurosky.com/)
* [OpenEEG](http://openeeg.sourceforge.net/doc/)
* [EEG-SMT by Olimex](https://bakerdh.wordpress.com/2013/01/31/a-first-look-at-the-olimex-eeg-smt/)
* [FreeEEG32: an open source 32 channel eeg](https://hackaday.io/project/20618-freeeeg32-32-channels-electroencephalography)
* [Muse](https://choosemuse.com/)
#### Research Devices
* [Wearable Sensing Dry Electrode EEG](http://www.wearablesensing.com)
* [g.BCIsys](http://www.gtec.at/Products/Complete-Solutions/g.BCIsys-Specs-Features)
* [EGI High Density EEG](https://www.egi.com/)
* [Biosemi](http://www.biosemi.com/)
* [ANT Neuro](https://www.ant-neuro.com)
* [Advanced Brain Monitoring](http://www.advancedbrainmonitoring.com)

#### EEG BCI Products
These devices use different brain signals for specific use cases (Such as sleeping, controlling a toy, etc). 
* [Muse](http://www.choosemuse.com/)
* [Puzzlebox](https://github.com/PuzzleboxIO)
* [Aurora](https://sleepwithaurora.com)
* [Mattel Mindflex](https://en.wikipedia.org/wiki/Mindflex)
* ~~[The Aware](https://www.kickstarter.com/projects/efitaware/the-aware-kickstart-the-hearable-revolution/)~~ (inactive, failed kickstarter)


#### EEG Parts
* [Florida Research Instruments](http://fri-fl-shop.com/)
* [TI ADS1299EEG-FE](http://www.ti.com/tool/ads1299eegfe-pdk)
* [DIY Electrode Design](https://oshpark.com/shared_projects/h2i1xBaW)
* [Comparison of different types of electrodes](http://www.sciencedirect.com/science/article/pii/S1388245704003906)
* [Intan Technologies](http://intantech.com)


### NIRS Research Devices
* [Artinis Medical Systems](http://www.artinis.com/)
* [Hitachi Hightech](http://www.hitachi-hightech.com/global/product_list/?ld=iis1&md=iis1-6)
* [NIRx](http://nirx.net/)
* [Shimadzu](http://www.ssi.shimadzu.com/products/productgroup.cfm?subcatlink=tissueimaging)

### Multimodal Neurotech 
These devices combine different type of sensors to measure or influence brain activity. 
* [Foc.us Dev kit: EEG,TDCS,fNIRS,TACS](https://world.foc.us/eeg)
* [Neuroelectrics: EEG,TDCS](http://www.neuroelectrics.com/)
* [BITalino: EEG,EMG,ECG,EDA](http://www.bitalino.com/)

### Brain Stimulation
* [DIY TMS](https://www.instructables.com/id/Transcranial-Magnetic-Stimulation-TMS-Device/)


### Upcoming NeuroImaging Tech
* [Functional Ultrasound](http://fultrasound.eu/)
* [FPGA Ultrasound Imaging on a Raspberry Pi ](http://un0rick.cc/FPGA-Rpi)
* [Event Related Optical Signal](https://en.wikipedia.org/wiki/Event-related_optical_signal)
* [Event-Related Optical Signal](https://www.researchgate.net/publication/223360817_Shedding_light_on_brain_function_The_event-related_optical_signal)
* [Quasi-Ballistic Photons. (The Tech being used by Facebook's BCI)](https://arxiv.org/pdf/cond-mat/9906188.pdf)
* [Open Electrical Impedance Tomography](https://github.com/OpenEIT/EIT_PCB)

### Diffused Optical Imaging Ressources. 
This is the tech being used by Mary Lou Jepken's company [Openwater](https://www.opnwatr.io/). She's aiming to build a portable MRI.

* [Diffuse optical imaging/ The tech being used by ](https://en.wikipedia.org/wiki/Diffuse_optical_imaging)
* [Diffuse Optical Imaging pt. 2](https://drive.google.com/file/d/0B-G2rraXdWRlenk2U0QzbW9PdkU/view?usp=sharing)

## Brain Databases

* [SCCN list of eeg/erp data for free public download](http://sccn.ucsd.edu/~arno/fam2data/publicly_available_EEG_data.html)
* [EEG studies with the raw data](http://www.studycatalog.org/) - [(from BigEEG Consortium)](http://www.bigeeg.org/)
* [BNCI Horizon Data Sets](http://bnci-horizon-2020.eu/database/data-sets)
* [g.tec biosignal Data Sets](http://www.gtec.at/Research/Biosignal-Data-Sets/content/Biosignal-Data-Sets)
* [The Child Mind Institute MIPDB Dataset](http://fcon_1000.projects.nitrc.org/indi/cmi_eeg/)
* [RAM (DARPA) Invasive Recording Dataset from U. Penn](http://memory.psych.upenn.edu/RAM)
* [MindBigData MNIST of Brain Digits](http://mindbigdata.com/opendb/index.html)
* [MindBigData ImageNet of The Brain](http://www.mindbigdata.com/opendb/imagenet.html)
* [meagmohit's List of EEG Datasets](https://github.com/meagmohit/EEG-Datasets)

## Consultants For Hire

* [Push The World](www.pushtheworld.us)

## Tutorials and Project Ideas

* [How to Hack Toy EEGs](http://www.frontiernerds.com/brain-hack)
* [BCI Workshop](https://github.com/bcimontreal/bci_workshop/blob/master/INSTRUCTIONS.md)
* [Introduction to Modern BCI](http://sccn.ucsd.edu/wiki/Introduction_To_Modern_Brain-Computer_Interface_Design)
* [Brain-Controlled Shark Attack](http://eeghacker.blogspot.com/2015/03/brain-controlled-shark-attack.html)
* [Controlling a sphero with a muse](https://github.com/neuralcubes/musephero)
* [Building a 20 Euro EEG for your smartphone](https://jmanart.github.io/smartphone-bci-hardware/)
* [Muse File Reader for OpenVibe](http://openvibe.inria.fr/forum/viewtopic.php?f=3&t=9668)
* [EEG 101: Interactive tutorial for Android and Muse](https://github.com/NeuroTechX/eeg-101)
* [Brainwave analyzer](https://github.com/katie356/BrainwaveAnalyzer/tree/master/web-edition)
* [BCI Course offered by Columbia University](http://naplab.ee.columbia.edu/bcilab.html)
* [BCI Course at Berkeley by Pierre of NeuroTechX](https://github.com/NeurotechBerkeley/bci-course)
* [EEG and MRI Course offered by OHBM](https://www.humanbrainmapping.org/m/pages.cfm?pageID=3814)
* [EEG Notebooks: Jupyter notebooks with classic EEG experiments for beginners](https://github.com/NeuroTechX/eeg-notebooks)

## Communities and Blogs

### Forums
* [NeuroBB](https://neurobb.com/)
* [OpenBCI Community](http://openbci.com/community/)
* [Muse Community](http://forum.choosemuse.com/)
* [NeuroSky](http://support.neurosky.com/discussions)
* [Emotiv](https://www.emotiv.com/forums/)

### Blogs

- [Autodidact](http://www.autodidacts.io/)
- [Strfry](http://strfry.org/blog/)
- [Fabien Lotte](https://sites.google.com/site/fabienlotte/code-and-softwares)
- [Chip Audette EEG Hacker](http://eeghacker.blogspot.ca/)
- [Atlants Embedded](http://www.atlantsembedded.com/blog)
- [Alexandre Barachant](http://alexandre.barachant.org/)
- [Pierre Karashchuk](http://lambdaloop.com/)
- [Jeremy Frey](http://phd.jfrey.info/)
- [Irene Vigué Guix](http://www.irenevigueguix.com)

## Competitions

### Data Competitions
* [Kaggle Grasp and Lift](https://www.kaggle.com/c/grasp-and-lift-eeg-detection)
* [Kaggle Error Detection](https://www.kaggle.com/c/inria-bci-challenge)
* [Kaggle Decode the Human Brain](https://www.kaggle.com/c/decoding-the-human-brain)
* [Kaggle Seizure Prediction](https://www.kaggle.com/c/seizure-prediction)
* [Kaggle Seizure Detection](https://www.kaggle.com/c/seizure-detection)
* [Decoding Brain Signals](https://gallery.cortanaintelligence.com/Competition/Decoding-Brain-Signals-2)
* [BCI Competition](http://www.bbci.de/competition/iv/)

### Brain Controlled Competitions

* [Brain Drone Competition](http://braindronerace.com/)
* [Cybathlon](http://www.cybathlon.ethz.ch/)

## Conferences and Events
* [**List**: Curated list of events (BCI Society)](http://bcisociety.org/events/)
* [BCI Meeting](http://bcisociety.org/meetings/bci-meeting-2016-welcome/)
* [NeuroGaming / XTech](http://www.neurogamingconf.com/)[(Youtube Videos)](https://www.youtube.com/user/NeuroGamingCon/videos)
* [CHI](https://chi2016.acm.org/wp/)
* [BrainTech](http://conference.israelbrain.org/)
* [Brain Summit](http://brainsummit.com/)
* [NIPS](https://nips.cc/)
* [SfN](http://www.sfn.org/)

## Reading Material

### Papers

- [MultiClass Brain-Computer INterface Classification by Riemannian Geometry](https://www.researchgate.net/publication/51727880_Multiclass_Brain-Computer_Interface_Classification_by_Riemannian_Geometry)
- [A New Generation of Brain-Computer Interface Based on Riemannian Geometry](https://www.researchgate.net/publication/258144410_A_New_Generation_of_Brain-Computer_Interface_Based_on_Riemannian_Geometry)
- [My Virtual Dream: Collective Neurofeedback in an Immersive Art Environment ](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0130129)
- [BCI Competition IV – Data Set I: Learning Discriminative Patterns for Self-Paced EEG-Based Motor Imagery Detection](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3272647/)
- [Single-Trial Analysis and Classification of ERP Components – a Tutorial](http://doc.ml.tu-berlin.de/bbci/publications/BlaLemTreHauMue10.pdf)
- [Interpretable Deep Neural Networks for Single-Trial EEG Classification](https://www.researchgate.net/publication/301817936_Interpretable_Deep_Neural_Networks_for_Single-Trial_EEG_Classification)
- [Large-Scale Assessment of a Fully Automatic Co-Adaptive Motor Imagery-Based Brain Computer Interface](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0148886)
- [Word pair classification during imagined speech using direct brain recording](http://knightlab.berkeley.edu/statics/publications/2016/10/03/srep25803.pdf)
- [Brain-Computer Interfaces Review, Nicolelis & Lebedev. 2017](https://www.ncbi.nlm.nih.gov/pubmed/28275048)
- [High-speed spelling with a noninvasive brain–computer interface](http://www.pnas.org/content/112/44/E6058.abstract)
- [A high-speed brain-computer interface (BCI) using dry EEG electrodes](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0172400)


### Introductory Books
* [Beyond Boundaries (Nicolellis)](http://www.amazon.com/Beyond-Boundaries-Neuroscience-Connecting-Machines/dp/1250002613)
* [Rhythms of Brain (Buzsaki)](http://www.amazon.com/Rhythms-Brain-Gyorgy-Buzsaki/dp/0199828237)
* [Cycles in mind (Cohen)](http://www.amazon.com/Cycles-mind-rhythms-control-perception-ebook/dp/B013ZI5AIA)
* [Principles of Neural Science (Kandel et al)](http://www.amazon.com/Principles-Neural-Science-Eric-Kandel/dp/0838577016)
* [The Future of the Mind (Kaku)](http://www.amazon.com/The-Future-Mind-Scientific-Understand/dp/038553082X)

### Technical Books
* [Brain-Computer Interfacing: An Introduction (Rao)](http://www.amazon.com/Brain-Computer-Interfacing-Introduction-Rajesh-Rao/dp/0521769418)
* [Brain Computer Interfaces (Wolpaw)](http://www.amazon.com/Brain-Computer-Interfaces-Principles-Jonathan-Wolpaw/dp/0195388852)
* [Analyzing Neural Time Series Data (Cohen)](https://mitpress.mit.edu/books/analyzing-neural-time-series-data)
* [Imaging Brain Function with EEG (Freeman & Quiroga)](http://www.springer.com/us/book/9781461449836)
* [Matlab for Neuroscientists](http://www.amazon.com/MATLAB-Neuroscientists-Introduction-Scientific-Computing/dp/0123745519)
* [Biomedical Optics](https://books.google.ca/books?id=EJeQ0hAB76gC&pg=PR3&redir_esc=y#v=onepage&q&f=false)
* [iMotions Top 10 EEG Books](https://imotions.com/blog/eeg-books/)

### Signal Processing

* [Signals & Systems MIT Class](http://ocw.mit.edu/resources/res-6-007-signals-and-systems-spring-2011/)
* Berkeley DSP class [lectures](https://www.youtube.com/watch?v=6_-ljdxjwac&list=PL-XXv-cvA_iCUQkarn2fxB3NggnPF_dob), [page](https://inst.eecs.berkeley.edu/~ee123/sp15/)
* [Signals & Systems (Oppenheim, Willsky, Hamid)](http://www.amazon.com/Signals-Systems-Edition-Alan-Oppenheim/dp/0138147574)
* [Discrete-Time Signal Processing (2nd Edition) (Oppenheim, Schafer, Buck)](http://www.amazon.com/Discrete-Time-Signal-Processing-Edition-Prentice-Hall/dp/0137549202)
* [Data analysis lecturelets (Mike X Cohen)](http://www.mikexcohen.com/lectures.html)


## Other Resources
* [Neuroscience Summer Schools](https://github.com/PhABC/neuroSummerSchools/blob/master/README.md)
* [Neuroscience Duke Course (Coursera)](https://www.coursera.org/learn/medical-neuroscience)
* [Brede Wiki](http://neuro.compute.dtu.dk/wiki/Main_Page)
* [Novel Neurotechnologies Intervening in the Brain](https://nuffieldbioethics.org/wp-content/uploads/2013/06/Novel_neurotechnologies_report_PDF_web_0.pdf)
* [Augment Human Cognitition by optimizing cortical oscillations](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4072086/)
* [Open Neuroscience](https://open-neuroscience.com/en/) - a user-driven database of Open Source/Science projects related to Neurosciences

