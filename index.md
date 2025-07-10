---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

Hyperlinks to each of the demos are listed below.

## Demos

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

## Sample Prompts for immersion experience

#### [Public Sector Senior Officials ](https://microsoftlearning.github.io/MS-4021-WWPS-Copilot-Immersion-Experience/Instructions/Prompts/1-Senior-Official-Prompts.html)

#### [Public Sector Human Resources (HR) Professionals](https://microsoftlearning.github.io/MS-4021-WWPS-Copilot-Immersion-Experience/Instructions/Prompts/2-HR-Prompts.html)

#### [Public Sector IT Professionals](https://microsoftlearning.github.io/MS-4021-WWPS-Copilot-Immersion-Experience/Instructions/Prompts/3-IT-Prompts.html)

#### [Public Sector Procurement Professionals](https://microsoftlearning.github.io/MS-4021-WWPS-Copilot-Immersion-Experience/Instructions/Prompts/4-Procurement-Prompts.html)

#### [Public Sector Finance Professionals](https://microsoftlearning.github.io/MS-4021-WWPS-Copilot-Immersion-Experience/Instructions/Prompts/5-Finance-Prompts.html)

#### [Public Sector Cybersecurity](https://microsoftlearning.github.io/MS-4021-WWPS-Copilot-Immersion-Experience/Instructions/Prompts/6-Cybersecurity.html)
