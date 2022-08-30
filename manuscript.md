---
title: 'satuRn: Scalable analysis of differential transcript usage for bulk and single-cell RNA-sequencing applications'
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2022-08-30'
author-meta:
- Jeroen Gilis
- Kristoffer Vitting-Seerup
- Koen Van den Berge
- Lieven Clement
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="satuRn: Scalable analysis of differential transcript usage for bulk and single-cell RNA-sequencing applications" />
  <meta name="citation_title" content="satuRn: Scalable analysis of differential transcript usage for bulk and single-cell RNA-sequencing applications" />
  <meta property="og:title" content="satuRn: Scalable analysis of differential transcript usage for bulk and single-cell RNA-sequencing applications" />
  <meta property="twitter:title" content="satuRn: Scalable analysis of differential transcript usage for bulk and single-cell RNA-sequencing applications" />
  <meta name="dc.date" content="2022-08-30" />
  <meta name="citation_publication_date" content="2022-08-30" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Jeroen Gilis" />
  <meta name="citation_author_institution" content="Department of Applied Mathematics, Computer science and Statistics, Ghent University" />
  <meta name="citation_author_orcid" content="0000-0001-8415-0943" />
  <meta name="twitter:creator" content="@GilisJeroen" />
  <meta name="citation_author" content="Kristoffer Vitting-Seerup" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="citation_author" content="Koen Van den Berge" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="citation_author" content="Lieven Clement" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <link rel="canonical" href="https://jgilis.github.io/satuRn_md/" />
  <meta property="og:url" content="https://jgilis.github.io/satuRn_md/" />
  <meta property="twitter:url" content="https://jgilis.github.io/satuRn_md/" />
  <meta name="citation_fulltext_html_url" content="https://jgilis.github.io/satuRn_md/" />
  <meta name="citation_pdf_url" content="https://jgilis.github.io/satuRn_md/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://jgilis.github.io/satuRn_md/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://jgilis.github.io/satuRn_md/v/271942615dc79ca200fd81395403a65a56d532d4/" />
  <meta name="manubot_html_url_versioned" content="https://jgilis.github.io/satuRn_md/v/271942615dc79ca200fd81395403a65a56d532d4/" />
  <meta name="manubot_pdf_url_versioned" content="https://jgilis.github.io/satuRn_md/v/271942615dc79ca200fd81395403a65a56d532d4/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://jgilis.github.io/satuRn_md/v/271942615dc79ca200fd81395403a65a56d532d4/))
was automatically generated
from [jgilis/satuRn_md@2719426](https://github.com/jgilis/satuRn_md/tree/271942615dc79ca200fd81395403a65a56d532d4)
on August 30, 2022.
</em></small>

## Authors



+ **Jeroen Gilis**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-8415-0943](https://orcid.org/0000-0001-8415-0943)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [jgilis](https://github.com/jgilis)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [GilisJeroen](https://twitter.com/GilisJeroen)<br>
  <small>
     Department of Applied Mathematics, Computer science and Statistics, Ghent University
     · Funded by FWO
  </small>

+ **Kristoffer Vitting-Seerup**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [kvittingseerup](https://github.com/kvittingseerup)<br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>

+ **Koen Van den Berge**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [koenvandenberge](https://github.com/koenvandenberge)<br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>

+ **Lieven Clement**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [statOmics](https://github.com/statOmics)<br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/jgilis/satuRn_md/issues)

:::


## Abstract {.page_break_before}

Alternative splicing produces multiple functional transcripts from a single gene. Dysregulation of splicing is known to be associated with disease and as a hallmark of cancer. Existing tools for differential transcript usage (DTU) analysis either lack in performance, cannot account for complex experimental designs or do not scale to massive single-cell transcriptome sequencing (scRNA-seq) datasets. We introduce satuRn, a fast and flexible quasi-binomial generalized linear modelling framework that is on par with the best performing DTU methods from the bulk RNA-seq realm, while providing good false discovery rate control, addressing complex experimental designs, and scaling to scRNA-seq applications.

## Introduction

Studying differential expression (DE) is one of the key tasks in the downstream analysis of RNA-seq data. Typically, DE analyses identify expression changes on the gene level. However, the widespread adoption of expression quantification through pseudo-alignment,1,2 which enables fast and accurate quantification of expression at the transcript level, has effectively paved the way for transcript-level analyses. Here, we specifically address differential transcript usage (DTU) analysis, one type of transcript-level analysis that studies the change in relative usage of transcripts/isoforms within the same gene. DTU analysis holds great potential: previous research has shown that most multi-exon human genes are subject to alternative splicing and can thus produce a variety of functionally different isoforms from the same genomic locus.3–5 The dysregulation of this splicing process has been reported extensively as a cause for disease,6–9 including several neurological diseases such as frontotemporal dementia, Parkinsonism and spinal muscular atrophy, and is a well- known hallmark of cancer.10

In this context, full-length single-cell RNA-Seq (scRNA-seq) technologies such as Smart-Seq211 and Smart-Seq312 hold the promise to further increase the resolution of DTU analysis from bulk RNA-seq data towards the single-cell level, where differences in transcript usage are expected to occur naturally between cell types. However, only a few bespoke DTU methods have been developed for scRNA-seq data and they lack biological interpretation. Indeed, methods specifically developed for scRNA-seq data are either restricted to exon/event level13,14 analysis (e.g. pinpointing exons involved in splicing events), or they can only pinpoint DTU genes without unveiling the actual transcripts that are involved.15 Interestingly, many DTU methods for bulk RNA-seq do provide inference at the transcript level and their performance has already been extensively profiled in benchmark studies.16–18 Based on a subset of the simulated RNA- seq dataset from Love et al.18 (see Methods), we show the performance of six DTU tools; DEXSeq,19 DoubleExpSeq,20 DRIMSeq,21 edgeR diffSplice,22 limma diffSplice23 and NBSplice24 (Figure 1A). DEXSeq and DoubleExpSeq have a higher performance than the other methods. In addition, we observe that most methods, and DRIMSeq in particular, fail to control the false discovery rate (FDR) at its nominal level, which is in line with previous reports.16–18

## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
