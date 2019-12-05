<img src="https://bioconductor.org/images/logo_bioconductor.gif" alt="BiocLogo">

# BioC Asia 2019

5-6 December, 2019  
Charles Perkins Centre, Camperdown Campus of University of Sydney, NSW, Australia

## General Information

This year a large portion of the BioC Asia conference will be shared with AMSI's
[BioInfoSummer](https://bis.amsi.org.au/). 

Note that the annual [ABACBS conference](https://www.abacbs.org/conference2019/about),
this year joined with GIW, will be held the following week (9-11 of December) in Sydney.

## Registration

Registration for BioC Asia is \$60 for both days for students and \$120 for anyone else.

<span style="color:red">*Note that registration has closed.*</span>

## Location

The conference will be held at the [Charles Perkins Centre](https://sydney.edu.au/charles-perkins-centre/):

John Hopkins Drive, 
The University of Sydney,
Sydney, NSW 2006

## Code of Conduct

Please be aware that during this event you are expected to follow the 
[University of Sydney's code of conduct](http://sydney.edu.au/policies/showdoc.aspx?recnum=PDOC2011/215&RendNum=0).
**In particular, the BioC Asia conference aims to provide a supportive, collegial, and harassment-free environment. **

If someone makes you or anyone else feel unsafe or unwelcome, please report it 
as soon as possible. Harassment and other code of conduct violations reduce the 
value of our event for everyone. We want you to be happy at our event. People 
like you make our event a better place.

You can make a report either personally or anonymously. You can make an 
anonymous or non-anonymous report here: https://biocasia.wufoo.com/forms/z1ghma0t1gx3tja/. 
It is a free-form text box that will be forwarded to conference organizers.

We can’t follow up an anonymous report with you directly, but we will fully 
investigate it and take whatever action is necessary to prevent a recurrence.

You can make a personal report with any of the members of the conference 
committee: Peter Hickey, Saskia Freytag, Dario Strbenac and Stephen Pederson.

When taking a personal report, our staff will ensure you are safe and cannot 
be overheard. They may involve other event staff to ensure your report is 
managed properly. Once safe, we’ll ask you to tell us about what happened. This 
can be upsetting, but we’ll handle it as respectfully as possible, and you can 
bring someone to support you. You won’t be asked to confront anyone and we 
won’t tell anyone who you are.

Our team will be happy to help you! We value your attendance.


## Keynote Speakers

We are pleased to annouce three international keynote speakers:

<p float="center">
  <img src="images/helena.jpeg" width="200" title="Helena Crowell"/>
</p>

**Helena Crowell**: Helena earned her undergraduate degree at the Univeristy of Heidelberg in 
Biochemistry. She then went on to earn her Master's degree in Computational Biology & Bioinformatics 
at the ETH Zurich. She is currently a PhD candidate in Statistical Bioinformatics at the University of
Zurich.

Helena focuses on developing analysis frameworks for CyTOF data and differential discovery in scRNA-seq data. She is the author of a popular Bioconductor package providing tools for preprocessing and analysis of cytometry data.

<p float="center">
  <img src="images/martin_morgan.jpg" width="200" title="Martin Morgan"/> 
</p>

**Martin Morgan**: Martin earned his undergraduate and Master's degrees in Botany at the University of Toronto. Martin's PhD studies at the University of Chicago involved the evolutionary consequences of frequency-dependent selection, and of multilocus deleterious mutation. Martin is currently at the Roswell Park Comprehensive Cancer Center in Buffalo.

Martin leads the core team that maintains the Bioconductor project. He is the author of many Bioconductor packages and a renowned biostatistican.

<p float="center">
  <img src="images/elana.jpg" width="200" title="Elana Fertig"/>
</p>

**Elana Fertig**: Elana is an Associate Professor of Oncology at Johns Hopkins University. Prior to entering the field of computational cancer biology, Elana was a NASA research fellow in numerical weather prediction. 

Elana runs a hybrid computational and experimental lab in the systems biology of cancer and therapeutic response. Her computational methods blend mathematical modeling and artificial intelligence to determine the biomarkers and molecular mechanisms of therapeutic resistance from multi-platform genomics data. 

## Invited Speakers

**Joshua Ho**, The University of Hong Kong

**John Marioni**, The University of Cambridge

**Shila Ghazanfar**, The University of Cambridge

## Presentations

The conference will feature selected talks (15mins), lightning talks (5mins), and software demos (5mins).

<span style="color:red">*Abstract submission has closed.*</span>

## Workshops

There will be 9 workshops to be held on Thursday
and Friday. Participants can elect to attend 3. 

<span style="color:red">*Abstract submission has closed.*</span>

All workshops are open to BioInfoSummer participants. For 
the workshops please note that:

- All participants are expected to bring their own laptops
- All participants are expected to have followed the installation instructions (please
    check the materials for the workshops) 
- WiFi access will be through either eduroam or using a login
- Access to power sockets will be available so please bring your power adapter
- Please ensure you are running a current browser (i.e. chrome, firefox etc)

To connect to a VM for BiocAsia 2019, please follow [these instructions](VM_connections.html)

If your VM doesn't start, the following code should work:

```
install.packages("BiocManager")
pkgs <- c(
    "cluster", "survival", "randomForest", "missForest", "glmnet", "Rcpp", 
    "foreach", "itertools", "iterators", "Matrix", "devtools", "impute",
    "WangLab-MSSM/DreamAI/Code", "PengyiYang/PhosR", "directPA", "ClueR", 
    "Bioconductor/BiocIntro", "usethis", "roxygen2", "devtools", "goodpractice",
    "BiocCheck", "ExperimentHub", "CATALYST", "diffcyt", "sa-lee/fluentGenomics", 
    "workflowr", "ICC", "clustree", "HDCytoData"
    )
BiocManager::install(pkgs)
```

Contents of the VM data folder can be downloaded from [here](https://cloudstor.aarnet.edu.au/sender/?s=download&token=12762220-5d8d-4b80-9db6-d5015b8a3a1d)

## Travel Awards

There will be a number of travel awards available, with priority given to support students and early career researchers.
You must submit an abstract for a talk, software demo, or workshop to be eligible for a travel award.

<span style="color:red">*Travel award applications have closed.*</span>

## Thursday: 5 December, 2019

Bioconductor Workshops are in Seminar Room 1.1

### Provisional Timetable

| Time | |
|:--------------- |:----------------------------- |
| 8:45am - 9:00am | Registration <br> |
| 9:00am - 9:30am | Orientation and project updates <br> Martin Morgan |
| Session 1 | *Chair: Paul Harrison* |
| 9:30am - 10:00am | [Investigating higher order interactions in single cell data with scHOT](abstracts/ghazanfar.html) <br> Shila Ghazanfar - invited talk|
| 10:00am - 10:15am | [Integration of multiple single-cell CyTOF datasets to untangle the heterogeneity of cancer patients' responses to a new class of anti-cancer drugs](abstracts/trussart.html) <br> Marie Trussart |
| 10:15am - 10:20am | [A gene orientated approach to analysis of Hi-C data from immune cells](abstracts/coughlan.html) <br> Hannah Coughlan |
| 10:20am - 10:25am | [A workshop on single-cell RNA-seq analysis](abstracts/qiao.html) <br> PuXue Qiao |
| 10:25am - 10:30am | [Seamless visualization of complex genomic variations in GMOs and edited cell lines using gmoviz](abstracts/zeglinski.html) <br> Kathleen Zeglinski |
| 10:30am - 11:00am | **Morning Tea** <br> (Provided) |
| Session 2 | *Chair: Alexandra Garnham*  |
| 11:00am - 11:15am | [Use R/Bioconductor for Nanopore RNA-seq data analysis](abstracts/dong.html) <br> Xueyi Dong |
| 11:15am - 11:30am | [topconfects: rank differentially expressed genes using confidence bounds on fold change, with multiple testing adjustment](abstracts/harrison.html) <br> Paul Harrison |
| 11:30am - 11:35am | [Network-based Classification with ClassifyR](abstracts/strbenac.html) <br> Dario Strbenac |
| 11:35am - 11:40am | [Modelling for heteroscedastic groups in RNA-seq data](abstracts/law.html) <br> Charity Law |
| 11:40 - 11:45am | Buffer time |
| 11:45am - 12:15pm | [Visualisation and analysis of circular RNAs using Ularcirc](abstracts/ho.html) <br> Joshua Ho - invited speaker |
| 12:15pm - 1:30pm | **Lunch**  | 
| 1:30pm - 3:00pm | Bioinformatics Workshop Stream A:<br>Pei Wang - Imputation and data quality control for proteomics data<br>([description](workshops/workshop_wang.html), [materials](https://bis.amsi.org.au/speakers/pei-wang/)) <br> Bioinformatics Workshop Stream B:<br>Pengyi Yang - Computational analysis for biological discovery from (phospho)proteomic data<br> ([description](workshops/workshop_yang.html), [materials](workshops/PhosR_workshop/index.html)) <br><span style="color:green">**Bioconductor Workshop Stream C:<br>Martin Morgan - R and Bioconductor for Genomic Analysis**<br></span> ([description](workshops/workshop_morgan.html), [materials](http://bioconductor.org/help/course-materials/2019/BiocAsia/02-Workshop.html)) | 
| 3:00pm - 3:30pm | **Afternoon Tea** <br> (Provided) | |
| 3:30pm - 4:30pm | Bioinformatics Workshop Stream A:<br>Pei Wang - Imputation and data quality control for proteomics data<br> ([description](workshops/workshop_wang.html), [materials](https://bis.amsi.org.au/speakers/pei-wang/)) <br> Bioinformatics Workshop Stream B:<br>Ben Crossett, David Maltby & Angela Connolly - Introduction to proteomics<br> ([description](workshops/workshop_crossett_maltby_connolly.html), [materials](https://bis.amsi.org.au/speakers/introduction-to-proteomics/)) <br> <span style="color:green">**Bioconductor Workshop Stream C:<br>Peter Hickey & Saskia Freytag - Building a Bioconductor package**<br></span> ([description](workshops/workshop_hickey_freytag.html), [materials](http://rpubs.com/Saskia/554320)) |
| Session 3 | *Chair: Dave Tang* |
| 4:30pm - 4:45pm | [Gene Set Testing for Differentially Methylated Regions](abstracts/maksimoovic.html) <br> Jovana Maksimovic |
| 4:45pm - 4:50pm | [A tidy wrapper suite that introduces a unifying grammar for single-cell and bulk transcriptomic analyses](abstracts/mangiola.html) <br> Stefano Mangiola |
| 4:50pm - 4:55pm | [An Introduction to currently available scATAC-seq data analysing tools](abstracts/yang.html) <br> Haoyu Yang |
| 5:00pm - 6:00pm | [Bioinfosummer Poster Session](https://bis.amsi.org.au/program/#1562227152701-30236d2b-8de2) |
| 6:00pm - 7:30pm | [Public Lecture: The bright future of applied statistics](https://bis.amsi.org.au/public-lecture/) <br> Rafael Irizarry | 
| 7:30pm - 9:00pm | Pub | 

## Friday: 6 December, 2019

Morning presentations are in The Hub, outside of Charles Perkins Centre main entry. Afternoon workshops in Dry Lab 1.1, Dry Lab 1.2 and Dry Lab 1.3.

### Provisional Timetable

| Time | |
|:--------------- |:----------------------------- |
| 8:45am - 9:00am | Registration <br> |
| Session 4 | *Chair: Peter Hickey* |
| 9:00am - 9:40am | [How to advance science using Bioconductor](https://bis.amsi.org.au/speakers/martin-morgan/) <br> Martin Morgan - keynote speaker |
| 9:40am - 9:55am | [The RNAseq123 workflow package in Bioconductor](abstracts/ritchie.html) <br> Matthew Ritchie |
| 9:55am - 10:10am | [ClinSV: Detection of clinically relevant structural and copy number variation from whole genome sequencing](abstracts/minoche.html) <br> Andre Minoche |
| 10:10am - 10:15am | [Experiences of a First-Time Package Contributor](abstracts/pederson.html) <br> Stephen Pederson |
| 10:15am - 10:20am | [schex avoids overplotting for large single cell RNA-sequencing datasets](abstracts/freytag.html) <br> Saskia Freytag |
| 10:20am - 10:25am | [COmapR: Genetic length calculation from crossover events](abstracts/lyu.html) <br> Ruqian Lyu |
| 10:25am - 10:30am | Buffer time |
| 10:30am - 11:00am | **Morning Tea** <br> (Provided) |
| Session 5 | *Chair: Marie Trussart* |
| 11:00am - 11:20pm | 	[Single cell analysis with Mass Cytometry; technology introduction and opportunities in clinical studies](https://bis.amsi.org.au/speakers/helen-mcguire/) <br> Helen McGuire - invited speaker |
| 11:20am - 12:00pm | [On differential discovery in high-dimensional cytometry data](https://bis.amsi.org.au/speakers/helena-crowell/) <br> Helena Crowell - keynote speaker |
| 12:00pm - 12:30pm | [Ethics of precision medicine]() <br> Lisa Dive |
| 12:30pm - 1:30pm | **Lunch**  | |
| 1:30pm - 3:30pm | <span style="color:green">**Bioconductor Workshop Stream A:<br>Helena Crowell - Differential discovery in high-dimensional cytometry data**<br></span> ([description](workshops/workshop_crowell.html), [materials](https://bioconductor.org/packages/release/bioc/vignettes/CATALYST/inst/doc/differential_analysis.html))<br> <span style="color:green">**Bioconductor Workshop Stream B:<br>Stuart Lee - Fluent genomics: a plyranges and tximeta case-study**<br></span> ([description](workshops/workshop_lee.html), [materials](https://sa-lee.github.io/fluentGenomics/articles/fluentGenomics.html)) <br> Bioinformatics Workshop Stream C:<br>Dave Tang - Reproducible bioinformatics<br> ([description](workshops/workshop_tang.html), [materials](https://github.com/davetang/reproducible_bioinformatics))|
| 3:30pm - 3:50pm | **Afternoon Tea** <br> (Provided) | 
| Session 5 | *Chair: Dario Strbenac* |
| 3:50pm - 4:45pm | [Defining immune signatures of therapeutic response with non-negative matrix factorization of bulk and single cell data](https://bis.amsi.org.au/speakers/elana-fertig/) <br> Elana Fertig - keynote speaker |
| 4:45pm - 5:00pm | **Closing Remarks** |

## Contact

### In Case of Questions

If you have any questions regarding the conference please email Peter via
<span style="color:blue">hickey@wehi.edu.au</span>.

### Conference Committee

* Peter Hickey, The Walter and Eliza Hall Institute
* Saskia Freytag, The Harry Perkins Institute
* Dario Strbenac, University of Sydney
* Stephen Pederson, University of Adelaide
