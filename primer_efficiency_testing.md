- See primer design section for primer design. PCR fragments should be between 70-100bp. We usually design four sets of primers per gene of interest.
- Before testing primer efficiency you should use a regular PCR kit as instructed to make sure the primers amplify bands at the expected length.
- Check that peaks are clean and around the right size with the tapestation. See D1000 TapeStation Protocol.docx in the Protocols folder in Box or email smbanerj@stanford.edu for the protocol and all necessary reagents and consumables.
test efficiency of all primers that amplified as expected! It can be tricky to get a gene of interest and house-keeping pair that are efficient at the same annealing temperature. Or a gene of interest and a single-copy gene pair!
- Make sure it's okay to use the qPCR machine in the Fraser lab
- To test efficiency you need to run triplicates of each primer on at least 6 serial dilutions of cDNA or gDNA. If the DNA is too concentrated you will need to dilute it. 10ng/ul seems to be fine but less is also fine!
the recipe for one qPCR reaction is 5ul of iQ sybr green supermix + 3.4ul of water + 0.3ul of 10uM forward primer + 0.3ul of 10uM reverse primer + 1ul of DNA
- efa1 a swordtail housekeeping primer we have in the lab is efficient at 62C so I usually start there for annealing temperature. Use the cycle CFX_2stepAmp+meltcurve.prcl.
- Check in the biorad software that there is a single peak in the melt curve analysis for each primer. If there is more than one peak per primer, then the primer cannot be used at the this temperature.
- Use this template to calculate efficiency /Box/Schumer_lab_resources/Extractions_and_library_preps/qPCR data/efficiency_calculation_template. Make sure the standard deviation between triplicates is low. Exclude outliers from analysis.
- Efficiency should be between 0.9-1.10. If your efficiency is too high, increase your annealing temperature. If your efficiency is too low, decrease your annealing temperature.
Once you have a primer pair that are in an acceptable range of efficiency you can proceed to your samples of interest
