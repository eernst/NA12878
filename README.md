# NA12878 Human Reference on Oxford Nanopore MinION

## Contributors

Mark Akeson (1), Andrew D. Beggs (2), Thomas Nieto (2), Miten Jain (1), Nicholas J. Loman (3), Matt Loose (4), Sunir Malla (4), Justin O’Grady (5), Hugh E. Olsen (1), Josh Quick (3), Hollian Richardson (5), Jared T. Simpson (6,7), Terrance P. Snutch (8), Louise Tee (2), John R. Tyson (8)

   1. University of California, Santa Cruz, Santa Cruz, CA, USA
   2. University of Birmingham, Birmingham, B15 2TT
   3. Institute of Microbiology and Infection, School of Biosciences, University of Birmingham, Birmingham, B15 2TT, United Kingdom
   4. DeepSeq, School of Life Sciences, University of Nottingham, Nottingham, UK
   5. Norwich Medical School, University of East Anglia, Norwich, NR4 7UQ, United Kingdom.
   6. Ontario Institute for Cancer Research, Toronto, Canada
   7. Department of Computer Science, University of Toronto, Toronto, Canada
   8. Michael Smith Laboratories, University of British Columbia, Vancouver, Canada

## Background

We have sequenced the CEPH1463 (NA12878/GM12878, Ceph/Utah pedigree) human genome reference standard on the Oxford Nanopore MinION using 1D ligation kits (450 bp/s) using R9.4 chemistry (FLO-MIN106).

Human genomic DNA from GM12878 human cell line (Ceph/Utah pedigree) was either purchased from Coriell - "DNA" - (cat no NA12878) or extracted from the cultured cell line - "cells".  As the DNA is native, modified bases will be preserved.

## Data availability

Check back soon for the raw signal-level reads (FAST5).

### rel3

#### Basecalls

The `rel3` release consists of the full dataset, and has two new rapid kit runs with a new long DNA extraction method:

* 39 flowcells
* 91240120433 bases
* 14183584 reads

