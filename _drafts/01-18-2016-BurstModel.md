---
layout: post
title:  "BURST: A model for value delivery"
author: Joseph Cruz
date:   2016-01-08 18:00:00 -0500
---
{% digraph BURST Model %}
fontname=arial
fontsize=18
label=""
labelloc=top
rankdir=LR
ranksep=.5
bgcolor=none
node [shape=circle, fixedsize=true, width=1, fontname=arial]
edge [fontsize=12]
b [label="Benefit"]
u [label="User\nAction"]
r [label="Result"]
s [label="Scenario"]
t [label="Test"]
b->u [label="Justifies"]
u->r [label="Triggers"]
r->s [label="Explained by"]
s->t [label="Verified by"]
{% enddigraph %}
The BURST model, illustrated above, assures features are valuable and verifiable. The model is easy to follow. Benefits justify user actions. User actions trigger one or more results. Scenarios explain when specific results should be expected. Repeatable test cases verify scenarios behave as expected. Miss just one element and value cannot be assured.

TODO