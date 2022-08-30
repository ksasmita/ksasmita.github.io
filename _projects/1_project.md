---
layout: page
title: Measuring event segmentation
description: An investigation into the stability of event boundary agreement across groups
img: 
importance: 1
category: phd
---
[[paper]](/assets/pdf/Sasmita%20and%20Swallow%20-%202022%20-%20Measuring%20event%20segmentation%20An%20investigation%20int.pdf) [[code]](https://github.com/ksasmita/esMethods) [[poster]](https://www.youtube.com/watch?v=-CTJDCYuYDE)

#### **Background**
To study how people spontaneously divide continuous experience into distinct events (*event segmentation*), we usually ask participants to watch a movie and simultaneously mark the boundaries between events (**segmentation task**). 

Performance in this task is typically quantified as a measure of **segmentation agreement** - how well do participants' boundary markings overlap with each other. Though segmentation agreement can be relatively high, the segmentation task is still naturally subjective & ambiguous. Thus, what kind of information is reflected in segmentation agreement values is unclear. 

#### **Questions** 
In this paper we ask whether measures (new and existing; Fig 1) that quantify segmentation agreement can:
1. Capture responses that are non-random and movie-specific.
2. Stabilize over increasing sample size. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/esMethod_Fig1.jpg" title="esMethods_Fig1" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fig 1. Illustration (A) and description (B) of group- and individual-level agreement measures. 
</div>

#### **Method**
First, we bootstrapped segmentation task performance collected *in-lab* and *online* to create samples of varying sizes (Fig 2.A). Then, for each agreement measures, we calculated agreement values using *true, randomized, or mismatched* data to test the sensitivity and specificity of each agreement measure (Fig 2.B). We then tested the ability of each agreement measure in capturing *non-random* and *movie-specific* responses, the minimum sample size required to observe these properties and the minimum sample size required to observe *stable performance* (Fig 2.C). 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/esMethod_Fig2.jpg" title="esMethods_Fig2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fig 2. Study design and data processing (A), calculation of varying types of segmentation agreement (B), and statistical approaches (C). 
</div>

#### **Main Findings**
For almost all measures, we found: 
1. When considering multiple samples, non-random & movie-specific agreement can be captured with performance from as little as 2 people. 
2. BUT, for a single sample to reliably capture signal-driven behavior, larger size is needed (6-18; Table 1).
3. Agreement improved with increasing sample size and eventually stabilized (Fig 3) when the sample is large enough (10-16 people).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/esMethod_T1.jpg" title="esMethods_Table1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/esMethod_Fig3.jpg" title="esMethods_Fig3" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Table 1. Practical characteristics of all agreement measures.   Fig 3. Representative result from agreement index. 
</div>

#### **Practical takeaways**
1. Segmentation task remains a powerful tool to capture how people spontaneously divide experience 
2. But as our data shows, it has it's limits 
3. So we should be mindful when using one group's segmentation to infer another group's boundary placement

**Moving forward, we suggest that future studies using the segmentation task should consider:**
1. Type of agreement to measure (group/ individual level).
2. Mode and medium of collected data (e.g., online/ in-lab, commercial/ everyday movie). 
3. Sample size needed to capture reliable, stable, & signal driven performance.
