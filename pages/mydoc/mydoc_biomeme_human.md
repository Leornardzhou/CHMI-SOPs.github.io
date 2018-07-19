---
title: Portable QPCR
tags: [QPCR, mobile, diagnostics]
keywords:
summary: "Biomeme protocol for detection of Leishmania braziliensis, skin commensals and host pro-inflammatory gene expression from lesion swabs in human cases of cutaneous leishmaniasis "
sidebar: mydoc_sidebar
permalink: mydoc_biomeme.html
folder: mydoc
---

## Lesion swab
For each patient, two sterile swabs (provided by Biomeme) are held together and used to swab the inner border of lesion (encircled 20x).  This will be used for DNA targets (bacteria).  Repeat with two new swabs (20x), and use this second set of swabs for RNA targets (host genes).  

1. Immerse swabs intended for DNA in 1ml of a 1:1 mix of BLB from DNA kit (0.5ml) and water (BEB; 0.5ml), twirl in media for 1 min, discard swabs.
2. Immerse swabs intended for RNA in 1ml of BLB from the RNA kit, twirl in media for 1min, discard swabs
2. Attach standard lab 1cc syringe to Biomeme filter tip. Pump lysate up/down 10x, expel volume
3. Immediately move to **BPW** wash (1ml), pump up/down 1x, expel volume
4. Immediately move to **BWB** wash (1ml), pump up/down 1x, expel volume
5. Immediately move to **BDW** wash (1ml), pump up/down 1x, expel volume
6. Pump air up/down repeatedly 10x, discard syringe but **keep filter tip**
7. attach 25cc or 50cc syringe to the same filter tip.  Pump up and down with air vigorously to dry the column.
8. remove and discard the syringe.  Connect new Biomeme 'slip-tip' 1 cc syringe to the column and draw up 150 ul of Biomeme Elution Buffer (BEB).  Pump up/down 3x with BEB.
9. Expel the elution buffer into a final collection tube.  Typical elution volume is ~120ul.  We use 17ul of this DNA for any of the assays listed below, which means a single eluate is enough for at least 6 QPCR assays.

## Primers and probes

### Skin-resident microbes 
The primers and probes below are used for detection of *Staphylococcus aureus (Saur)*, *Streptococcus pyogenes (Spyo)* and *Leishmania braziliensis (Lbra)*

{% include note.html content="All of these targets are DNA, so be sure to use appropirate lysis buffer (BLB from DNA bulk extraction kit) and mastermix (LyoDNA)." %}

{% include note.html content="We prepare a standard curve for the *S. aureus* assay using genomic DNA provided by Biomeme.  Stock is ~100,000 *S. aureus* genomes per ul, and curve is 100000, 10000 and 1000 copies.  We prepare a similar standard curve from *L. braziliensis* promastigotes, with a stock that is also ~100,000 genome copies per ul.  When running a standard curve on the Two3 device, always put the tube containing the lowest amount of target in the center well.  This position is closest to the sensor, and therefore provides a bit more sensitivity."%}

* *Leishmania braziliensis* primer/probes are from [Weirather et al., 2011](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3209110/)
* *Streptococcus pyogenes* primer/probes were adapted from CDC [here](https://www.cdc.gov/streplab/protocols.html)
* *Staphylococcus aureus* primers and probes were provided by Biomeme Inc.


| name | Sequence (5' -> 3') |
|-------|--------|
| *Saur* fwd | provided by Biomeme |
| *Saur* rev | provided by Biomeme |
| *Saur* probe | provided by Biomeme |
| *Spyo* fwd | GCA CTC GCT ACT ATT TCT TAC CTC AA |
| *Spyo* rev | ATT ACT GGT TTC CAA GAC ATT GTG AC |
| *Spyo* probe | */56-FAM/*CCG CAA CTC */ZEN/* ATC AAG GAT TTC TGT TAC CA*/3IABkFQ/* |
| *Lbra* fwd | TGC TAT AAA ATC GTA CCA CCC GAC A |
| *Lbra* rev | AAA TGG CAT ACA GAA ACC CCG TTC |
| *Lbra* probe | */56-FAM/*GCC TCT GGG */ZEN/* TAG GGG CGT TCT GCA A*/3IABkFQ/* |


### Human transcripts
The primers and probes below are for the detection of host transcripts present in cellular material on recovered from the swab

{% include note.html content="All of these targets are mRNAs, so be sure to use appropirate lysis buffer (BLB from RNA bulk extraction kit) and mastermix (LyoRNA)." %}

{% include note.html content="The 18S assay is included as a positive extraction control.  The primers recognize an exon in the 18S gene, so there will be some signal from DNA in the reaction (the Biomeme RNA extraction isolates both RNA and DNA), however, given the large copy number for 18S transcripts, there should be much stronger signal for RNA."%}

| name | Sequence (5' -> 3') |
|-------|--------|
| hIL1B fwd | CAA AGG CGG CCA GGA TAT AA |
| hIL1B rev | CTA GGG ATT GAG TCC ACA TTC AG |
| hIL1B probe | */56-FAM/*AGA GCT GTA */ZEN/* CCC AGA GAG TCC TGT*/3IABkFQ/* |
| hGZMB fwd | GTA CCA TTG AGT TGT GCG TG |
| hGZMB rev | CAT GCC ATT GTT TCG TCC ATA G |
| hGZMB probe | */56-FAM/*CCT CCA GAG */ZEN/* TCC CCC TTA AAG GAA GT*/3IABkFQ/* 
| h18S (+ control) fwd | provided by Biomeme |
| h18S (+ control) rev | provided by Biomeme |
| h18S (+ control) probe | provided by Biomeme |



{% include links.html %}