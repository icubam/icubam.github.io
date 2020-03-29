---
layout: page
title: More info
permalink: /about/
---

ICUBAM provides real-time monitoring of intensive care unit (ICU) bed
availability in French hospitals. Data is directly obtained from doctors
working inside ICU by sending them SMS with a HTTP link to a form that they can
fill in 15 seconds.

This software stack is currently being used by the ICU system in Eastern France
to help manage the COVID crisis.

The project was co-built by ICU Doctors from CHRU Nancy/Université de Loraine
and engineers from INRIA & Polytechnique. It was fleshed out live during the
Covid crisis in Eastern France to answer an urgent need for finding available
ICU beds in a saturated and deteriorating situation. At the time of writing, 5
engineers are working full-time, 7 days a week, on the project, in direct
contact with the team of ICU doctors on the ground.

Most of the data handled by ICUBAM is less than 1 hour old. ICUBAM integrates
with the ministry of health's back-end system for sending data upstream to
inform authorities and retrieving data to synchronise with other data sources.

This software is open-source and made available
[on GitHub](https://github.com/icubam/icubam).

It will soon be released as a one-click deployable docker container.

You can contact the team for deployment information or general experience
sharing at contact@icubam.net.
