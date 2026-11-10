## Submitting libraries for sequencing 
We do most of our sequencing at Admera health. [1](https://www.admerahealth.com/genomics-and-bioinformatics-2/) <br>

**Submitting libraries to Admera**
- make sure that your library or pooled library is within the size range you want using the tapestation and is around 4nM using the Qubit and the nM conversion spreadsheet in box (https://stanford.app.box.com/file/418914060874)
- send 10 ul to the sequencing facility and keep the rest in the -20C freezer here
- fill out the admera health form with
> Delivery: Your name/Schumer Lab, 371 Jane Stanford Way, Schumer Lab Room 318, Stanford, CA 94305 <br>
> Bill to: Pamela Hung, 371 Jane Stanford Way, Stanford, CA 94305 <br> 
leave PO info blank (Pam has an account set up)
> Service: Copy description from quote you recieved
> kits: none (we have already done the library prep)
> Admera Health Quote no.: put in quote number
> data transfer method: ftp link (this is the fasted method, you can download data to oak using wget or cyberduck)
> special instructions: any info you want them to have, for example: these are three pools each to be ran on a separate lane
> library and pool ID columns should be the same for each pool (one row filled out per pool)
> library type as appropriate and sample type is usually tissue
> insert size including adapters: "total library size: x bp" using tapestation peak size
> Phix %: 1% is a standard spike-in amount. the purpose of Phix is to serve as a control to make sure the sequencing reaction worked. It can also help balance indixes. However, the more Phix you spike in, the less data you will get
> index sequences: one row for each library in a pool, Admera can use either the sequences or the reverse complements as long as you adjust the column heading to say which you are providing.