| flowcell_id | reads  | bases      | Date     | Centre  | SampleType | Kit         | Pore | Links                                                                                              | 
|-------------|--------|------------|----------|---------|------------|-------------|------|----------------------------------------------------------------------------------------------------| 
| FAB23716    | 356209 | 1409812422 | 14/07/16 | UBC     | DNA        | Rapid       | R9   | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4244727060-FAB23716.fastq.gz) | 
| FAB39088    | 658224 | 3287994454 | 19/09/16 | Notts   | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-288418386-FAB39088.fastq.gz)  | 
| FAB39075    | 466329 | 2439355478 | 20/09/16 | UBC     | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4246400039-FAB39075.fastq.gz) | 
| FAB39043    | 436976 | 2273008592 | 23/09/16 | Bham    | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3709921973-FAB39043.fastq.gz) | 
| FAB42706    | 430660 | 1966505502 | 12/10/16 | UBC     | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4111103328-FAB42706.fastq.gz) | 
| FAB41174    | 117057 | 687394987  | 13/10/16 | Bham    | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3976885577-FAB41174.fastq.gz) | 
| FAB42260    | 267644 | 1399557161 | 13/10/16 | UBC     | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4177064552-FAB42260.fastq.gz) | 
| FAB42804    | 16669  | 75062609   | 14/10/16 | Bham    | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-84744914-FAB42804.fastq.gz)   | 
| FAB42316    | 572838 | 3275026637 | 14/10/16 | Notts   | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-216722908-FAB42316.fastq.gz)  | 
| FAB42205    | 317654 | 1686630108 | 14/10/16 | Notts   | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3573838535-FAB42205.fastq.gz) | 
| FAB42561    | 233678 | 1520513556 | 19/10/16 | Notts   | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-356443753-FAB42561.fastq.gz)  | 
| FAB42473    | 644869 | 3357548938 | 19/10/16 | UBC     | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4179682758-FAB42473.fastq.gz) | 
| FAB42395    | 38291  | 179704035  | 20/10/16 | Norwich | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4178605061-FAB42395.fastq.gz) | 
| FAB42476    | 435158 | 2363036522 | 27/10/16 | UBC     | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3843483077-FAB42476.fastq.gz) | 
| FAB42451    | 817629 | 4530477841 | 28/10/16 | Notts   | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4239353418-FAB42451.fastq.gz) | 
| FAB42704    | 276152 | 1750149482 | 28/10/16 | UBC     | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-87746129-FAB42704.fastq.gz)   | 
| FAB42828    | 33527  | 163405138  | 01/11/16 | Norwich | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-288548394-FAB42828.fastq.gz)  | 
| FAB42810    | 322058 | 2020615256 | 02/11/16 | Norwich | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-352384898-FAB42810.fastq.gz)  | 
| FAB42798    | 193551 | 1339441522 | 03/11/16 | Norwich | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3306352129-FAB42798.fastq.gz) | 
| FAB45280    | 128234 | 799554798  | 11/11/16 | Norwich | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-222619780-FAB45280.fastq.gz)  | 
| FAB46664    | 491346 | 2038018797 | 15/11/16 | UBC     | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-288286712-FAB46664.fastq.gz)  | 
| FAB46683    | 72605  | 286275511  | 17/11/16 | Bham    | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4246923067-FAB46683.fastq.gz) | 
| FAB45332    | 530938 | 2864140853 | 17/11/16 | UBC     | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-551111640-FAB45332.fastq.gz)  | 
| FAB43577    | 426941 | 2539015084 | 18/11/16 | UCSC    | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3574887596-FAB43577.fastq.gz) | 
| FAB44989    | 558224 | 3443824633 | 18/11/16 | UCSC    | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-2567311907-FAB44989.fastq.gz) | 
| FAF01169    | 339447 | 2913892142 | 22/11/16 | Bham    | Cells      | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4245879798-FAF01169.fastq.gz) | 
| FAF01441    | 254705 | 2203636947 | 22/11/16 | Bham    | Cells      | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3910073345-FAF01441.fastq.gz) | 
| FAB45277    | 53547  | 445641679  | 22/11/16 | Notts   | Cells      | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-86567043-FAB45277.fastq.gz)   | 
| FAB45321    | 299174 | 2584017112 | 22/11/16 | Notts   | Cells      | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-19064779-FAB45321.fastq.gz)   | 
| FAF01127    | 632728 | 4972081712 | 25/11/16 | Bham    | Cells      | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-353303576-FAF01127.fastq.gz)  | 
| FAF01132    | 689781 | 5455971336 | 25/11/16 | Bham    | Cells      | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-84868110-FAF01132.fastq.gz)   | 
| FAB49712    | 632158 | 4906148911 | 28/11/16 | Bham    | Cells      | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-622291475-FAB49712.fastq.gz)  | 
| FAF01253    | 471698 | 3695661984 | 28/11/16 | Bham    | Cells      | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-83756522-FAF01253.fastq.gz)   | 
| FAB45321*   | 123037 | 1043504055 | 28/11/16 | Notts   | Cells      | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-285174896-FAB45321.fastq.gz) | 
| FAB49914    | 309175 | 2841008085 | 28/11/16 | Notts   | Cells      | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3775529215-FAB49914.fastq.gz) | 
| FAB45271    | 472656 | 3689043164 | 28/11/16 | Notts   | Cells      | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-152889212-FAB45271.fastq.gz)  | 
| FAB49164    | 746333 | 4438258089 | 06/12/16 | UCSC    | DNA        | Ligation | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4045668814-FAB49164.fastq.gz) | 
| FAB49908    | 224380 | 3141600861 | 09/12/16 | Bham    | Cells      | Rapid    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-481119249-FAB49908.fastq.gz)  | 
| FAF04090    | 91304  | 1213584440 | 09/12/16 | Bham    | Cells      | Rapid    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3842965088-FAF04090.fastq.gz) | 

Please verify downloads against <a href="rel3-md5s.txt">MD5 hashes</a>.

[*] This flowcell ID was input incorrectly.

#### Alignments by flowcell

Reads aligned against pre-computed 1000 genomes GRCh38 BWA database at <ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp/technical/reference/GRCh38_reference_genome/> with decoys using BWA MEM (commit: `5961611c358e480110793bbf241523a3cfac049b`) using parameters `-x ont2d`. Alignment statistics calculated using `samtools stats` (samtools version 1.3.1).

