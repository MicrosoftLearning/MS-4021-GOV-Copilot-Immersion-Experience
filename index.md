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

#### [Senior Officials](https://microsoftlearning.github.io/MS-4021-GOV-Copilot-Immersion-Experience/Instructions/Prompts/1-Senior-Official-Prompts.html)

#### [HR](https://microsoftlearning.github.io/MS-4021-GOV-Copilot-Immersion-Experience/Instructions/Prompts/2-HR-Prompts.html)

#### [IT](https://microsoftlearning.github.io/MS-4021-GOV-Copilot-Immersion-Experience/Instructions/Prompts/3-IT-Prompts.html)

#### [Procurment](https://microsoftlearning.github.io/MS-4021-GOV-Copilot-Immersion-Experience/Instructions/Prompts/4-Procurment-Prompts.html)

#### [Finance](https://microsoftlearning.github.io/MS-4021-GOV-Copilot-Immersion-Experience/Instructions/Prompts/5-Finance-Prompts.html)
