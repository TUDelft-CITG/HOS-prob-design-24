---
layout: page
title: Calendar
nav_order: 2
description: Listing of course modules and topics.
---
# Calendar

This page gives an overview of the in-class sessions, homework assignments and reading material. See the [About](about.md) page for more information about the unit.

{% for module in site.modules %}
{{ module }}
{% endfor %}
