# Data Downloads 
Just as valuable as the browser view -- maybe more valuable -- are the options for data download from the sources used in the browsers. Each browser has a special way to download data.  

## UCSC's Table Browser  
UCSC's source data download tool is called the Table Browser. It is accessible from the Tools menu.  
* When you enter the Table Browser from a genome browser region showing your feature of interest, the Table Browser will automatically load the genomic coordinates of the window you were viewing. This is convenient. This shows under the **Region** section. You can also define specific regions, paste a list of identifiers, or download data from the whole genome (NOT recommended for human data).
* In the **Select dataset** section:
  * The Clade, Genome and Assembly will also auto-populate from your browser session.
  * Select your Group, Track, and Table.
    * The Group is basically the grouping of selectable tracks you see under the genome graphic view in the Genome Browser, with Track and Table specific to data from those groups.
  * For our example, were going to keep it VERY simple: we're going to download coordinates for all the transcripts from ACE2, showing transcript start and stop sites, exon numbers, and protein information (if available).
    * **Group**: Genes and Gene Predictions
    * **Track**: GENCODE v46
    * **Table**: knownGene
  * Under **Retrieve and display data**,
    * Choose whether you want all fields, selected fields, and optional GTF or BED formats. You can also send data directly to Galaxy (the public web version) or GREAT. For this example, we'll just keep all fields.
    * Give it a filename, or leave it blank to see the output in the web browser.
    * Choose tsv or csv  
    * Plain text or .zip (recommended if you are downloading a lot of dat on several regions or identifiers). 