| FileID   | Sequences | Mapped | Mapped MQ0 | Unmapped | Bases Mapped | Avg Length | Link                                                                                                        |                                                                                                                 | 
|----------|-----------|--------|------------|----------|--------------|------------|-------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------| 
| FAB23716 | 356209    | 319259 | 26702      | 36950    | 1165998694   | 3957       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4244727060-FAB23716.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4244727060-FAB23716.fastq.gz.sorted.bam.bai) | 
| FAB39088 | 658224    | 613044 | 35394      | 45180    | 3007307322   | 4995       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-288418386-FAB39088.fastq.gz.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-288418386-FAB39088.fastq.gz.sorted.bam.bai)  | 
| FAB39075 | 466329    | 425117 | 28167      | 41212    | 2146453407   | 5230       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4246400039-FAB39075.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4246400039-FAB39075.fastq.gz.sorted.bam.bai) | 
| FAB39043 | 436976    | 415389 | 21043      | 21587    | 2113140439   | 5201       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3709921973-FAB39043.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3709921973-FAB39043.fastq.gz.sorted.bam.bai) | 
| FAB42706 | 430660    | 375374 | 17378      | 55286    | 1867123361   | 4566       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4111103328-FAB42706.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4111103328-FAB42706.fastq.gz.sorted.bam.bai) | 
| FAB41174 | 117057    | 114520 | 4186       | 2537     | 652217119    | 5872       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3976885577-FAB41174.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3976885577-FAB41174.fastq.gz.sorted.bam.bai) | 
| FAB42260 | 267644    | 246982 | 15624      | 20662    | 1263089767   | 5229       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4177064552-FAB42260.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4177064552-FAB42260.fastq.gz.sorted.bam.bai) | 
| FAB42804 | 16669     | 13311  | 1755       | 3358     | 53666089     | 4503       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-84744914-FAB42804.fastq.gz.sorted.bam)   | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-84744914-FAB42804.fastq.gz.sorted.bam.bai)   | 
| FAB42316 | 572838    | 512994 | 18985      | 59844    | 3100596254   | 5717       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-216722908-FAB42316.fastq.gz.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-216722908-FAB42316.fastq.gz.sorted.bam.bai)  | 
| FAB42205 | 317654    | 282502 | 12561      | 35152    | 1601397762   | 5309       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3573838535-FAB42205.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3573838535-FAB42205.fastq.gz.sorted.bam.bai) | 
| FAB42561 | 233678    | 225141 | 10255      | 8537     | 1420740185   | 6506       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-356443753-FAB42561.fastq.gz.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-356443753-FAB42561.fastq.gz.sorted.bam.bai)  | 
| FAB42473 | 644869    | 611138 | 32539      | 33731    | 3112342902   | 5206       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4179682758-FAB42473.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4179682758-FAB42473.fastq.gz.sorted.bam.bai) | 
| FAB42395 | 38291     | 36477  | 2059       | 1814     | 167168840    | 4693       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4178605061-FAB42395.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4178605061-FAB42395.fastq.gz.sorted.bam.bai) | 
| FAB42476 | 435158    | 416969 | 20908      | 18189    | 2214880871   | 5430       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3843483077-FAB42476.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3843483077-FAB42476.fastq.gz.sorted.bam.bai) | 
| FAB42451 | 817629    | 779328 | 36986      | 38301    | 4178966543   | 5540       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4239353418-FAB42451.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4239353418-FAB42451.fastq.gz.sorted.bam.bai) | 
| FAB42704 | 276152    | 263722 | 12926      | 12430    | 1619875186   | 6337       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-87746129-FAB42704.fastq.gz.sorted.bam)   | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-87746129-FAB42704.fastq.gz.sorted.bam.bai)   | 
| FAB42828 | 33527     | 27843  | 2442       | 5684     | 146819837    | 4873       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-288548394-FAB42828.fastq.gz.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-288548394-FAB42828.fastq.gz.sorted.bam.bai)  | 
| FAB42810 | 322058    | 305070 | 16802      | 16988    | 1808343119   | 6274       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-352384898-FAB42810.fastq.gz.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-352384898-FAB42810.fastq.gz.sorted.bam.bai)  | 
| FAB42798 | 193551    | 185739 | 8749       | 7812     | 1232035338   | 6920       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3306352129-FAB42798.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3306352129-FAB42798.fastq.gz.sorted.bam.bai) | 
| FAB45280 | 128234    | 122219 | 6336       | 6015     | 743280816    | 6235       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-222619780-FAB45280.fastq.gz.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-222619780-FAB45280.fastq.gz.sorted.bam.bai)  | 
| FAB46664 | 491346    | 456247 | 27622      | 35099    | 1862427349   | 4147       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-288286712-FAB46664.fastq.gz.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-288286712-FAB46664.fastq.gz.sorted.bam.bai)  | 
| FAB46683 | 72605     | 64739  | 5307       | 7866     | 269213160    | 3942       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4246923067-FAB46683.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4246923067-FAB46683.fastq.gz.sorted.bam.bai) | 
| FAB45332 | 530938    | 497862 | 26392      | 33076    | 2620752139   | 5394       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-551111640-FAB45332.fastq.gz.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-551111640-FAB45332.fastq.gz.sorted.bam.bai)  | 
| FAB43577 | 426941    | 410137 | 19835      | 16804    | 2344990054   | 5946       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3574887596-FAB43577.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3574887596-FAB43577.fastq.gz.sorted.bam.bai) | 
| FAB44989 | 558224    | 536572 | 25936      | 21652    | 3161900821   | 6169       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-2567311907-FAB44989.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-2567311907-FAB44989.fastq.gz.sorted.bam.bai) | 
| FAF01169 | 339447    | 315489 | 16481      | 23958    | 2677881316   | 8584       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4245879798-FAF01169.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4245879798-FAF01169.fastq.gz.sorted.bam.bai) | 
| FAF01441 | 254705    | 238834 | 12458      | 15871    | 2010117898   | 8651       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3910073345-FAF01441.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3910073345-FAF01441.fastq.gz.sorted.bam.bai) | 
| FAB45277 | 53547     | 51957  | 2132       | 1590     | 426639054    | 8322       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-86567043-FAB45277.fastq.gz.sorted.bam)   | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-86567043-FAB45277.fastq.gz.sorted.bam.bai)   | 
| FAB45321 | 299174    | 283355 | 15165      | 15819    | 2366003310   | 8637       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-19064779-FAB45321.fastq.gz.sorted.bam)   | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-19064779-FAB45321.fastq.gz.sorted.bam.bai)   | 
| FAF01127 | 632728    | 605633 | 27192      | 27095    | 4640355789   | 7858       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-353303576-FAF01127.fastq.gz.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-353303576-FAF01127.fastq.gz.sorted.bam.bai)  | 
| FAF01132 | 689781    | 655357 | 33564      | 34424    | 4966810089   | 7909       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-84868110-FAF01132.fastq.gz.sorted.bam)   | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-84868110-FAF01132.fastq.gz.sorted.bam.bai)   | 
| FAB49712 | 632158    | 612752 | 26264      | 19406    | 4594356245   | 7760       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-622291475-FAB49712.fastq.gz.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-622291475-FAB49712.fastq.gz.sorted.bam.bai)  | 
| FAF01253 | 471698    | 454434 | 20639      | 17264    | 3430678969   | 7834       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-83756522-FAF01253.fastq.gz.sorted.bam)   | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-83756522-FAF01253.fastq.gz.sorted.bam.bai)   | 
| FAB45321 | 123037    | 118311 | 5891       | 4726     | 952851126    | 8481       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-285174896-FAB45321.fastq.gz.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-285174896-FAB45321.fastq.gz.sorted.bam.bai)  | 
| FAB49914 | 309175    | 296250 | 12281      | 12925    | 2673848960   | 9188       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3775529215-FAB49914.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3775529215-FAB49914.fastq.gz.sorted.bam.bai) | 
| FAB45271 | 472656    | 450702 | 20148      | 21954    | 3468377327   | 7804       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-152889212-FAB45271.fastq.gz.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-152889212-FAB45271.fastq.gz.sorted.bam.bai)  | 
| FAB49164 | 746333    | 718351 | 32664      | 27982    | 4107087899   | 5946       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4045668814-FAB49164.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-4045668814-FAB49164.fastq.gz.sorted.bam.bai) | 
| FAB49908 | 224380    | 211060 | 11903      | 13320    | 2898563539   | 14001      | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-481119249-FAB49908.fastq.gz.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-481119249-FAB49908.fastq.gz.sorted.bam.bai)  | 
| FAF04090 | 91304     | 83164  | 6072       | 8140     | 1085757398   | 13291      | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3842965088-FAF04090.fastq.gz.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/rel3-nanopore-wgs-3842965088-FAF04090.fastq.gz.sorted.bam.bai) | 

