# Data Downloads 
Just as valuable as the browser view -- maybe more valuable -- are the options for data download from the sources used in the browsers. Each browser has a special way to download data.  

## UCSC's Table Browser  
UCSC's source data download tool is called the Table Browser. It is accessible from the Tools menu.  
* When you enter the Table Browser from a genome browser region showing your feature of interest, the Table Browser will automatically load the genomic coordinates of the window you were viewing. This is convenient. This shows under the **Define region of interest** section. You can also define specific regions, paste a list of identifiers, or download data from the whole genome (NOT recommended for human data).
* In the **Select dataset** section:
  * The Clade, Genome and Assembly will also auto-populate from your browser session.
  * Select your Group, Track, and Table.
    * The Group is basically the grouping of selectable tracks you see under the genome graphic view in the Genome Browser, with Track and Table specific to data from those groups.
  * For our example, were going to keep it VERY simple: we're going to download coordinates for all the transcripts from ACE2, showing transcript start and stop sites, exon numbers, and protein information (if available).
    * **Group**: Genes and Gene Predictions
    * **Track**: GENCODE v46
    * **Table**: knownGene
* **Optional**: in the **Optional: Subset, combine, compare with another track**, you can filter by many characteristics to only retrieve data from the tracks that match your criteria, or you can create an **Intersection**, where the table will show data from the "Select dataset" result from the previous page that overlaps with a second dataset you define on this page.
  * Many people want to see all the fields from both datasets when combining two sets of track features. If this is your goal, there's a tool called **Data Integrator**, which can be found under the **Tools** menu in the top menu bar.
  * For variants specifically, if you want to get a file showing where variants overlap transcripts, use the **Variant Annotation Integrator** (also available in the Tools menu), or read instructions on getting variant data at [https://genome.ucsc.edu/FAQ/FAQdownloads.html#snp](https://genome.ucsc.edu/FAQ/FAQdownloads.html#snp)
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
    * You can instead choose other types of data to download such as **Sequences**, **Variation** (Germline or Somatic), **Homologues**, and **Structures**
    * **Variation** choices are useful, since not all variants are shown in the genome browser variant image or variant table, so if you are interested in intronic (or any non-exonic) variants, this is the place to get them.
* **Optional**: choose a second database to pull data from, intersecting with the first database. This is a good way to get all of the interval data (gene information) along with relevant variants for your selected region/genes, by using a variant database as your second database.
* To get a preview of your number of results, use the **Count** tab at the top of the left menu to get a unique count (though the results may have many more rows than the count says: the count is a count of unique genes in your dataset, while the rows will show features for each transcript).
* To download a file, click on the **Results** tab at the top of the left menu. You'll see a preview of your data's first *n* rows, with options to download a file immediately in one of a few formats, or put in your email address to receive the file via email (if it's a particularly large query).


# Image Downloads  

## Download an image from UCSC  
Before you download an image from UCSC, you might want to simplify it. You can do this by going to the **Genome Browser** menu and selecting **Configure**.
* Here you can remove the blue vertical lines, resize things, change the font, hide the track controls, and many other visual options.
* When you're done, click the **Submit** button at the top of the configuration page.
* This downloads a PDF which you can edit with your chosen PDF editing software.

## Download an image from Ensembl  
Images from any browser view in Ensembl can be configured and downloaded from the **Export Image** button in the menu bar just above or below the browser graphic.  
* You don't have as many options to remove browser lines or resize / change font, but you can export in more different file types than you can in UCSC.
* Click the **Download** button in the image panel.
