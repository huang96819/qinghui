---
layout: archive
title: "Research Experience"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?hl=en&tzom=300&user=j0mw7EAAAAAJ}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

 &emsp; _University of Florida_              &emsp;     &emsp;                      **_Supervisor: Prof. Shuo Wang_**
 
*  **EMI modeling and reduction of traction inverter for electrical vehicle**  &emsp;      Aug. 2023-present supported by Ford Motor Company
  
  1)	Diagnosis and analysis of CM/DM EMI noise sources and propagation paths in e-powertrain
  
  2)	Investigated and developed CM/DM EMI models of e-powertrain to predict CM/DM EMI noise up to 108MHz including 
  extraction and simulation of parasitic parameters of CM/DM EMI noise path in e-powertrain, modeling and prediction of 
  spectrum analyzers considering RBW effects
   
  3)	Designed EMI filter and balance technique to reduce CM/DM EMI noise

  *  **Radiated EMI filters design for power converters**  &emsp;      Nov. 2022-Jul. 2023
    
1)	Developed radiated EMI model of power converters with radiated EMI filters
   
2)	Identified and developed a model for a new radiation antenna consisting of power converters and output cables excited by voltage of CM choke
   
3)	Proposed radiated EMI filter design procedure and topology/value selection guidelines

   
*  **High-frequency CM EMI model and performance improvement for isolated converters**   Feb. 2022-Nov. 2022
  
1)	Investigated CM EMI model of isolated converters including flyback converter, two-switch forward converter, and LLC converter especially related to model and physical mechanism of resonance in CM impedance of the transformer
2)	Proposed new transformer structure of primary winding in bifilar structure with an effective frequency range of two-capacitor model and capacitance balance EMI reduction technique increasing by ~50%
3)	Proposed RLC balance technique for transformer with the benefit of CM EMI noise reduction frequency range doubled and almost 20 dB CM EMI noise reduction for 1kW LLC converter
   
*  **Integration of near-field communication (NFC) antenna and wireless charging(WLC) coil**  &emsp;      Sep. 2021-Feb. 2022
  
1)	Investigated integration between NFC antenna and WLC coil leveraging leakage inductance
   
2)	Characterized and built circuit and physical model of integration coil at high frequency
   
3)	Proposed integration coil demonstrating 15W wireless power delivery and successful NFC communication which shows 3 times power transfer ability compared to the existing technique



 &emsp; _Zhejiang University_              &emsp;     &emsp;                      **_Supervisor: Prof. Wuhua Li_**
*  **DC Microgrid Operation and Fault Detection**        &emsp;                     Nov. 2018-Mar.2021

1)	Virtual damping control for improvement of dynamic performance in DC microgrid

2)	Islanding detection method for safe operation in the abnormal condition in DC microgrid

3)	Seamless transfer strategy at islanding event for improvement of reliability and quality of power supply

   &emsp; Outcomes: proposed two DC-based islanding detection methods


  &emsp; _Hunan University_              &emsp;    
  *  **2017 National Undergraduate Electronics Design Contest**       &emsp;                   May 2017-Sep. 2017
   
                      
   
 &emsp; Main activities and responsibilities:
 
1)	Design and implementation of AC microgrid simulator consisting of two inverters

2)	Implementation of specific operating requirements such as efficiency, control strategy, etc.

3)	Hardware design for the power circuit, including parameter design, PCB layout, and device selection and software design and debugging for the control system

   &emsp; Outcomes: Second Prize in the contest of China and First Prize in the contest of Hunan Province

