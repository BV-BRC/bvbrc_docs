===================
Flute Experiment 3
===================

Comprehensive Essentiality Analysis of the Mycobacterium tuberculosis Genome via Saturating Transposon Mutagenesis
==================================================================================================================

**Publication:** `PMC5241402 <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5241402/>`_

For decades, identifying the regions of a bacterial chromosome that are
necessary for viability has relied on mapping integration sites in
libraries of random transposon mutants to find loci that are unable to
sustain insertion. To date, these studies have analyzed subsaturated
libraries, necessitating the application of statistical methods to
estimate the likelihood that a gap in transposon coverage is the result
of biological selection and not the stochasticity of insertion. As a
result, the essentiality of many genomic features, particularly small
ones, could not be reliably assessed. We sought to overcome this
limitation by creating a completely saturated transposon library in
*Mycobacterium tuberculosis*. In assessing the composition of this
highly saturated library by deep sequencing, we discovered that a
previously unknown sequence bias of the *Himar1* element rendered
approximately 9% of potential TA dinucleotide insertion sites less
permissible for insertion. We used a hidden Markov model of essentiality
that accounted for this unanticipated bias, allowing us to confidently
evaluate the essentiality of features that contained as few as 2 TA
sites, including open reading frames (ORF), experimentally identified
noncoding RNAs, methylation sites, and promoters. In addition, several
essential regions that did not correspond to known features were
identified, suggesting uncharacterized functions that are necessary for
growth. This work provides an authoritative catalog of essential regions
of the *M. tuberculosis* genome and a statistical framework for applying
saturating mutagenesis to other bacteria.

The following file provides the insertion counts at TA sites (merged
over 14 replicates) in .wig format (the reference sequence for the
coordinates was
??`NC_000962.3 <https://www.ncbi.nlm.nih.gov/protein/NC_000962.3>`__).

`14_replicates_combined.wig <ftp://ftp.patricbrc.org/BRC_Mirrors/FLUTE/Experiment_3/14_replicates_combined.wig>`__

The following Excel file provides a spreadsheet with essentiality calls
for each ORF, performed using the HMM in Transit. The categories are:

-  essential (ES)
-  essential domain (ESD)
-  growth defect (GD)
-  nonessential (NE)
-  growth advantage (GA)
-  uncertain (for short empty genes)

`mBio-Table-S3.xlsx <ftp://ftp.patricbrc.org/BRC_Mirrors/FLUTE/Experiment_3/mBio-Table-S3.xlsx>`__

This experiement also identified 65 sRNAs. The spreadsheet below gives
coordinates (relative to the H37Rv sequence determined by the Broad
Institute, NC_018143.1), strand, and name (according to a convention
proposed by Gyanu Lamichhane)

`inline-supplementary-material-8.xlsx <ftp://ftp.patricbrc.org/BRC_Mirrors/FLUTE/Experiment_3/inline-supplementary-material-8.xlsx>`__

The same list of sRNAs are also available from the genome page: `sRNA
Feature
Table <https://www.patricbrc.org/view/Genome/83332.111#view_tab=features&filter=and(eq(feature_type,misc_RNA),eq(annotation,PATRIC))>`__

.. raw:: html

   </div>

.. raw:: html

   </div>

.. raw:: html

   </div>
