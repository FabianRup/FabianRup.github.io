---
title: Structural homologs DO NOT EXIST (you just mean something different) 
date: 2026-02-17
# links:
#   - type: site
#     url: https://github.com/pytorch/pytorch

image:
  caption: 'Image credit: Fabian Ruperti'
  focal_point: ""
  preview_only: false


tags:
  - conference
  - evolution
  - talk
---

This marks the end of my 2026 beginning-of-the-year conference marathon. This time, I talked about 'old' work that was [published](/publications/journal-article-2) during my PhD together with [Nikolaos Papadopoulos](https://zoology.univie.ac.at/people/scientific-staff/nikolaos-papadopoulos/), [Milot Mirdita](https://mirdita.de) and [Martin Steinegger](https://steineggerlab.com/en/authors/admin/). Back then, AlphaFold (predicting protein structures from sequence only) and Foldseek (searching for similar protein structures) *just* came out and we came up with a pipeline that used structural similarity (rather sequence similarity) to detect homologs for functional transfer. We called a pair of proteins that shared very similar structures **Morphologs**. 

And that brings me to an important point in all of this. If we don't have additional information other than two proteins that share a similar structure (especially over long evolutionary distances), it is not possible to determine if we are actually looking at homologs or not. However, in this work, we did find that most morphologs are indeed homologs (share a common ancestor) and that they share function over long evolutionary distances even in cases when sequence similarity doesn't suggest homology any more.

So, the last thing I did during the talk was to try to convince my audience that something like a *structural* or *sequence homolog* does not exist. Either a pair of proteins share a common ancestor (and are therefore homologs) or they don't. Sequence or structure similarity is just a quantitative measure for evidence for the hypothesis of ancestry. Makes sense?

<div class="grid grid-cols-1 md:grid-cols-3 gap-3 not-prose my-4">
  <a href="img1.jpeg"><img src="img1.jpeg" alt="Shot 1" class="rounded-lg"></a>
  <!-- add more as needed -->
</div>

<!--more-->
