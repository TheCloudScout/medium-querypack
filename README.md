# Bring your investigation queries with you across multiple workspaces
## … by saving them inside a 'query pack'

## Medium Article

I wrote an article about this subject on Medium. Check it out for more background information about this repository:

https://medium.com/@koosg/bring-your-investigation-queries-with-you-across-multiple-workspaces-1ac43ded292c

## Overview

As a security analyst, responsible for performing triage as part of incident response, you're performing similar tasks quite regularly. Like checking a user by determining from where they logged on, how, and with what device as an example.

When you're using Microsoft Sentinel (and/or their Defender suite of products) you're probably getting quite familair with KQL to easily retrieve this information. And you've probably already collected a small arsenal of such investigation queries and saved them into the Log Analytics workspace for later use.

But what happens when you have to switch workspaces? All of your carefully saved queries are suddenly no longer available.
Larger enterprises tend to have multiple Sentinel workspaces to limit the amount of cross region traffic and the additional costs that come with it.

Please don't start duplicating your queries by saving them into every workspace you touch. To help with such tasks, Microsoft has you covered with query packs (preview). An Azure resource which helps you to centrally manage all of your queries and use them across all of your workspaces!
Query packs are not exclusive to Microsoft Sentinel-enabled workspaces. You can use them for all of your other Azure Monitor / Log Analytics workspaces as well.