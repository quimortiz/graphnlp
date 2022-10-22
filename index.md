---
layout: page
title: Graph-NLP Planner
description: J. Ortiz-Haro, E. Karpas, M. Katz and M. Toussaint 
background: '/img/Screenshot from 2022-02-28 14-59-16-small.png'
---

<style>
.mydiv {

  text-align: justify;
  text-justify: inter-word;

}
</style>

Project webpage of the paper:

<div class="mydiv">
J. Ortiz-Haro, E. Karpas, M. Katz and M. Toussaint (2022). <b>A Conflict-driven Interface between Symbolic Planning and Nonlinear Constraint Solving</b>. <i>IEEE Robotics and Automation Letters (RA-L).</i>
</div>

<!-- Paper Preprint (8 pages) <a href="{{site.baseurl}}/assets/root.pdf">PDF</a> --> 

<!-- Appendix (4 pages) <a href="{{site.baseurl}}/assets/root.pdf">PDF</a> --> 


Appendix <a href="{{site.baseurl}}/assets/appendix.pdf">PDF</a> 


(**Recommended**) Extended Version (Paper + Appendix) <a href="{{site.baseurl}}/assets/root.pdf">PDF</a> 


<!-- ## Overview -->


### Supplementary Video 

Duration: 3 min 20 s

{% include youtubePlayer.html id="CEQUv09xIHs" %}


### Showcase: All real-world experiments 

Duration: 2 min 10 s

{% include youtubePlayer.html id="I8ZcgJUdF9Q" %}

## Real-world experiments


<p style="margin:0 0;">Metrics:</p>
* **Time**: computational time (in seconds) to generate a solution (plan of tasks and motions)
* **N**: number of symbolic actions of the found solution

#### Building a Hanoi Tower

|          | N | Time (s) |
|----------|:-----:|:------:|
| Side to middle | 12  | 9.4   |
| Side to side | 24   | 25.1    |
| Middle to side | 12   | 9.2    |
{:.custom-table}


##### a) Hanoi - Side to side 

{% include youtubePlayer.html id="7G1aFCUKmPM" %}

##### b) Hanoi - Side to middle

{% include youtubePlayer.html id="NZ_ixp9lEyE"  %}

##### c) Hanoi - Middle to side

{% include youtubePlayer.html id="qHv50xRosuc" %}

#### Building a Tower with obstacles


|          | N | Time (s) |
|----------|:-----:|:------:|
| Middle | 12  | 5.5    |
| Transfer | 16   | 27.2    |
| Middle-tower | 12   | 8.9    |
| Side-small | 8   | 8.1 |
{:.custom-table}



##### a) Obstacles - Middle

{% include youtubePlayer.html id="gZhjujhQBAo" %}

##### b) Obstacles - Transfer

{% include youtubePlayer.html id="_N4rXUonWEU" %}


##### c) Obstacles - Middle-tower

{% include youtubePlayer.html id="mAPHRygMG7k" %}

##### d) Obstacles - Side-small

{% include youtubePlayer.html id="gbkJwm9M9ts" %}


## Building a Tower 

|          | N | Time (s) |
|----------|-----|------|
| Middle | 12  | 2.9    |
| Side | 12   | 5.7    |
| Transfer | 24   | 37.1     |
| Transfer-small | 12   | 6.9    |
{:.custom-table}

##### a) Tower - Middle

{% include youtubePlayer.html id="tp4oZEFd02s" %}

##### b) Tower - Side

{% include youtubePlayer.html id="hqFB2xtRZ2Y" %}

##### c) Tower - Transfer
 
{% include youtubePlayer.html id="izvQasYEBls" %}


##### d) Tower - Transfer - Small
{% include youtubePlayer.html id="uoGfSIX_Qso" %}

