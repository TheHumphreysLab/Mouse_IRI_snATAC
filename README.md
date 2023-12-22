# **Dynamic remodeling of cell type-specific epigenetic landscape driving failed repair in acute kidney injury**
__Yoshiharu Muto, Eryn E. Dixon, Yasuhiro Yoshimura, Nicolas Ledru, Haojia Wu and Benjamin D. Humphreys__  

Welcome to our GitHub repository!  
Here you will find preprocessing scripts for our project where we integrate paired snRNAseq and snATACseq from mouse kidneys with ischemia-reperfusion injury along time course. Please contact the corresponding author, Dr. Benjamin Humphreys, with questions or comments.  
<br/>
Thanks,  
Benjamin D. Humphreys, Yoshiharu Muto

Visit the Humphrey's lab website:   
www.humphreyslab.com  
<br/>
Check out our interactive datasets with Kidney Interactive mulTiomics (KIT):  
http://humphreyslab.com/SingleCell/
<br/><br/>
Find us on Twitter: 
<br/>
  <a href="https://twitter.com/HumphreysLab?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-show-count="false"> @HumphreysLab</a>
<br/><br/>

**preprocessing workflow**  

1. Preprocessing of individual snATAC-seq data

2. Identification of doublets with AMULET

3. Integration of snATAC-seq data

4. Label transfer from snRNA-seq data to snATAC-seq data and filtering out nuclei with low-confident prediciton 

5. Integration / clustering and celltype annotation by gene activities

6. Filtering out nuclei with inconsistent annotation between prediction vs gene activiies (potential remaining doublets and low-QC nuclei)

7. Final integration / clustering and celltype annotation
