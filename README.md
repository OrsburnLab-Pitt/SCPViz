
Welcome to the new home of SCP Viz - A universal vizualization platform for single protein analysis in single cell proteomics data


<img width="755" height="651" alt="scpviz-icon" src="https://github.com/user-attachments/assets/19c56797-1025-4898-a2e4-bbc092f31bcc" />

Just want to get running with SCP Viz? Here is a tutorial video for an early version - new ones coming soon. https://youtu.be/eK5RtNQMviY

Don't want to download a weird R file from the internet? Run SCP Viz on the amazing Pitt HPC here! https://shiny.crc.pitt.edu/scpviz/

If you do use it please cite this preprint that we are updating now that we feel the software is ready with V1.1 onward. https://pubmed.ncbi.nlm.nih.gov/37693496/

Single Cell Proteomics by mass spectrometry is an exciting and emerging field of research that has yet to take a final form. You can use many mass spectrometers and you can use any of the over 1,000 LCMS data analysis platforms to process your data. The one constant right now is that when you've got hundreds of cells it is very difficult to see what each single protein is doing. And this is where SCP Viz comes in.

SCP Viz is simple and lightweight and it just plots your target single molecule of interest across as many cells as you want. 
Proteomics data? Sure. Peptide level proteomics data? That as well. Post-translational modifications? Absolutely? 
Once this was flexible enough to work for most major LCMS based proteomics datasets, it was flexible for just about anything else. In the upcoming paper we'll show how single cell transcriptomics and proteomics of the same cells treated with the same drug can all be evaluated here to understand how a small molecule inhibitor is working. 

Now with major updates where we literally just took every cool idea the SCP community has had about looking at these data and we added them to our GUI.

Pick a protein like (Like a Histone, maybe H4, thank you Michael Lanz, et al., JPR 2023) and use that to normalize your data? Sure! 
Want fine tuned control over the number of iterations in your normalized T-SNEs or U-MAPs, but don't want to use the nice R code from Cedars or from Schoof Lab? We put it in here as well.

Major update for Ben because he's pretty sure he's still reviewing 1 in every 3 SCP papers is a new front page that summarizes any study where they make their processed data easily available. Did the authors get 5,000 proteins across their study and that's the number they want you to remember? Are you curious about how many proteins or peptides they got per cell on average? And whether there were just 10 cells out of 200 that were AMAZING? Just load their FragPipe, DIA-NN, Proteome Discoverer, SpectroNaut, etc., transformed or not, into SCP Viz and then get a summary of that study! 
<img width="1035" height="901" alt="Screenshot 2026-04-17 150426" src="https://github.com/user-attachments/assets/381c4988-f7e7-47bc-9b75-aa995e2a5cb3" />


Most importantly, SCP Viz 1.1 now allows the rapid identification of a subpopulation of cells that are interesting. Do you have a cluster of cells in your PCA or T-SNE that are unique? Highlight them, give them a new name like "Weird cells" and then compare those weird cells to the other cells or cell populations in your study using the Volcano plot tab. They might be the cells that failed that you just don't want to think about... But if they aren't you may have discovered an entirely new phenotype or cell type! This functionality extends to individual proteins as well. 
<img width="1026" height="914" alt="Screenshot 2026-04-17 151823" src="https://github.com/user-attachments/assets/5ac6dbc5-29a1-4680-bd6a-edd362fde568" />

The example that started this whole project was that some single cells weren't making less KRAS in response to KRASG12D inhibition. https://pubs.acs.org/doi/full/10.1021/acs.jproteome.3c00212

You can go into the bar plot and just start highlighting the cells - at a protein or peptide level - that aren't responding the right way - and now you can add them to a new population.
BOOM - you've got a new group of cells that you can compare to the others to find out why they're special. 

Updated paper and tutorial stuff coming soon. 
