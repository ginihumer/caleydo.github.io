---
layout: publication
title: "TACO: Visualizing Changes in Tables Over Time"
key: 2017_infovis_taco
permalink: /publications/2017_infovis_taco/
type: paper

shortname: TACO
image: 2017_infovis_taco.png

# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2017_infovis_taco_teaser.png


authors:
- Christina Niederer
- stitz
- Reem Hourieh
- Florian Grassinger
- Wolfgang Aigner
- streit

journal: IEEE Transactions on Visualization and Computer Graphics (InfoVis '17), _to be published_
year: 2017
award: 

#doi: 10.1109/TVCG.2017.xxxxxxx
# use publisher only if no doi is available
publisher: 


project: taco

#video: 2017_infovis_taco_video
#preview-video: 2017_infovis_taco_video_preview


pdf: 2017_infovis_taco.pdf
supplement:
supplements:
# - name: Music Dataset project (CAL)
#   link: 2014_infovis_domino_number_ones.cal

#bibtex: 2017_infovis_taco.bib

abstract: "
<p>Multivariate, tabular data is one of the most common data structures used in many different domains.</p>
<p>Over time, tables can undergo changes in both structure and content, which results in multiple versions of the same table. A challenging task when working with such derived tables is to understand what exactly has changed between versions in terms of additions/deletions, reorder, merge/split, and content changes. For textual data, a variety of commonplace "diff" tools exist that support the task of investigating changes between revisions of a text. Although there are some comparison tools which assist users in inspecting differences between multiple table instances, the resulting visualizations are often difficult to interpret or do not scale to large tables with thousands of rows and columns.</p>
<p>To address these challenges, we developed TACO, an interactive comparison tool that visualizes effectively the differences between multiple tables at various levels of detail. With TACO we show (1) the aggregated differences between multiple table versions over time, (2) the aggregated changes between two selected table versions, and (3) detailed changes between the selection. To demonstrate the effectiveness of our approach, we show its application by means of two usage scenarios.</p>"

---

# Acknowledgements

We want to thank Samuel Gratzl for his contributions made during all phases of the project as well as to the implementation of the prototype system. We would also like to thank Nils Gehlenborg for giving domain specific input on the biomedical usage scenario and for providing feedback on the prototype implementation and its potential value for domain experts. This work was funded by the Austrian Science Fund as part of the _VisOnFire_ project (FWF P27975-NBL) and the Austrian Ministry for Transport, Innovation and Technology (BMVIT) under the ICT of the future program via the VALiD project (FFG 845598)}.