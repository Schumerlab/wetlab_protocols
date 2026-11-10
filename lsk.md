We follow the ONT Ligation Sequencing protocol, which can be found in Dropbox: 
```/Protocols/Nanopore/genomic-dna-by-ligation-sqk-lsk114-document-document-PromethION-en-GDE_9161_v114_revAC_24Sep2025-70.pdf```

We also incorporate these modifications in the protocol for optimal sequencing results: 

```
####################################
#### Modifying LSK Instructions ####
####################################

Protocol modifications based on Ligation sequencing DNA V14 (SQK-LSK114)(GDE_9161_v114_revAC_24Sep2025))

Modifications from Tris Dodge (Schumer Lab)
-Increase input DNA to 2-3ug (from 1ug)
-Shear HMW DNA with 26G needle 20x (see ONT_26Gneedle_shearing_protocol.txt protocol)
-Do not add DNA control sample (DCS)
-Wash with LFB instead of 80% ETOH
-Increase lengths of bead incubation steps to allow to come back fully into solution (sometimes up to 1hr)
-Substitute kit's AXP beads with BioDynami 10kb beads
-Elute final pellet in 33µL EB at 37ºC for ≥10 min
-Load all DNA on promethion flow cell

Modifications from Nathan Gamarra (Altemose Lab)
-Pass through HMW DNA 3-5X through a 1mL syringe with 26G needle
-Half volumes of all end-repair step components (same total amount of DNA) in the end repair step (done to save reagents)
-Do not bead purify end repaired DNA. Instead, dilute it up to 60µL with MQ water and use that as input for adapter ligation
-Extend adapter ligation to 30 minutes
-Bead purify as stated washing with LFB buffer
-Elute at 37ºC with 30µL EB for 5 minutes
-Load all DNA on promethion flow cell

```
