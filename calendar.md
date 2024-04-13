---
layout: page
title: Calendar
nav_order: 2
description: Listing of course modules and topics.
---
# Calendar

This page gives an overview of the in-class sessions, homework assignments and reading material. See the [About](about.md) page for more information about the unit.

%Required reading is noted in the third column below, where "HOS" and "ADK" refer to the online HOS textbook and [textbook](https://doi.org/10.1017/9781108991889) by Armen der Kiureghian, respectively. For the HOS book, "HOS-PD" and "HOS-EVA" refer to the parts with chapters on Probabilistic Design and Extreme Value Analysis topics.

{% for module in site.modules %}
{{ module }}
{% endfor %}
