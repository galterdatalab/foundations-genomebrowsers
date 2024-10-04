# Exercise 3 - Variant Tracks  
Variants are numerous, especially in the annotated human genome, so genome browser variant tracks can be overloaded with short variants. The two genome browsers vary in how they show (or don't show) variants in the browser graphic.  

## Variants in UCSC  
By default, UCSC shows the current dbSNP release in the dense view. If you expand this view to "full", you will see why depicting variants graphically can be challenging.  
* Some variants can be found in the Phenotype and Literature section instead of Variation - these are clinically assessed or disease-associated variants in databases like ClinVar and COSMIC, along with other sources.
* The dbSNP variants, when you click on them, open the Item Detail page, with useful information on the variant and frequencies from several reporting databases.
* These tracks are straightforward. There's very little that you need to do to find discover the data. You can always look for more variant data in the Track Hubs, too.

## Variants in Ensembl - "Too much data to display"    
Unlike UCSC, Ensembl does **not** show human variants in the graphic view for the Gene tab. They have determined that there are too many variants to show effectively in the graphic view, so if you click on "Variant Image" in the left menu while in the Gene tab, you will receive a message that Ensembl has retired the variant image for human variants.  
* However, if you click on a transcript from the transcript table, you can view variants in the variant image for that transcript. The graphical image is still quite hard to interpret.
* You can also select tracks of variant data using the "Configure this page" menu from the left or the "Add/remove tracks" button at the top of bottom of the browser view (like we did with regulatory tracks).
  * There are many sources of variant data, much like there are for UCSC, but they are found within the configuration page (again similar to what we did with regulation). 
  * When you add tracks from the configuration page, they **will** show in the browser graphic.  
* One of my favorite features in Ensembl is the Variant Table (available from the left menu).
  * In the Gene tab, the variant table will show only exonic variants. Like the variant image, there are too many variants at the gene level to be included in the table, so only exonic variants are shown.
  * You can see all variants in the variant table for an individual transcript, though (including intronic and 3' and 5' UTRs).  
  * The variant table allows you to filter from several data sources: SIFT score, PolyPhen score, consequence, MAF, and "other" which includes evidence, clinical significance, source, and other data features.
