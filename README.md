# modcre
##################
# Configuration  #
##################

  -> Set configuration file parameters (i.e. ./scripts/config.ini).

##################
# Download files #
##################

PDB:
----
Go to "http://www.rcsb.org/pdb/search/advSearch.do?search=new".
Choose "All/Experimental Type/Molecule Type".
"Ignore" Experimental Method and select Molecule Type "Protein/NA complex".
Click on "Submit Query".
Click on "Download Results".
Uncheck all but "PDB".
Select Compresion Type "uncompressed".
Click on "Launch Download Application" and download "download_rcsb.jnlp".
Execute script and download files under "./pdb/all/".
Now, uncheck all but "Biological Assemblies".
Select Compresion Type "uncompressed".
Click on "Launch Download Application" and download "download_rcsb.jnlp".
Execute script and download files under "./pdb/biounits/".

<!-- Cis-BP:
-------
Go to "http://cisbp.ccbr.utoronto.ca/index.php".
Select "PBM" in By Evidence Type" and press "GO" button.
Add all TFs to cart and click on "View cart" in the left menu.
Click on "Download TFs in cart" and only leave a [check] on "TF info" and "Protein features", then
 click on "Download TFs in cart!".
Go to "http://cisbp.ccbr.utoronto.ca/entireDownload.php".
Click on "E-scores" and download "Escores.txt.zip".
Unzip downloaded files and you should obtain the following: "TF_Information.txt", "prot_seq.txt" a
nd "Escores.txt".

