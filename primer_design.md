# Schumer lab: Primer Design 
## Primer design 
Obtain the fasta file for your gene of interest

NCBI has a great tool for primer design called [Primer BLAST](https://www.ncbi.nlm.nih.gov/tools/primer-blast/). The parameters we usually change are target amplicon length and the RefSeq annotation organism (we use maculatus for all xiphophorous primers).

Target a self-complementarity <5 and 3' complementarity <3.

If you want your primers to amplify in hybrids or multiple species, align your selected primers sequences with the gene sequences of all species of interest to make sure the primer has no differences with any speices of interest. You can use [clustal omega online](https://www.ebi.ac.uk/jdispatcher/) to do this

You can also check for heterodimers and other forms of secondary structure using [IDT's oligoanalyzer](https://www.idtdna.com/pages/tools/oligoanalyzer)

Phusion polymerases have different primer-binding capabilities than Taq polymerases, and the buffer used creates higher Tm than Taq buffers. Thermo Fisher provides a [Tm calculator specific to Phusion reactions](https://www.thermofisher.com/us/en/home/brands/thermo-scientific/molecular-biology/molecular-biology-learning-center/molecular-biology-resource-library/thermo-scientific-web-tools/tm-calculator.html)
