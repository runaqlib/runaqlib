---
layout: page
title: my work
permalink: /mywork
description: projects, presentations, libguides, static sites, and my research.
nav: true
nav_order: 3
display_categories: [work, fun]
horizontal: false
---



## Summer 2023

- [NYU Digital Humanities](https://digitalhumanities.nyu.edu/funding/grad-fellowships/) Student Summer Fellowship
I created [Runakunaq Bibliotecanku](https://runaqlib.hosting.nyu.edu), a static site using CollectionBuilder + Jekyll as an open resource to access texts about the Andes, Quechua Language, and Worldwide Indigenous study.

## Spring 2023

- Appiani, G., Pereira, M., Warsco, A., Arones, D. (2023, April 1). _Preserving and Celebrating Quechua in NYC_ [Conference presentation]. Quechua Alliance Annual Meeting, Harvard University, Cambridge, MA, United States. [https://thequechua.org/event-program/](https://thequechua.org/event-program/)
- Center for Latin American and Caribbean Studies [Quechua Library Catalog Airtable](https://airtable.com/shr8oNRurEIZzfgIz) 

## Fall 2022
- [Indigenous Latin America Libguide](https://liupalmer.libguides.com/c.php?g=1288128&p=9459377)


## Undergraduate Work

- In 2018, I presented a paper at the Leadership Alliance Mellon Initiative Research Symposium titled “Bein’ Lum: Language as a Legitimizing Force for an Illegitimate People,” exploring the Lumbee English dialect as a community-creating and identification tactic for the federally-unrecognized Lumbee tribe of North Carolina. 

## GitHub Repositories

{% if site.data.repositories.github_repos %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}