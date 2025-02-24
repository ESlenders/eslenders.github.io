---
title: "BrightEyes-MCS: a control software for multichannel scanning microscopy"
collection: publications
date: 2024-11-24
venue: 'The Journal of Open Source Software'
authors: 'Mattia Donato, Eli Slenders, Alessandro Zunino, Luca Bega, Giuseppe Vicidomini'
paperurl: https://doi.org/10.21105/joss.07125
doi: 10.21105/joss.07125
tagline: '- Paper'
type: "MCS"
---

<h2> Abstract </h2>
<p align= "justify">
In live-cell microscopy, the demand for high-resolution imaging coexists with the necessity to protect sample integrity. Fast pixel dwell times are instrumental in this pursuit, minimizing sample damage while enhancing image quality. Leveraging the capabilities of the SPAD array detector, which can achieve megahertz photon flux per single pixel, requires an advanced data acquisition and control system based on FPGA technology. Existing open-source microscope control software, such as ImSwitch and µManager, while general-purpose, flexible, and scriptable, are primarily designed for camera-based systems. They are not optimized to handle the precise synchronization and high-performance demands of ISM instruments, especially for configuration with pixel dwell times as low as 1 µs and photon flux rates in the megahertz range. In contrast, BrightEyes-MCS (Microscope Control Suite) is an open-source software specifically designed for controlling laser-scanning microscopes equipped with SPAD detectors. It overcomes the limitations of other software by providing real-time synchronization, high-throughput data acquisition, and seamless compatibility with the high-speed scanning demands of ISM systems.

BrightEyes-MCS not only features a user-friendly graphical interface (GUI) for microscope control, but also supports real-time previews and efficient data saving in the HDF5 format, which is ready for internal processing or integration with external analysis tools. Although tailored for ISM, BrightEyes-MCS is versatile and can be adapted for various applications, including fluorescence correlation spectroscopy (FCS), spectroscopy, and other advanced imaging techniques. This flexibility makes it a valuable resource for researchers working with diverse microscopy setups that require precise control and high-performance data acquisition.</p>
  
<p align= "justify">
PDF <a href="../../files/Donato_10.21105.joss.07125.pdf">here.</a></p>
  