#### Alignments by chromosome

Flowcell alignments were separated into individual chromosomes using `samtools merge`.

| Chrom | Mapped # | Mapped MQ0 | Bases Mapped | Avg Length | BAM                                                                | BAI                                                                    | 
|-------|----------|------------|--------------|------------|--------------------------------------------------------------------|------------------------------------------------------------------------| 
| chr1  | 1075867  | 43397      | 6829526262   | 6744       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr1.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr1.sorted.bam.bai)  | 
| chr2  | 1062314  | 31802      | 6755642896   | 6842       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr2.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr2.sorted.bam.bai)  | 
| chr3  | 858643   | 24189      | 5487703898   | 6757       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr3.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr3.sorted.bam.bai)  | 
| chr4  | 845677   | 30723      | 5395140705   | 6890       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr4.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr4.sorted.bam.bai)  | 
| chr5  | 774613   | 23499      | 4953273570   | 6821       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr5.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr5.sorted.bam.bai)  | 
| chr6  | 723047   | 24496      | 4618883250   | 6762       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr6.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr6.sorted.bam.bai)  | 
| chr7  | 696473   | 28231      | 4382999832   | 6772       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr7.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr7.sorted.bam.bai)  | 
| chr8  | 617988   | 23361      | 3968911801   | 6844       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr8.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr8.sorted.bam.bai)  | 
| chr9  | 539660   | 25898      | 3428430670   | 6764       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr9.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr9.sorted.bam.bai)  | 
| chr10 | 594688   | 20787      | 3805443564   | 6845       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr10.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr10.sorted.bam.bai) | 
| chr11 | 583055   | 17748      | 3710684724   | 6855       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr11.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr11.sorted.bam.bai) | 
| chr12 | 586663   | 17891      | 3734922623   | 6840       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr12.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr12.sorted.bam.bai) | 
| chr13 | 440615   | 17662      | 2844212242   | 6904       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr13.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr13.sorted.bam.bai) | 
| chr14 | 383777   | 15752      | 2439119767   | 6713       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr14.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr14.sorted.bam.bai) | 
| chr15 | 359853   | 19556      | 2268233023   | 6838       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr15.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr15.sorted.bam.bai) | 
| chr16 | 386401   | 22680      | 2425913744   | 6787       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr16.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr16.sorted.bam.bai) | 
| chr17 | 369036   | 22907      | 2302471086   | 6661       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr17.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr17.sorted.bam.bai) | 
| chr18 | 339094   | 13053      | 2172098564   | 6807       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr18.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr18.sorted.bam.bai) | 
| chr19 | 257039   | 10926      | 1472760724   | 6266       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr19.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr19.sorted.bam.bai) | 
| chr20 | 291960   | 13226      | 1829244829   | 6659       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr20.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr20.sorted.bam.bai) | 
| chr21 | 192383   | 24988      | 1207807437   | 6792       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr21.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr21.sorted.bam.bai) | 
| chr22 | 172934   | 10514      | 1041347396   | 6665       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chr22.sorted.bam) | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chr22.sorted.bam.bai) | 
| chrX  | 658347   | 28769      | 4210769167   | 7076       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chrX.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chrX.sorted.bam.bai)  | 
| chrY  | 23378    | 5292       | 133803203    | 7869       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chrY.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chrY.sorted.bam.bai)  | 
| chrM  | 59363    | 658        | 91949786     | 1628       | [BAM](http://s3.amazonaws.com/nanopore-human-wgs/chrM.sorted.bam)  | [BAI](http://s3.amazonaws.com/nanopore-human-wgs/chrM.sorted.bam.bai)  | 

# Read lengths

![Cellular library read length distribution](cells_readlength.png)

Figure: A typical read length distribution from a flowcell where we have run a cell-extracted DNA library. The y-axis shows the count of bases. Mean read length ~8.6kb with N50 of ~12.5kb (vertical line). Reads longer than 60kb are not expected due to limitations of the QIAGEN extraction kit employed.

# Disclaimer

This dataset is currently subject to rapid change as we continue to post up runs, therefore some statistics here may not represent full nanopore runs.

# Acknowledgements

We would like to acknowledge the support of Oxford Nanopore Technologies in generating this dataset, with particular thanks to Rosemary Dokos, Oliver Hartwell, Jonathan Pugh and Clive Brown. We would like to thank Radoslaw Poplawski and Simon Thompson for technical assistance with configuration and optimising of the CLIMB platform file system. We are grateful to Angel Pizarro and Jed Sundwall at Amazon Web Services for hosting this dataset as an <a href="https://aws.amazon.com/government-education/open-data/">AWS Open Data</a> set.

# Contact

Please raise issues on this Github repository concerning this dataset. A preprint describing the dataset in more detail will be available shortly.

# History

    * rel1: 1st December 2016. Initial release.
    * rel2: 5th December 2016. 25 flowcells, 58958035887 bases, 9053909 reads
