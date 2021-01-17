---
layout: splash
permalink: /research/
title: "Research"
categories: pages
header:
  overlay_image: /assets/images/LandingPageHeader.jpeg
  overlay_filter: 0.5

overview:
  - image_path: /assets/research/AreaOfInterest.jpeg
    alt: "Area of Interest"
    title: "Toward Sustainable Purification and Separation Processes"
    excerpt: "The PAST laboratory aims to develop sustainable technologies for challenging purification and separation problems. To achieve this the research activities span all the way from understanding fundamentals to developing processes. *Particulate Technology*, *Gas Separation*, and *Porous Materials* are the three focus areas of the laboratory. <br />"
---

<br />

{% include feature_row id="overview" type="center" %}

<p align="center"><a href="#ParTech" class="btn btn--primary">Particulate Technology</a> <a href="#" class="btn btn--primary">Gas Separation</a> <a href="#" class="btn btn--primary">Porous Materials</a></p>

<h3 id="ParTech">Particulate Technology</h3>
Crystals can be found today in every aspect of our lives. They appear either as a naturally occurring material or as a chemically synthesized product from a industrial process. Minerals, gemstones, and snowflakes are examples of the former, while pharmaceutical drugs, sugar, table salt, and cocoa fat in chocolates are examples of the latter. Crystallization is a separation and purification technique, which is defined as a phase change in which a crystalline product is obtained from a solution or a melt. Crystallization processes are frequently applied in food, in bioprocessing, and in pharmaceuticals industries, to name a few. The crystalline products from these industries are produced in scales ranging from a few milligrams to a few thousand tons annually. Even though the process of crystallization appears simple on paper, there exist several bottlenecks for a robust, reliable, and safe operation. Irrespective of the widespread use of crystallization for decades, it can be said with certainty that it is poorly understood. 
{: .text-justify}

The work performed in this group will hold a small piece of a very large puzzle aimed to understand and to develop better processes involing particulate matter (or crystals here). The work here falls within the broader domain of *Crystal Shape Engineering*. As of today the research topics that are being pursued are:
* Characterization of the size and shape of particulate populations
* Manipulation of the size and shape of particulate populations
* Downstream processability of crystallized products
{: .text-justify}

<h4>Characterization of the size and shape of particulate populations</h4>
Crystallization typically involves a number of fundamental phenomena - often poorly understood - like nucleation, growth, dissolution, breakage, to name a few. The lack of reliable monitoring and characterization tools inhibits attaining deeper insights into the mechanisms involved, which thereof affects the robust and optimal operation of these crystallization processes. Crystals exhibit different shapes depending on the crystal habit, and an accurate characterization of shape is critical in the design and control of such processes. Often, commercially available crystallization process characterization tools condense shape related information of crystals into a single characteristic length. Commercially available sizing tools that rely on the assumption of a single characteristic length, such as focused beam reflectance measurement (FBRM), laser diffraction, Coulter counter, as well as monoscopic imaging tools, are prone to errors and misleading effects for nonspherical particles. Multiprojection imaging systems, have the ability to tackle shape-related issues rather satisfactorily, thus reducing the ill effects encountered by commercial sizing tools for nonspherical particles, thereby providing the so called *particle size and shape distribution* (PSSD). (see Figure 1).
{: .text-justify}

{% include figure image_path="/assets/research/DISCO.jpg" alt="DISCO" caption="Figure 1: Illustration of the multistep image processing approach for the multiprojection imaging device, DISCO (*Dual Imaging System for Crystallization Observation*). The device takes images from orthogonal directions and processes the images thus obtained to provide a multidimensional particle size and shape distribution. (Rajagopalan et al., *Powder Technol.* **2017**, 321, 479–493.)" %}

Employing imaging based techniques for crystallization processes, even though being powerful, poses several engineering challenges. For example, the nature in which these devices operate (*in situ* or *ex situ*, online or offline), the maximum suspension density that the device can tolerate without losing accuracy, physical and optical properties of crystals and solvent (e.g. chiral compounds, aggregating compounds) are some of the commonly encountered problems. Some of things that are under consideration include developing:
* an *in situ* multiprojection imaging probe
* an imaging tool to track the size and shape chiral systems
* a *dry* powder size and shape characterization tool
{: .text-justify}

The projects in this sub area are open ended and will lead to scenarios with high risk and high gain. Advancements in other communities like computer vision and machine learning, form the basis of innovation in this sub area.
{: .text-justify}

<h4>Manipulation of the size and shape of particulate populations</h4>
Recent developments in imaging techniques have led to characterizing nonequant crystals (particularly needle-like crystals) with moderate to high accuracy, which was not possible till a few years back. This has contributed to an increased interest in size and shape manipulation of nonequant crystals, which influences the downstream processing operations. Processes developed to manipulate the size and shape of nonequant populations have exploited temperature cycling or mechanical action or combination of these (see Figure 2). It was evident from many of these studies that incorporating additional actuators like antisolvent or growth inhibiting modifiers might be beneficial to induce a broader manipulation of size and shape.
{: .text-justify}

In this sub area, the goal is to develop size and shape manipulation processes for nonequant compounds (e.g. elongated morphology, plate-like morphology) using a variety of actuators. To this aim, the following steps are usually considered:
* Development of a multidimensional mathematical model to describe the process
* Estimating the multidimensional growth/dissolution kinetics of a model compound
* Fine-tuning the process using the estimated kinetics, optimizing the process in a modeling framework, and testing the performance in an experimental setting
* Employing feedback control methodologies to have a robust process performance
{: .text-justify}

{% include figure image_path="/assets/research/ThreeStageProcess.jpg" alt="Three stage process" caption="Figure 2: A schematic of a three stage process developed to manipulate the size and shape of elongated crystals to equant crystals. The process employs temperature cycling and mechanical action to achieve the goal. (Salvatori and Mazzotti, *Ind. Eng. Chem. Res.* **2017**, 56, 9188−9201.)" %}

<h4>Downstream processability of crystallized products</h4>
The crystallization step in a typical pharmaceutical production chain is followed by the downstream processing steps, i.e. filtration, washing, drying, redissolution, and formulation. These steps are as important as the crystallization step in determining the final properties of the crystallized product. The particle size and shape distribution (PSSD) after crystallization is one of the major factors that affects the downstream processes apart from surface properties, electrostatic properties, moisture content, and brittleness (see Figure 3). 
{: .text-justify}

{% include figure image_path="/assets/research/Downstream.jpg" alt="Downstream" caption="Figure 3: Processability of a compound that exhibits equant and elongated morphology. The equant particles forms a nice heap (good flowability), while the elongated shaped forms huge lumps (poor flowability)." %}

In this sub area the aim is to bridge the gap between the upstream crystallization step (discussed in the previous sub area) with the downstream processing steps. In a nut shell, the goal is to devise a mathematical model that takes as an input the size and shape characteristics of a particulate population and gives as an output the processability of the final product after downstream processing (see Figure 4). To this aim, the following steps will be undertaken:
* Modeling the individual downstream processing steps using simple/complex particle dynamics models
* Evaluating the impact of different PSSDs on the downstream processes
* Linking the upstream and downstream processing steps using novel mathematical modeling tools (e.g. surrogate (machine learning) and/or hybrid modeling)
{: .text-justify}

{% include figure image_path="/assets/research/DownstreamVision.jpg" alt="Downstream Vision" caption="Figure 4: A potential scenario in the future, where given an input PSSD one can quantitatively judge the processability of particulate matter. Size and shape manipualation tools can then be employed to re-engineer the particles to enhance its processability." %}
