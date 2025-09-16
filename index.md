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

#### [Executives](https://learn.microsoft.com/en-us/training/modules/envision-new-ideas-with-microsoft-365-copilot/) (Redirects to Microsoft Learn)

#### [Communications](https://mscpnerd.github.io/Learning/Instructions/Prompts/Communications-Prompts.html)

#### [HR](https://mscpnerd.github.io/Learning/Instructions/Prompts/HR-Prompts.html)

#### [Sales](https://mscpnerd.github.io/Learning/Instructions/Prompts/Sales-Prompts.html)

#### [IT](https://mscpnerd.github.io/Learning/Instructions/Prompts/IT-Prompts.html)

#### [Executive Assistant](https://mscpnerd.github.io/Learning/Instructions/Prompts/EA-Prompts.html)

#### [Business Manager](https://mscpnerd.github.io/Learning/Instructions/Prompts/Business-Manager-Prompts.html)

#### [Marketing](https://mscpnerd.github.io/Learning/Instructions/Prompts/Marketing-Prompts.html)

#### [Operations](https://mscpnerd.github.io/Learning/Instructions/Prompts/Operations-Prompts.html)

#### [Legal](https://mscpnerd.github.io/Learning/Instructions/Prompts/Legal-Prompts.html)

#### [Legal](https://mscpnerd.github.io/Learning/Instructions/Prompts/Legal-Prompts.html)

#### [Finance](https://mscpnerd.github.io/Learning/Instructions/Prompts/Finance-Prompts.html)

#### [Agents - Business Users](https://mscpnerd.github.io/Learning/Instructions/Prompts/EU-Agents.html)

#### [Agents - Executives](https://mscpnerd.github.io/Learning/Instructions/Prompts/Exec-Agents.html)

#### [Copilot Chat](https://mscpnerd.github.io/Learning/Instructions/Prompts/CopilotChat.html)

#### [Promptathon](https://MSCPnerd.github.io/Learning/Instructions/Prompts/CopilotChat.html)
