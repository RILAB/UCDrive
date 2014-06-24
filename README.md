# UCDrive

Undergrad Centromere Drive

Here's a start at the paper.  We should start writing ASAP.  It's in latex, which will require a bit of a learning curve.  Please start working on your methods sections, and start adding in results as appropriate (GWAS, CENTC abundance, etc.).  It's all on github, so just commit and push your changes and we should be fine.  I recommend using [latexian](http://tacosw.com/latexian/) or [texshop](http://pages.uoregon.edu/koch/texshop/) for editing LateX.

## Folders and Files


### Folder:scripts

		A place for scripts used during the project to be placed for reference further down the road.


####	File:CRM2_BWA_Jiao.sh (slurm script, CentC abundance)

		Misleading title, originally used BWA mem and SAMtools to check for CRM2 abundance, but modified to estimate CentC abundance across Jiao Lines.

####	File:cDNA_Jiao_abun.sh (slurm script, cDNA abundance)

		Uses BWA mem and SAMtools to estimate cDNA abundance from [Zea_mays.AGPv3.22.cdna.all.fa](http://plants.ensembl.org/Zea_mays/Info/Index) to give a relative comparison in genome size across the lines. Again this script was modified from the other BWA using script.

### File:Abundance.md

	Links for Rscripts and graphs produced using R Markdown from RStudio and published on Rpubs. CentC abundance and cDNA abundance used to estimate centromere size and relative genome size respectively.

