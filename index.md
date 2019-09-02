---
layout: home
title: Home
---

# {{site.service_name}}

This page provides a single source of documentation relevant to the
{{site.service_name}} such as design documents, decision logs and discussions.

## ADRs

{% for adr in site.adrs %}

- [{{adr.title}}]({{adr.url | relative_url}})

{% endfor %}

## Designs

{% for design in site.designs %}

- [{{design.title}}]({{design.url | relative_url}})

{% endfor %}
