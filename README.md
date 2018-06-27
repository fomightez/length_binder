[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/fomightez/length_binder/master?filepath=index.ipynb)

# length_binder
Use Jupyter environment to look at protein length for various organisms. Served via Binder system.

Click the `launch binder` badge anywhere on this page to launch an active Jupyter session where the length data is plotted.

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/fomightez/length_binder/master?filepath=index.ipynb)

Data sources
------------

The sources for protein length data:

- *Saccharomyces cerevisiae* S288C (yeast) - At the time of running the code it is interactively collected from YeastMine using Intermine's webservice to retrieve length of all proteins, which is based on [this template](https://yeastmine.yeastgenome.org/yeastmine/template.do?name=Organism_Protein&scope=all).

![Intermine](https://raw.githubusercontent.com/intermine/design-materials/master/logos/intermine/InterMine.svg)

- Arabidopsis thaliana (thale cress) - the repo includes a file obtained June 2018 from [Genome Annotation at TAIR](https://www.arabidopsis.org/portals/genAnnotation/gene_structural_annotation/annotation_data.jsp). Specifically, if you follow the link for [the TAIR ftp site](ftp://ftp.arabidopsis.org/home/tair/Genes/TAIR9_genome_release/) from the text under 'Data availability', it leads to page that features [TAIR9_sequences](ftp://ftp.arabidopsis.org/home/tair/Genes/TAIR9_genome_release/) among the list that you can click on to get to a page where you can download [TAIR9_pep_20090619](ftp://ftp.arabidopsis.org/home/tair/Genes/TAIR9_genome_release/TAIR9_sequences/TAIR9_pep_20090619).


- Drosophila melanogaster (fruit fly) - the repo includes a file obtained June 2018 from [Proteomes - Drosophila melanogaster (Fruit fly)](https://www.uniprot.org/proteomes/UP000000803) by clicking on the 'Download' tab under `Components` in middle of the page.

