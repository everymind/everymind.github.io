---
title: "Comparative Neuroscience Studies at the Brighton Sea Life Center"
permalink: /projects/comparative-neuroscience-brighton/
excerpt: "An exhibit/citizen science experiment hosted at Sea Life Brighton, July-August 2017."
author: Danbee Kim
header:
  image: /assets/images/Brighton_header_small.png
categories:
  - projects
tags:
  - Sea Life Brighton
---

During the summer of 2017, Sea Life Brighton will host an interactive citizen science exhibit that engages Sea Life guests with current neuroscience research trying to understand general principles of _intelligent behaviour_ by comparing the nervous systems of many different animal species. 

{% for project in site.projects %}
  {% if project == "ComparativeNeuroscience-Brighton"}
    {% for post in project}
    {% include archive-single.html type="grid" %} 
  {% endif %}
{% endfor %} 

## Acknowledgements

| Production Staff |                   |                                                              |
| ------           | ------            | ------                                                       |
| [Danbee Kim](mailto:danbee@alum.mit.edu) | Project Co-Lead | Sainsbury Wellcome Centre for Neural Circuits and Behaviour  |
| Kerry Perkins    | Project Co-Lead   | Sea Life Brighton                                     |
| Clive Ramble     | Design and Fabrication of outer casing for eye-tracking station | Sol Vin  |
| Hazel Grenade    | Design and Fabrication of outer casing for eye-tracking station | Sol Vin  |
| Goncalo Lopes    | Eyetracking Software | Sainsbury Wellcome Centre for Neural Circuits and Behaviour |
| Dario Quinones   | Eyetracking Hardware | Sainsbury Wellcome Centre for Neural Circuits and Behaviour |
| [Fedor Lischenko](mailto:Fedor-LN@ya.ru) | Video content contributor | Russian Federal Research Institute of Fisheries and Oceanography |
| Ian Blaney       | Stores and Logistics Manager | Sainsbury Wellcome Centre for Neural Circuits and Behaviour |
| Karen Fergus     | Administrative assistance | Sainsbury Wellcome Centre for Neural Circuits and Behaviour |
| Martyn Stopps    | Prototyping assistance | Sainsbury Wellcome Centre for Neural Circuits and Behaviour |
| Robb Barrett     | Prototyping assistance | Sainsbury Wellcome Centre for Neural Circuits and Behaviour |

Many additional thanks to <br/>
Adam Kampff (Sainsbury Wellcome Centre for Neural Circuits and Behaviour) for support and mentorship throughout this project; <br/> 
Helen Fitzgerald (Sea Life Brighton) for granting approval to host this exhibit at Sea Life Brighton; <br/>
and Daniel Osorio (Sussex University) for initiating the collaboration with Sea Life Brighton.
