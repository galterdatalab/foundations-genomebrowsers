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

## Ensembl data downloads and BioMart  
Since some sections in the Ensembl Genome Browser view are text-heavy, there is often an option to download those data fields as Excel. There is also an "Export data" button in the left menu.  However, to get the most data available from Ensembl, there is a tool called BioMart, which, like UCSC's Table Browser, allows you to control what fields you download and add more data than are availble from the browser interface.  
* Click on "BioMart" in the menu at the top of the page. (You might want to right click and open BioMart in a new tab in your browser, so you still have the genome browser avaiable in the original tab.)
* Unlike UCSC, you will not be taken to the region you've just been viewing in the genome browser. You'll have to start from scratch with BioMart.
* **Choose Database**: Choice of Ensembl Genes, Mouse Strains, Ensembl Variation and Ensembl Regulation. We'll choose Ensembl Genes for this example.
* **Choose Dataset**: You have the choice of MANY species' gene datasets, with the most popular in the top section.
* After you choose your dataset, you will notice the interface changes. There are now some menu options showing on the left.
* Here's where you select WHAT you want from WHERE, and what FIELDS to display.
  * **Filters**: Use **Region** or **Gene** to choose where you want data from.
  * Other filters allow you to select only genes associated with specific **Phenotypes**, clinically significant **Variants**, genes that only are associated with **Protein** IDs and more.
    * Be careful not to over-filter. If you set filters that are too stringent (for a very specific phenotype, for example), and your genes or region don't contain a lot of data for that filter, you will not retrieve very much. Also be careful not to under-filter. It's not recommended to select fields with a lot of data from an entire chromosome. 
  * **Attributes**: Here is where you specify the fields you want included in your data.
    * Make sure you choose enough fields that help you identify what you are looking at (eg. use both gene symbol and Ensembl gene ID).
    * **Features** are the most common fields describing gene start and stop, strand, exons, etc. Be aware that **the order you click the features is the order they will show in the downloaded file**.
    * You can instead choose other types of data to download such as **Sequences**, **Variation** (Germline or Somatic), Homology
