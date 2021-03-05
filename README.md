# Cmds_gapseq
Gapseq is a powerful genome-based metabolic pathways prediction tool. It can help to fill the gene gap of an incomplete genome by providing a proper growth medium.


Gapseq_codes_v20210305.sh is the code for applying gapseq to a microbial genome.

File(s) in the 'Input files' folder is the genome for analysis.
STY_Merged_OTU01.fasta is a merged file of four genomes that were dereplicated:
STY1_bin_1.fna
STY2_bin_2.fna
STY3_bin_1.fna
STY4_bin_1.fna

Its GTDB classification is d__Bacteria;p__Proteobacteria;c__Gammaproteobacteria;o__UBA10353;f__UBA5680;g__;s__. And it is a gram-negative bacteria.


File(s) in the 'Output files' folder are obtained by running gapseq against STY_Merged_OTU01.fasta.
STY_Merged_OTU01.RDS is the draft model.
STY_Merged_OTU01.RDS-gapfilled.RDS is the final model with gene gaps filled.


File(s) in the 'Growth medium' folder are the modified growth medium for different microbial taxa. You can create your own medium for a specific microorganism by adding/deleting compounds or changing the flux values in the file.