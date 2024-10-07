# So Many Tools!  

There are lots of tools in each genome browser. We encourage you to explore them with your own data. Here are some highlights:
* **[Ensembl's Variant Effect Predictor (Ve!p)](https://useast.ensembl.org/info/docs/tools/vep/index.html)** - upload a VCF and get an overview of the numbers and consequences of variants (based on known annotations) in your file. It doesn't replace more in-depth analyses using more robust computational tools, but it is a good way to see a graphical summary of your variants, so you can make decisions on how to clean up your VCF files, if necessary.
  * The rough equivalent in UCSC is the Variant Annotation Integrator, which gives you more options on what to do with your files, but is less user-friendly. It gives you files in Variant Effect Predictor format, though, so you can take those files over to Ensembl for visualization.
* **LiftOver** tools - allow you to convert between older genomes (eg. hg19) to current (eg. hg38) or other builds. Availalbe from the **Tools** menu in both browsers.  
* **Gene Interactions** from UCSC. More of a fun tool, it provides simple network maps of your chosen gene. Also available from the Tools menu.
* **Linkage Disquilibrium Calculator** from Ensembl. Requires a little bit of pre-work to prepare files with lists of regions or variants, but allows you to select any number of populations from 1000 Genomes or GGVP data. Available from Ensembl's Tools menu.

There are more tools from each site, and more are being created all the time.


# Uploading Your Own Data  
Both sites allow you to upload your own experimental data. There isn't time to demonstrate this for this session, but we have included instructions on how to prepare data for upload to UCSC using Globus. Those instructions, created by Rad