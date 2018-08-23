# Vion_Identification
Peaks deconvolution &amp; identifications

The input CVSV document (C:\Users\nkummer1\switchdrive\MA\Vion\Data Treatment\R\20180821_Demo\20180821_Demo) is exported from Progenesis (use for the alignement). The following column have to be exported: Compound, m/z, Retention time (min), CCS (angstrom^2), Identifications, Maximum Abundance et Raw abundance. 
Remarques: The column called "Neutral mass (Da)" exported from Progenesis as to be deleted before running the code (otherwise it generate errors due to missing values). 

Three files are created, Data2, data3 and data4. The document data4 will be use to creat heatmaps. 

## TTo use the code, change the name of the CSV file in the beggining of the code. 
