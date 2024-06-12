# NeuroTechEDU's Awesome List of BCI-related Resources

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a list of tools, resources, and learning materials related to Brain-Computer Interfaces (BCI). The list is maintained by the [NeuroTechX](https://neurotechx.com/) community.

This list of resources is non-exhaustive. If you find something which you think should be included, please add it! If you have never worked with Markdown before, check out this [cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## Table of Contents

- [NeuroTechEDU's Awesome List of BCI-related Resources](#neurotechedus-awesome-list-of-bci-related-resources)
  - [Table of Contents](#table-of-contents)
  - [Software](#software)
    - [BCI Experiment Design and Analysis](#bci-experiment-design-and-analysis)
    - [Matlab Toolboxes](#matlab-toolboxes)
    - [Python Toolboxes](#python-toolboxes)
    - [Mobile Apps](#mobile-apps)
    - [Brain Visualizations](#brain-visualizations)
    - [RaspberryPi Framework](#raspberrypi-framework)
    - [Communication Protocols](#communication-protocols)
  - [Hardware](#hardware)
    - [EEG](#eeg)
      - [Consumer and DIY Devices](#consumer-and-diy-devices)
      - [Research Devices Manufactures](#research-devices-manufactures)
      - [EEG Parts \& Supplies](#eeg-parts--supplies)
    - [NIRS](#nirs)
    - [Multimodal Neurotech](#multimodal-neurotech)
    - [Brain Stimulation](#brain-stimulation)
    - [Upcoming NeuroImaging Tech](#upcoming-neuroimaging-tech)
  - [Brain Databases](#brain-databases)
  - [Consultants For Hire](#consultants-for-hire)
  - [Tutorials and Project Ideas](#tutorials-and-project-ideas)
  - [Communities and Blogs](#communities-and-blogs)
    - [Forums](#forums)
    - [Blogs](#blogs)
  - [Competitions](#competitions)
    - [Data Competitions](#data-competitions)
    - [Brain Controlled Competitions](#brain-controlled-competitions)
  - [Conferences and Events](#conferences-and-events)
  - [Reading Material](#reading-material)
    - [Papers](#papers)
    - [Introductory Books](#introductory-books)
    - [Technical Books](#technical-books)
    - [Signal Processing](#signal-processing)
  - [Schools \& Summer Courses](#schools--summer-courses)
  - [Other Resources](#other-resources)

## Software

### BCI Experiment Design and Analysis

These applications help you design BCI experiments, run them, collect data, and analyze the results.

* [EEG-ExPy](https://github.com/NeuroTechX/eeg-expy): Free & Open-Source (FOSS) Python library for EEG & experiment design, recording, and analysis. Maintained by the EEG-ExPy team within NeuroTechX. [CNS2024 Poster](https://bit.ly/m/eeg-expy-cns)
* [OpenViBE](http://openvibe.inria.fr/): A software platform dedicated to designing, testing, and using Brain-Computer Interfaces, maintained by the OpenViBE Consortium.
* [BCI2000](http://www.schalklab.org/research/bci2000): Software suite with GUI based on C++ for data acquisition, stimulus presentation, and brain monitoring applications.
* [Brainstorm](http://neuroimage.usc.edu/brainstorm/): Collaborative, open-source application dedicated to the analysis of brain recordings: MEG, EEG, fNIRS, ECoG, depth electrodes and multiunit electrophysiology.
* [BrainBay](http://www.shifz.org/brainbay/): Bio- and neurofeedback application working with various hardware frameworks including OpenBCI/OpenEEG.
* [EventIDE](http://okazolab.com/): EventIDE is a software platform for designing and running multimodal experiments, with an IDE.
* [NeuroPype](https://neuropype.io): platform for real-time brain-computer interfacing (BCI), neuroimaging, and neural signal processing, which supports a range of biosignal modalities including EEG, fNIRS, ExG, etc.
* [MNE](https://mne.tools/stable/install/mne_tools_suite.html): MNE-Python is an open-source Python module for processing, analysis, and visualization of functional neuroimaging data (EEG, MEG, sEEG, ECoG, and fNIRS). The tools suite includes interoperable packages in Python, MATLAB, C++, etc., which operate in GUI, CLI, or API.
* [PsychoPy Builder](https://www.psychopy.org/builder/): PsychoPy is an open-source application for creating experiments in neuroscience, psychology, and psychophysics.
* [PsychToolBox](http://psychtoolbox.org/): Psychophysics Toolbox Version 3 (PTB-3) is a free set of Matlab and GNU Octave functions for vision and neuroscience research.

### Matlab Toolboxes

* [EEGLab](http://sccn.ucsd.edu/eeglab/)
* [FieldTrip](http://www.fieldtriptoolbox.org/)
* [BCILab](http://sccn.ucsd.edu/wiki/BCILAB)
* [BBCI](https://github.com/bbci/bbci_public)
* [ERPLAB](http://erpinfo.org/erplab)
* [Psychtoolbox](http://psychtoolbox.org)
* [Chronux](http://chronux.org/)

### Python Toolboxes

* [Thunder](https://github.com/thunder-project/thunder)
* [Pyff](https://github.com/bbci/pyff)
* [Mushu](https://github.com/bbci/mushu)
* [Wyrm](https://github.com/bbci/wyrm)
* [EEGrunt](https://github.com/curiositry/EEGrunt)
* [Cloudbrain](http://getcloudbrain.com/)
* [MNE-Python](https://github.com/mne-tools/mne-python)
* [OpenNFB](https://github.com/strfry/OpenNFB)
* [bcikit](https://github.com/octopicorn/bcikit)
* [PsychoPy](http://www.psychopy.org/)
* [BioSPPy](https://github.com/PIA-Group/BioSPPy)
* [Timeflux](https://timeflux.io)
* [EEGsynth](https://github.com/eegsynth/eegsynth)
* [pyRiemann](https://github.com/pyRiemann/pyRiemann)
* [MOABB](https://github.com/NeuroTechX/moabb)
* [NeuroPrime](https://github.com/nmc-costa/neuroprime)
* [Braindecode](https://braindecode.org/dev/index.html)
* [Brainflow](https://brainflow.org)
* [EEG-ExPy](https://github.com/neurotechx/eeg-expy)
* [PyBCI](https://github.com/LMBooth/pybci)

### Mobile Apps

* MindMonitor: [iOS App Store](https://apps.apple.com/ca/app/mind-monitor/id988527143), [Google Play Store](https://play.google.com/store/apps/details?id=com.sonicPenguins.museMonitor)
* NeuroSky Android SDK: [Google Play Store](https://github.com/pwittchen/neurosky-android-sdk)
* EEG-101 (Now-deprecated): [Google Play Store](https://github.com/NeuroTechX/eeg-101)

### Brain Visualizations

* [BrainBox](http://brainbox.pasteur.fr/)
* [BrainBrowser](https://brainbrowser.cbrain.mcgill.ca/)
* [Moonlight](https://zzz.bwh.harvard.edu/luna/moonlight/)

### RaspberryPi Framework

* [PiEEG](https://pieeg.com/)
* [Blino PiNaps](https://github.com/BlinoTech/BlinoTech.github.io)
* [IntelliPi](https://github.com/AtlantsEmbedded/IntelliPi) (deprecated)

### Communication Protocols

These are some of the commonly used Communication protocols.

* [Lab Streaming Layer](https://github.com/sccn/labstreaminglayer)
* [Open Sound Control](http://www.opensoundcontrol.org/)
* [FieldTrip buffer](http://www.fieldtriptoolbox.org/development/realtime/buffer_protocol/)

## Hardware
This section is separated into different sections based on the types of technology. 

### EEG
[Electroencephalography](https://en.wikipedia.org/wiki/Electroencephalography) is the most commonly used form of Neurotechnology. There are many options out there meaning that you can easily find a device that matches your needs and price.

#### Consumer and DIY Devices

Some of these devices are still supported and actively developed by manufacturers, community members, or researchers. Others are no longer supported but may still have a community of users who can help you get access.

* [Muse 2016, Muse 2, Muse S](https://choosemuse.com/)
* [OpenBCI Ganglion, Cyton, Daisy, Galea](http://openbci.com)
* [IDUN Guardian](https://iduntechnologies.com/idun-guardian)
* [Neurable MW75 Neuro](https://neurable.com/)
* [Neurosity Crown](https://neurosity.co/)
* [Nucleus-Hermes](https://re-ak.com/)
* [BrainBit Headband & Flex](https://brainbit.com/)
* [Emotiv EPOC, Flex, Insight](https://emotiv.com)
* [Dreem by Beacon Biosignals](https://beacon.bio/dreem-headband/)
* [Cognionics](http://www.cognionics.com/)
* [Elemind](https://elemindtech.com/)
* [Melomind](https://www.themelomind.com/)
* [Neurosky](http://neurosky.com/)
* [FreeEEG32: an open source 32 channel eeg](https://www.crowdsupply.com/neuroidss/freeeeg32)
* [EEG-SMT by Olimex](https://bakerdh.wordpress.com/2013/01/31/a-first-look-at-the-olimex-eeg-smt/)
* [HackEEG](https://www.crowdsupply.com/starcat/hackeeg)
* [icibici](https://icibici.github.io/site/)
* [OpenEEG](http://openeeg.sourceforge.net/doc/)

#### Research Devices Manufactures

* [Wearable Sensing Dry Electrode EEG](http://www.wearablesensing.com)
* [g.tec](https://www.gtec.at)
* [EGI High Density EEG](https://www.egi.com/)
* [BioSemi](http://www.biosemi.com/)
* [ANT Neuro](https://www.ant-neuro.com)
* [Advanced Brain Monitoring](http://www.advancedbrainmonitoring.com)
* [Brain Products](https://www.brainproducts.com/)
* [Mentalab Explore](https://mentalab.com/)
* [Natus Neuro](http://www.natus.com)
* [TMSi](https://www.tmsi.com/products/)

#### EEG Parts & Supplies

* [Conscious Labs - EEG Supra Headphones](https://conscious-labs.com/3-eeg-devices)
* [Emotiv Flex Gel](https://www.emotiv.com/products/flex-gel) & [Emotiv Flex Saline](https://www.emotiv.com/products/flex-saline)
* [Florida Research Instruments](http://fri-fl-shop.com/)
* [DIY Electrode Design](https://oshpark.com/shared_projects/h2i1xBaW)
* [TI ADS1299EEG-FE](http://www.ti.com/tool/ads1299eegfe-pdk): Analog Front End for EEG solutions. e.g., in OpenBCI Cyton.
* [Intan Technologies](http://intantech.com): Microchips and miniature recording & stimulation headstages.
* [IDUN Dryode](https://shop.openbci.com/products/idun-dryode-kit): Adhesive dry electrodes for EEG.
* [Bio-Medical](https://bio-medical.com/supplies/eeg-electrodes.html): For supplies and consumables
* [Comparison of different types of electrodes](http://www.sciencedirect.com/science/article/pii/S1388245704003906)

### NIRS

Near-Infrared Spectroscopy (NIRS) is a technology that measures the concentration of hemoglobin in each brain region, which can be used to infer energy expenditure and hence higher activity in that region.

* [Artinis Medical Systems](http://www.artinis.com/)
* [CortiVision](https://www.cortivision.com/)
* [Hitachi Hightech](http://www.hitachi-hightech.com/global/product_list/?ld=iis1&md=iis1-6)
* [NIRx](http://nirx.net/)
* [Shimadzu](http://www.ssi.shimadzu.com/products/productgroup.cfm?subcatlink=tissueimaging)
* [Kernel Flow](https://kernel.co): EEG + TD-fNIRS

### Multimodal Neurotech

These devices combine different type of sensors to measure or influence brain activity.

* [Foc.us Dev kit: EEG,TDCS,fNIRS,TACS](https://world.foc.us/eeg)
* [Neuroelectrics: EEG,TDCS](http://www.neuroelectrics.com/)
* [BITalino: EEG,EMG,ECG,EDA](http://www.bitalino.com/)
* [Emotibit: EDA,PPG,Temperature](https://www.emotibit.com/)

### Brain Stimulation

* [DIY TMS](https://www.instructables.com/id/Transcranial-Magnetic-Stimulation-TMS-Device/): Transcranial Magnetic Stimulation (TMS)
* [Boston Scientific](https://www.bostonscientific.com/en-US/products/deep-brain-stimulation-systems.html): DBS, SCS
* [Medtronic](http://www.medtronic.com/us-en/index.html): DBS, tES, SCS
* [Magstim](https://www.magstim.com/): TMS
* [Soterix Medical](https://www.soterixmedical.com/): TDCS, tACS, tRNS
* [Clarity](https://clarity-technologies.com/): Light & Stimulation therapy for Alzheimer's Disease
* [Vielight](https://vielight.com/): Transcranial Photobiomodulation
* [Neuroelectrics](http://www.neuroelectrics.com/): tDCS, tACS, tRNS
* [NeuroPace](https://www.neuropace.com/): RNS
* [NerveX](https://nervexneurotech.com/): VNS in canine epilepsy.
* [NeuroSigma](https://neurosigma.com/): eTNS
* [Brainsway](https://www.brainsway.com/): Deep TMS

### Upcoming NeuroImaging Tech

* [Functional Ultrasound (FUS)](http://fultrasound.eu/)
* [FPGA Ultrasound Imaging on a Raspberry Pi ](http://un0rick.cc/FPGA-Rpi)
* [Event Related Optical Signal](https://en.wikipedia.org/wiki/Event-related_optical_signal)
* [Event-Related Optical Signal](https://www.researchgate.net/publication/223360817_Shedding_light_on_brain_function_The_event-related_optical_signal)
* [Quasi-Ballistic Photons. (The Tech being used by Facebook's BCI)](https://arxiv.org/pdf/cond-mat/9906188.pdf)
* [Open Electrical Impedance Tomography](https://github.com/OpenEIT/EIT_PCB)
* [Optically Pumped Magnetometers (OPM)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9805039/), e.g., [QuSpin](https://quspin.com/) and [Cerca](https://www.cercamagnetics.com/cerca-opm-meg):
  * "Optically" stabilizing highly sensitive magnetometers to measure the change in magnetic fields due to neural activity.
  * Does not need Helium cooling like conventional (SQUID) MEG, and hence is much smaller and lighter, and somewhat cheaper.
* Diffused Optical Imaging: Used for instance by Mary Lou Jepken et al @ [Openwater](https://www.opnwatr.io/), aiming to build a portable MRI. More info on the tech:
  * [Diffuse optical imaging pt. 1 (wiki)](https://en.wikipedia.org/wiki/Diffuse_optical_imaging)
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
* [OpenNeuro](https://openneuro.org/)
* [PhysioNet](https://physionet.org/)
* [National Sleep Research Resource](https://sleepdata.org/): A large collection of sleep data. Supported by the Sleep Research Society (SRS).
* [Temple University EEG Corpora](https://isip.piconepress.com/projects/): various datasets including health, epilepsy, artifactual, etc.

## Consultants For Hire

* [NeuroTechX Services](https://neurotechx-services.com/): Specialized Advisory group dedicated to supporting Startups, Scaleups, Strategics and Investors in their efforts to commercialize Neurotechnology and (Neuro) Digital Health innovations.

## Tutorials and Project Ideas

* [EEGEdu](https://eegedu.com): Web-based live Tutorial on EEG and BCI, from basic to advanced. Maintained by the Mathewsons ([Ky](https://sites.psych.ualberta.ca/kylemathewson/)[Kor](https://korymathewson.com/)[Key](https://www.linkedin.com/in/keyfer/))
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

## Communities and Blogs

### Forums
* [NeuroBB](https://neurobb.com/)
* [OpenBCI Community](http://openbci.com/community/)
* [Muse Community](http://forum.choosemuse.com/)
* [NeuroSky](http://support.neurosky.com/discussions)
* [Emotiv](https://www.emotiv.com/forums/)

### Blogs

- [NeuroTechX Content Lab](https://neurotechx.medium.com/): Articles, tutorials, and interviews on neurotechnology
- [The EEG Newsletter](https://eegnewsletter.substack.com/): News, events, and resources in EEG. By Raquel E. London
- [Natalie Schaworonkow](https://nschawor.github.io/posts/)
- [Autodidact](http://www.autodidacts.io/)
- [Strfry](http://strfry.org/blog/)
- [Fabien Lotte](https://sites.google.com/site/fabienlotte/code-and-softwares)
- [Chip Audette EEG Hacker](http://eeghacker.blogspot.ca/)
- [Atlants Embedded](http://www.atlantsembedded.com/blog)
- [Alexandre Barachant](http://alexandre.barachant.org/)
- [Pierre Karashchuk](http://lambdaloop.com/)
- [Jeremy Frey](http://phd.jfrey.info/)
- [Irene Vigué Guix](http://www.irenevigueguix.com)
- [Fred Simard | RE-AK Technologies (medium)](https://medium.com/@re-ak)

## Competitions

### Data Competitions
* [Kaggle Grasp and Lift](https://www.kaggle.com/c/grasp-and-lift-eeg-detection)
* [Kaggle Error Detection](https://www.kaggle.com/c/inria-bci-challenge)
* [Kaggle Decode the Human Brain](https://www.kaggle.com/c/decoding-the-human-brain)
* [Kaggle Seizure Prediction](https://www.kaggle.com/c/seizure-prediction)
* [Kaggle Seizure Detection](https://www.kaggle.com/c/seizure-detection)
* [Decoding Brain Signals](https://gallery.cortanaintelligence.com/Competition/Decoding-Brain-Signals-2)
* [BCI Competition](http://www.bbci.de/competition/iv/)
* [BR41N.io BCI Competition](https://www.br41n.io/)

### Brain Controlled Competitions
* [Brain Drone Competition](http://braindronerace.com/)
* [Cybathlon](http://www.cybathlon.ethz.ch/)

## Conferences and Events
* [**List**: Curated list of events (BCI Society)](http://bcisociety.org/events/)
* [BCI Meeting](http://bcisociety.org/meetings/bci-meeting-2016-welcome/)
* [NeuroGaming / XTech](http://www.neurogamingconf.com/) [(Youtube Videos)](https://www.youtube.com/user/NeuroGamingCon/videos)
* [CHI](https://chi2016.acm.org/wp/)
* [BrainTech](http://conference.israelbrain.org/)
* [Brain Summit](http://brainsummit.com/)
* [NIPS](https://nips.cc/)
* [SfN](http://www.sfn.org/)
* [g.tec SpringSchool on BCI](https://www.gtec.at/spring-school-2021/)

## Reading Material

### Papers

- [Multiclass Brain-Computer Interface Classification by Riemannian Geometry](https://www.researchgate.net/publication/51727880_Multiclass_Brain-Computer_Interface_Classification_by_Riemannian_Geometry)
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

## Schools & Summer Courses

* [NeuroTech MicroCredentials Course](https://neurotechmicrocreds.com/): An accredited series of theoretical and hands-on courses on Neurotechnology, offered by NeuroTechX and Queens University.
* [Neuromatch Academy (NMA) Summer Schools](https://neuromatch.io/academy/): An online, community-driven set of summer schools in computational sciences
* [Sinxpress summer schools](https://sincxpress.com/summerschool.html) by Mike X. Cohen
* [Brainhack](https://brainhack.org/): A community-driven, online, and in-person school for neurotech enthusiasts, happening in many cities around you!
* Recurring summer schools or community-maintained lists of Neurotech-related summer schools
  * [List maintained by N. Schwar](https://nschawor.github.io/posts/2024/neuro-summer-schools/)
  * [List maintained by N. Biswas](https://nayanika-biswas.notion.site/58f1530bd891475eb92f1e2e4984022f?v=83fc50c53b3a4191aa6f7cdf8d9b4e40)

## Other Resources
* [Neuroscience Duke Course (Coursera)](https://www.coursera.org/learn/medical-neuroscience)
* [Brede Wiki](http://neuro.compute.dtu.dk/wiki/Main_Page)
* [Novel Neurotechnologies Intervening in the Brain](https://nuffieldbioethics.org/wp-content/uploads/2013/06/Novel_neurotechnologies_report_PDF_web_0.pdf)
* [Augment Human Cognition by optimizing cortical oscillations](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4072086/)
* [Open Neuroscience](https://open-neuroscience.com/) - a user-driven database of Open Source/Science projects related to Neurosciences
* [Awesome-BCI-Reviews](https://github.com/okbalefthanded/awesome-bci-reviews) - Curated list of Brain-Computer Interface peer-reviewd published reviews and surveys ordered by year of publication.
* [Mindscape-Emotions](https://bit.ly/mindscape-emotions-en) - An eBook exploring emotional and cognitive analysis of entertainment experiences at scale, using the Nucleus-Hermès.
