![text about an image](logo-iac.png) ![text about an image](ljmu_logo.png)

# Ground-breaking rapid robotic follow-up with a 4-metre successor to the Liverpool Telescope

Welcome to the new webpage for the Liverpool New Robotic Telescope; a collaboration between Liverpool John Moores University and the Instituto de Astrofísica de Canarias. The [design team](team.md), established in early 2018, are in the process of finalising the engineering and science requirements of the facility.

The [news](news.md) page details the latest project developments including workshops, meetings, partners and outreach.

As part of the Astrophysics Research Institute at LJMU, we are dedicated to pushing our [equity and diversity](ed.md) initiatives and creating a welcoming working environment and partnership. 

![text about an image](NRTW_group_2_400.png) 

docs_list_title: ACME Documentation
docs:

- title: Introduction
  url: introduction.html

- title: Configuration
  url: configuration.html

- title: Deployment
  url: deployment.html

<h2>{{ site.data.samplelist.docs_list_title }}</h2>
<ul>
   {% for item in site.data.samplelist.docs %}
      <li><a href="{{ item.url }}" alt="{{ item.title }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>
