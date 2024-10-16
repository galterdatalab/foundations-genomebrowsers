# Accessing the browsers
[UCSC Genome Browser](https://genome.ucsc.edu/cgi-bin/hgGateway)  

[Ensembl Genome Browser](https://useast.ensembl.org/index.html)  
      This links to the "US East" browser mirror. If you are in a different part of the world, you can start at https://www.ensembl.org/index.html, and you should be taken to the best mirror for your location.

# Exercise 1 - Finding your gene  
We're going to use the gene ACE2 for this example.  
ACE2 is the angiotensin converting enzyme 2. It is not as well annotated as some other genes (my example gene in the UCSC Genome Browser GalterGuide is ACE, which is well-annotated). However, this enzyme has received more interest in recent years, since it is the functional receptor for the spike glycoprotein of the SARS-CoV and SARS-CoV-2 (COVID-19) viruses.  
## Searching for your gene, navigating, and finding essential information in UCSC  
* Go to the [UCSC Genome Browser](https://genome.ucsc.edu/cgi-bin/hgGateway) home page
* Click on Genome Browser in the top dark blue menu, or in the main page (top link)
* If you've used the browser (fairly) recently, please hover over the Genome Browser menu and click "Reset User Settings". This will give you a "clean" start.
* Select your species and genome assembly
    * By default, the browser goes to the human genome, which we will use, but there are MANY other curated genomes available. The current annotated assembly is GRCh38/hg38, but you can select older builds, and there is an in-progress 2022 build, as well.
* In the Position/Search Term box, type ACE2. As you type, the browser will suggest results for you.
  * If you click on the ACE2 result, you will go right into the browser.
  * If you instead click on "GO", you will be taken to a list of possible matches from a number of gene annotation databases.
  * Clicking on the suggested result is the most efficient method, IF you are certain this is the gene you want.  
* Take some time figuring out: What chromosome and strand is the gene coded on? How can you change the order of the tracks? How do you zoom? How do you find links to the DNA sequence? Protein? Structure? Is it easy to find how many transcripts the gene encodes?


## Doing the same thing in Ensembl  
* Go to the [Ensembl Genome Browser](https://useast.ensembl.org/index.html) home page
* Notice that you don't have the option to select the build. If you look in the "Favorite Genomes" section under the search box, though, you can see a link to the GRCh37 build.
    *  Side note: if you click on "Human" in this section, you will go to a page where you can find all kinds of specific downloads and tasks.
* In the blue search region, use the dropdown menu to select Human, search for ACE2 and hit "GO".
* The results here will show you all the human hits from your search. Note that there is a left side menu with catogories for gene, transcript, variation, etc. The top hit is usually the one you're looking for. There is also a small graphic of "Best gene match" to the right.
* Click on the ACE2 gene result and you'll be taken into the browser view.
* If you have used this browser recently and have different tracks, please find "Reset Configuration" in the blue-grey bar at the top or bottom of the browser graphic, and reset the defaults.
    * Note that this looks VERY different from UCSC. There are more text elements, with the browser view in the bottom.
    * The left menu is very helpful. It will take you to specific features with their own detailed options.
    * Also note the top of the view: there are two tabs, one for location and one for gene. If you click on a transcript, for example, you will open another tab. This is nice if you want to get back to where you started, but some people might find multiple tabs distracting. 
* Take some time figuring out: What chromosome and strand is the gene coded on? How can you change the order of the tracks? How do you zoom? How do you find links to the DNA sequence? Protein? Structure? Is it easy to find how many transcripts the gene encodes?  


## Clicking on things in the browser graphic  
When you click on a feature in each browser, varying things will happen.  
* When you click (left click) on an individual feature in UCSC (like a transcript, a SNP a regulatory feature), _in most cases_, an "Item detail" page will open over the browser, displaying more information on the feature and links to supporting information.  
  * Sometimes, in very feature-heavy tracks, clicking on what looks like a single feature will expand the track to "full", then you can click on a feature to see the information page.  
  * In other tracks (layered methylation or acetylation, for example) clicking on the feature will open the configuration page for the track.  
  * You will get used to the different results from clicking on different track types.    
* When you click (left click) on an individual feature in Ensembl, a small popup will open, giving information on the feature and links to sequence and information.
* When you right click on a feature in UCSC, a feature-specific popup will open, allowing you to change the view, highlight, get DNA for the feature.
* When you right click on a feature in Ensembl, nothing happens in the genome browser (instead you will get a web browser popup menu).
* **In UCSC only**: When you click on a track title (above the track), the track will condense down to dense view.
* **In Ensembl only**: When you click on the track title (to the left of the track), you will get a small configuration menu where you can highlight, hide, get a link AND, if there is a cogwheel icon, you can change the density of the track's display. 
* **In UCSC only**: When you click on the vertical bar to the left of any track, it will open the configuration menu for that track, where you can change the view, features shown, etc.  

### To drag the genome graphic:  
* **In UCSC**: Click anywhere NOT on a feature and drag left or right.
* **In Ensembl**: Shift + click anywhere NOT on a feature and drag left or right.
