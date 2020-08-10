## 24.07

Zoom with Mato

- create a list of homologs of cI Lambda
- take around 100-200 bp upstream promoter
- align
- get info from literature search for studied cases
- get an overview of structure of Pr regions from different phages

Might be useful: [operon prediction tool](http://www.softberry.com/berry.phtml?topic=index&group=programs&subgroup=gfindb&gclid=Cj0KCQjwjer4BRCZARIsABK4QeUp8Z9j2BHO1GEtD2Igz7hu5hHQCUDW8dKenXb9X3W8Ym7MdT6olssaAmAWEALw_wcB)

## 27.07

NCBI Protein

repressor [Escherichia virus Lambda]
NCBI Reference Sequence: [NP_040628.1](https://www.ncbi.nlm.nih.gov/protein/NP_040628.1)

Display: 1000
Filter: Organism - viruses (taxid:10239)

[Rusults](https://github.com/agreshno/Mato/blob/master/seqdump%20(2).txt) - protin seq in fasta format

Reminder: Immunity region of phage lambda

![immunity_reg_L_phage](https://github.com/agreshno/Mato/blob/master/immunity_region_lambda_phage.jpg)

Fig.1 Structure of PR region of phage Lambda

![im_region_L_phage_seq](https://github.com/agreshno/Mato/blob/master/immunity_region_lambda_phage_seq.jpg)

Fig.2 Detailed structure of PR region of phage Lambda

### First attempt

150 bp upstream cI gene from available viral genomes

Table 1. Coordinates of regions from genomes (homologs of cI lambda) for analysis

Organism | RefSeq ID | Coordinates
--|--|--
Escherichia phage Lambda | NC_001416.1 | 37941-38091
HK244 | No entry in NCBI | 
Escherichia phage Lambda_ev243 | No entry in NCBI |
Escherichia phage HK544 | NC_019767.1 | 29401-29551
Escherichia virus HK97 | NC_002167.1 | 28953-29102
Escherichia phage HK542 | NC_019769.1 | 27885-28035
Enterobacteria phage CL707 | No entry in NCBI |
Escherichia phage Lambda_ev099 | No entry in NCBI |
Enterobacteria phage mEp332 | No entry in NCBI |
Escherichia Stx1 converting phage | NC_004913.3 | 43484-43634
Enterobacteria phage 2851 | GenBank: FM180578.1 | 11032-11182
Stx2-converting phage 1717 | NC_011357.1 | 11696-11846
Enterobacteria phage VT2-Sakai | NC_000902.1 | 11410-11560
Escherichia phage P13374 | NC_018846.1 | 17831-17981
Salmonella phage vB_SosS_Oslo | NC_018279.1 | 37074-37224
Salmonella phage 103203_sal5 | NC_031946.1 | 32320-32470
Salmonella phage SPN9CC | NC_017985.1 | 12135-12285
Salmonella phage g341c | NC_013059.1 | 30725-30875
Salmonella phage epsilon34 | NC_011976.1 | 15289-15439
Salmonella phage 29485 | GenBank: KY709687.1 | 9249-9399
Salmonella phage 118970_sal4 | NC_030919.1 | 12434-12584

[Fasta file with 150 bp regions upstream cI gene](https://github.com/agreshno/Mato/blob/master/seq/upstream_cI_phages.txt) - Use this later

[Fasta file with seqs from NCBI search](https://github.com/agreshno/Mato/blob/master/seq/cI_lambda_homoligs_complete%20seqs.txt)

[Fasta file with seqs from NCBI seqarch and available genomes](https://github.com/agreshno/Mato/blob/master/seq/cI_lambda_homologs_complete-seqs_with_genomes_av.txt)

## 29.07

Decicded to add to this list of homologs spme PR regions from the literature

![Pr_regions](https://github.com/agreshno/Mato/blob/master/rel(Lambda)_PR.png)

Fig.3 Activities of Prs from different phages (from Claudia's thesis)

Table 2. Coordinates of regions from genomes (from Claudia's thesis) for analysis

Organism | RefSeq ID | Coordinates
--|--|--
Enterobacteria phage P22 | NC_002371.2 | 31883-32033
Enterobacteria phage phi80 | NC_021190.1 | 35302-35452
Enterobacteria phage HK620 | NC_002730.1 | 9116-9266
Enterobacteria phage 933W | NC_000924.1 | 12783-12933
Bacteriophage 434 | GenBank: J02460.1 | 1-150

I have a feeling that Enterobacteria phage P22 has completely different organisation of its immunity region.

No full genome of Bacteriophage 434; only an entry with the regulatiry region.

## 10.8

Literature search

Phage | OR1 | OR2 | OR3 | OL1 | OL2 | OL3 | Ref
-|-|-|-|-|-|-|-
Enterobacteria phage P22 | ATTAAAGAACACCTAAAT | ACTAAAGGAATCTTTAGT | ATTTAAGATGACTTAACT | ATTTAAGACTTCTTAATT | TTTGAAGAAAACTTAAAT | ACTTAAGTTTTTATTTGA | [1]

## References:

[1](https://www.sciencedirect.com/science/article/pii/0022283680901588) - Operator sequences of bacteriophages P22 and 21
