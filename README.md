# Introduction to evolutionary genomics - LEG/UM5

## Course (editions)

1st. Edition [EG1-LEG/UM5](http://www.fsr.ac.ma/content/g%C3%A9nomique) @ Faculté des Sciences Rabat, June 10-14, 2019.

<!-- <img src="docs/pics/Participantes_curso_intro2phyloinfo_UNLP_2-6Julio2018.jpg" /> -->


***
 
## Presentation

### About the instructor
Hi, I'm [Pablo Vinuesa](http://www.ccg.unam.mx/~vinuesa/) and work as a professor @
[Center for Genome Sciences](http://www.ccg.unam.mx) from the 
[Universidad Nacional Aut&oacute;noma de M&eacute;xico - UNAM](http://www.unam.mx/).

Mi [research lines](http://www.ccg.unam.mx/~vinuesa/research.html) 
integrate genomics and bioinformatics with molecular genetics and biology to study the evolution and raise
of opportunistic nosocomial pathogens from environmental bacteria.

### On teaching materials
They are distributed from this [GitHub repository](https://github.com/vinuesa/Evolutionary_Genomics1-LEG-UM5) and include the slides, exercises and data that will be used in the course. These materials were compiled them from those I've developed over the years to teach diverse courses at the 
 [Universidad Nacional Aut&oacute;noma de M&eacute;xico - UNAM](https://www.unam.mx/). The current version of the materials is written in Spanish. Future versions will be progressively translated to English.

### Licencia y t&eacute;rminos de uso
I'm releaseing these materials [**EG-LEG-UM5**](https://github.com/vinuesa/Evolutionary_Genomics1-LEG-UM5) to the public domain through this [GitHub repository]((https://github.com/vinuesa/Evolutionary_Genomics1-LEG-UM5) under a [**No Comercial Creative Commons 4.0 License**](https://creativecommons.org/licenses/by-nc/4.0/) 

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 

#### Cloning of the repository
If you have [git](https://git-scm.com/) installed on your machine, you can clone the repo by issuing the following command:

   <code>git clone https://github.com/vinuesa/Evolutionary_Genomics1-LEG-UM5.git</code>

On [ubuntu](https://www.ubuntu.com/) (and other Linux) machines it is very easy to install git: 

  <code>sudo apt install git</code>



<!--
### ¿Horario y lugar de impartici&oacute;n de las sesiones?
Las clases se imparten en el sal&oacute;n de c&oacute;mputo del Instituto de Biotecnolog&iacute;a 
de 9 a 18 hrs. Algunas sesines te&oacute;ricas esperamos poder impartirlas en el auditorio.


<img src="docs/pics/intro2phyloinfo_aula_UNLP_2-6Julio2018.jpg" />

-->

### Aims, structure and overview of the course
Each chapter has an introductory section describing the key concepts underlying the diverse bioinformatics and evolutionary gentics topics under discussion, followed by one or more hands-on practical sessions. The course will walk you through the basics of homology searching on local machines (formatting of sequence databases for BLAST searches), multiple sequence alignment and phylogenetic inference under the maximum-likelihood and Bayesian optimality criteria, progressing towards microbial pan-genome analysis and phylogenomics. 

#### Monday 10. 
- Basic concepts in evolutionary biology and phylogenetics (theory)
- Introduction to Linux (computer lab)

#### Tuesday 11. 
- BLAST searching from the command line (computer lab)
- Multiple sequence alignment (computer lab)
- Introduction to phylogenetics, gene trees and species trees (theory)

#### Wednesday 12. 
- Substitution models and phylogenetic inference under the maximum likelihood criterion (theory)
- **Research seminar** by [Pablo Vinuesa](http://www.ccg.unam.mx/~vinuesa/): The evolution of resistance and virulence in multidrug-resistant opportunistic pathogens: a phylogenomic approach.
- Ajuste de modelos e inferencia de filogenias de máxima verosimilitud (computer lab)

#### Jueves 13. 
- Bayesian phylogenetics (theory and computer lab)
- Discussion with students and Faculty, on research projects

#### Viernes 14.
- Computing homologous gene families from genomic data (theory)
- Pan-genome analyses with GET_HOMOLOGUES (computer lab)
- Inferring genome phylogenies from core- and pan-genomes (theory)
- Estimating genome phylogenies with GET_PHYLOMARKERS (computer lab)


### Software:
To follow the course practicals, you will need to install the following software on your laptop/computer:
- [GET_HOMOLOGUES](http://eead-csic-compbio)
- [GET_PHYLOMARKERS](https://github.com/vinuesa/)
- [Seaview (visor-editor de alineamientos y más)](http://pbil.univ-lyon1.fr/)
- [jModelTest2](https://github.com/ddarriba/)
- [FigTree (para visualizar y editar árboles)](http://tree.bio.ed.ac.uk/)
- [MrBayes](http://mrbayes.sourceforge)

## Detailed syllabus, slides, hands-on tutorials and data

### Theme 1: Basic concepts in microbial evolutionary genomics
- [presentación - pdf](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema1_conceptos_basicos_evolucion/Teoria1_conceptos_básicos_de_filoinformática_y_diversidad_microbiana.pdf)


### Theme 2: Introduction to GNU/Linux
Work in genomics is mostly performed on UNIX or GNU/Linux servers. It is therefore essential to work proficiently in these environments.
Therfore:

- all practical sessions will be run using GNU/Linux as the operating system
- we'll start the course by learning basic Linux commands and Bash programming

#### Biocomputing on GNU/Linux machines
- [presentaci&oacute;n - PDF](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/intro2linux/intro_al_biocomputo_con_Linux.pdf)

#### Computer lab 1. First contact with the GNU/Linux computing environment
- [pr&aacute;ctica1 - html](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/intro2linux/)
- [pr&aacute;ctica1 - pdf](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/intro2linux/working_with_linux_commands.pdf)
- [pr&aacute;ctica1 - tabla_comandos](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/intro2linux/linux_commands.tab)

#### Computer lab 2. Fetching FASTA sequences from GenBank with ENTREZ parsing of files using the Linux filtering toolbox
- [pr&aacute;ctica2 - html](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/practica2_parseo_fastas/)
- [pr&aacute;ctica2 - pdf](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/practica2_parseo_fastas/ejercicio_parseo_fastas_ENTREZ.pdf)
- [pr&aacute;ctica2 - fasta](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/practica2_parseo_fastas/data/recA_Bradyrhizobium_vinuesa.fa)


<!--

### Tema 2: Búsqueda de homólogos mediante BLAST: teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema2_BLAST/Tema2_BLAST_OVERVIEW.pdf)
- [pr&aacute;ctica1 - comandos](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema2_BLAST/data/running_and_parsing_BLAST_from_the_cmmd_line.commands)
- [pr&aacute;ctica1 - 16S_4blastN.tgz ](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema2_BLAST/data/16S_4blastN.tgz)
- [pr&aacute;ctica1 - gene_discovery_and_annotation_using_blastx.tgz](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema2_BLAST/data/gene_discovery_and_annotation_using_blastx.tgz)

### Tema 3: Alineamientos múltiples: teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema3_alineamientos_multiples/Tema3_alineamientos_multiples.pdf)
- [pr&aacute;ctica1 - tgz](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema3_alineamientos_multiples/data/practicas_aln_multiples.tgz)


### Tema 4: Introducción a los métodos filogenéticos y modelado paramétrico de evolución de secuencias nucleotídicas: teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema4_modelos_y_maxima_verosimilitud/Tema4_intro_a_la_filogenetica_y_modelos_de_sustitucion.pdf)

### Tema 5: Máxima verosimilitud: estima de parámetros y selección de models - teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema4_modelos_y_maxima_verosimilitud/Tema5_maxima_verosimilitud_y_seleccion_de_modelos.pdf)
- [pr&aacute;ctica1 - tgz](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema4_modelos_y_maxima_verosimilitud/data/practicas_MV_y_seleccion_modelos.tgz)


### Tema 6: Introducción a la pangenómica microbiana con [GET_HOMOLOGUES](https://github.com/eead-csic-compbio/get_homologues) - teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema5_get_hom_get_phy/introduccion_a_la_pangenomica_microbiana_UNLP_5Jul18.pdf)
- [pr&aacute;ctica1 - tgz](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema5_get_hom_get_phy/data/get_hom.tgz)
- [tutorial - GET_HOMOLOGUES/GET_PHYLOMARKERS - docker](https://vinuesa.github.io/get_phylomarkers/#get_phylomarkers-tutorial)
- [start_docker - script](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema5_get_hom_get_phy/data/start_docker.sh)

### Tema 7: Introducción a la filogenómica microbiana con [GET_PHYLOMARKERS](https://github.com/vinuesa/get_phylomarkers) - teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema5_get_hom_get_phy/introduccion_a_la_filogenomica_microbiana_UNLP_5Jul18.pdf)
- [paper GET_PHYLO - pdf](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema5_get_hom_get_phy/data/get_phylo/Vinuesa_GET_PHYLOMARKERS_FrontMicro2018.pdf)
- [manual - GET_PHYLOMARKERS](https://vinuesa.github.io/get_phylomarkers/#get_phylomarkers-manual)
- [tutorial - GET_PHYLOMARKERS](https://vinuesa.github.io/get_phylomarkers/#get_phylomarkers-tutorial)


### Tema 8: Inferencia bayesiana de filogenias con [MrBayes](http://mrbayes.sourceforge.net/index.php) - teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema6_inferencia_bayesiana/inferencia_bayesiana_con_MrBayes.pdf)
- [pr&aacute;ctica1 - tgz](https://vinuesa.github.io/Evolutionary_Genomics1-LEG-UM5/tema6_inferencia_bayesiana/data/MrBayes.tgz)


<!--


#### Pr&aacute;ctica 3. Introducci&oacute;n a la inferencia filogen&oacute;mica usando GET_PHYLOMARKERS
- [pr&aacute;ctica1 - html](https://vinuesa.github.io/get_phylomarkers/)

-->

