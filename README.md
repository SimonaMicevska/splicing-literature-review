## Splicing literature review

| Method | Binary splicing events | Complex splicing events | Retained introns | 5' UTR length | 3' UTR length | Alternative first exon | Alternative last exon | RNA-seq input | Annotation input | RNA-seq reads used quantification | Interpretation | Link to publication | Publication date | Link to software | Last updated | Summary
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :-----: | :---: | :---: | :---: | :---: | :---: |
|Transcription events |
| Altrans | Known + novel | N/A | Known + novel | Known + novel | Known + novel | Known + novel | Known + novel | BAM alignment | GTF | junction reads | The majority (66%) of the signal that Altrans captures is due to exon skipping events followed by alternative 5' and 3' UTRs (15% and 11%, respectively) | 10.1016/j.ajhg.2015.09.004 | 01.10.2015 | https://omictools.com/altrans-tool | 2018 | After it is run, it is determined that in the presence of unannotated transcripts, Altrans performs better in quantifications |
| DEXSeq | Known | N/A | Known | Known | Known | Known | Known | BAM alignment | GTF | read coverage | The interpretation of the results of this method is straightforward when a single exon of a gene with many exons is called differentially used. However, if many exons within a gene are affected, the interpretation is more complex. For instance, consider a gene with two isoforms, a long one with n exons and a short one consisting of only the first n/2 exons. If an experimental condition increased the number of long transcripts at the expense of the short ones, without changing the total number, one might expect an analysis to indicate differential usage for the last n/2 exons. However, their method cannot distinguish this situation from one in which the gene is overall down-regulated, while the first n/2 exons are more strongly used. | 10.1101/gr.133744.111 | 22.10.2012 | http://bioconductor.org/packages/release/bioc/html/DEXSeq.html | 2018 | It detects exons that are subject to differential exon usage. |














