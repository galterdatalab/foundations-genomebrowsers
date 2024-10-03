# Adding tracks to the view  
It's easy to add new tracks to each browser's view. The most difficult part is knowing which tracks have the information you want to see.  
  
## Adding regulation tracks in UCSC  
There are several regulatory regions available in the set tracks for UCSC. Data from the ENCODE project with ENCODE cCREs and layered H3K27Ac are shown by default. You can add more, though.  
* Go down to the set of track selection panels, and under Regulatory, click on the name "ENCODE Regulation".  
  * Any set of tracks that has a folder next to it will have multiple tracks that may or may not show in the browser's default view. By clicking on the track name, you can add more.  
* Add the methylation tracks (and any others you're interested in), then click the "Refresh" button in the blue ribbon header for the track set.  The browser will refresh.
* However, you may not like the look of the display, or you may want to see if there are more track options.  
  * Click on the vertical bar on the left side of the track, and try changing the Overlay Method, Track Height, and change the scaling to auto-scale.  
  * If you don't see the regulatory feature you're interested in, click on the text link "Broad Histone" in the Description on this configuration page. It will open a chart of all the features and cell lines you can add, (though some regulatory features are not available for all cell lines).
  * You can always de-select any of the cell types from the bottom list.  
  * When you're done, hit the "Submit" button near the top of the selection panel.  

If you want to see more tracks that aren't in the default selection section, go to the "My Data" menu at the very top of the page and click on "Track Hubs". Under the "Public Hubs" tab, you can search for and load more tracks. **NOTE**: There are also instructions on this page on the "Connected Hubs" and "Hub Development" tabs that guide you through creating your own public hubs to share with collaborators (or the world). 


## Adding regulation tracks in Ensembl  
A few regulatory features are shown by default in Ensembl. There is a Regulatory Build track displayed under the transcripts in the browser graphic. It displays promoters (and their flanks), enhancers, CTCF binding sites, open chromatin, and TF binding sites. There is a color legend under the browser graphic.  

If you click on "Regulation" in the left menu, your window will zoom out by default, showing a much larger view with many genes and more regulation features packed in.  

Regulation tracks are a little more tricky to add in Ensembl. They don't display featured tracks in selectable menus in the browser view, like UCSC. Instead, you must click on "Configure this page" in the left side menu OR click on "Add/remove tracks" just above the browser graphic.  
* Configure this Page is where you can add any kind of tracks that are available in Ensembl. We're going to concentrate just on the Regulation tracks for now.  
* "DNA Methylation" is somewhat disappointing in this section. It only includes Reduced Representation Bisulphite Sequencing (RRBS) for several cell lines. Some cell lines may have many features, while others may have none. 
* Instead, to find more options, click on the menu for "Features by Cell/Tissue". Here you will find MANY available regulatory features.  
  * Use the search box in the Cell/Tissue tab to search for your tissue or cell line of interest and click the check boxes next to your choices.  
  * Click on the Experiments tab and choose the regulatory features you want from the Histone, Open Chromatin, and Transcription Factors internal tabs. There is a search box in Experiments to help you find what you want faster, too.  
  * When you've selected what you want to see, click the green "Configure track display" button to preview what you will add, then click the green "View tracks" button. The configuration page will close and the browser will refresh.
  * Notice that there is a link to the Trackhub Registry in a yellow banner on ANY feature configuration page. You can try adding tracks from these hubs, too.
 * **Note**: Clicking on the header for any of the track sets (e.g. "Variation") will allow you to select options in all the categories in that heading, instead of setting them one-by-one. If you use this method, to add the features, click the checkmark in the upper right corner of the configuration page. 
