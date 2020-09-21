---
layout: post
title: "C-F Bond Activation by FLPs"
date: 2020-01-05 16:25:06 -0700
comments: false
categories: Highlights

---
<div class="post-categories">
  {% if post %}
    {% assign categories = post.categories %}
  {% else %}
    {% assign categories = page.categories %}
  {% endif %}
  {% for category in categories %}
  Category: {{category}}
  {% unless forloop.last %}&nbsp;{% endunless %}
  {% endfor %}
</div>

# Introduction
In their recent [article](https://doi.org/10.1039/C9DT04588K), Stephan _et al._ describe how a proazaphosphatrane P(MeNCH<sub>2</sub>CH<sub>2</sub>)<sub>3</sub>N, can react with PhC(O)CF<sub>3</sub>. They first use this proazaphosphatrane , also known as "Verkade’s base", as an actual Lewis base and then test it in presence of a Lewis acid, with which it forms a Frustrated Lewis pair (FLP).

# Background: FLPs in C-F Activation
Stephan has previously shown that P/B FLP reacts with C-F bond containing compounds to
break it heterolytically.  
<br/>
![FLPs_background](https://dl.dropboxusercontent.com/s/bthvv4euey4pt22/FLPs_background3.png?dl=0)  

# When the Lewis Base is used Without a Lewis Acid Present: No FLP
The Lewis base acts a very strong base at P and It reacts first by defluorinating the alpha fluorine of the first molecule of 
PHC(O)CF<sub>3</sub> to form a salt. Then the formed anion PHC(O)CF<sub>2</sub><sup>-</sup> attacks the second molecule of PHC(O)CF<sub>3</sub>. It just looks like an Aldol condensation but with fluorines instead of hydrogens. This intermediate could be
further verified by derivatizing it, by reacting it with R<sub>3</sub>SiCl.
<br/>    
![FLP_as_base](https://dl.dropboxusercontent.com/s/ark8707nx0uwnoy/FLP_as_base5.jpg?dl=0){:height="100%" width="800px"}  

# The Reactivity of P(MeNCH<sub>2</sub>CH<sub>2</sub>)<sub>3</sub>N When BPh<sub>3</sub> Is Present: FLP

Monitored by computational methods, in the presence of BPh<sub>3</sub>, proazaphosphatrane reversibly forms an FLP. This changes the reactivity of proazaphosphatrane
completely and it will act as a nucelophile for PHC(O)CF<sub>3</sub> to form __Int1/BPh<sub>3</sub>__. This intermediate
later does a C-P to C-O migration (rearrangement) and finally BPh<sub>3</sub> will abstract an F<sup>-</sup> to form __2__.  
<br/>
![FLP_nu_attack](https://dl.dropboxusercontent.com/s/nh9sf8eu3wwt5uq/FLP_nu_attack.png?dl=0){:height="100%" width="800px"}  

# Conclusions

> FLPs are able to intercept reaction intermediates.

The paper also later describes how using FLPs, the resulting enolates of acetophenone can be incorporated into a phosphonium cation or a borate anion. This is promising for accessing divergent synthetic solutions using FLPs.  
<br/>
![diverg](https://dl.dropboxusercontent.com/s/kbpkj7isrh9iicu/diverg.jpeg?dl=0){:height="100%" width="800px"}  
<br/>

The author is the founder of FLPs. This paper shows the vast potential 
of these species. especially in one of the most challenging bond activations (C-F bond). Looking at the 
DFT calculated reaction profile, the breaking of the C-F bond is the rate-determining step and it is safe to say that 
an actual C-F bond activation is happening. Again, it is interesting that the oxygen of carbonyl does not hinder the functionality of the FLP by acting as a Lewis base. Indeed, this is has been studied in details by Warren Piers in
[B(C<sub>6</sub>F<sub>5</sub>)<sub>3</sub> catalyzed hydrosilation of carbonyl functions ](https://doi.org/10.1021/jo991828a).

