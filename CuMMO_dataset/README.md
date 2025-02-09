Metagenomic and metatranscriptomic data were collected from NCBI SRA and CAMERA database through screening with keywords (e.g., metagenome, metatranscriptome, water, soil, waste, and marine). The Basic Local Alignment Search Tool (BLAST) was used to acquire amoA/pmoA reads with an e-value cutoff of 10, and 381 representing sequences were searched against datasets with tBLASTn program. The extracted data were trimmed to remove reads shorter than 60 bp and low-quality bases (Q <20). For paired-end reads, reads were assembled using fastq-join in ea-utils version 1.1.2-806(Aronesty, 2013) and for read pairs that could not be assembled, only one read remained to maintain an accurate count. Finally, all of the retained sequences were combined into one file. 
The extracted shotgun reads were corrected, translated and classified against another reference databases of manually identified 63 full-length AmoA/PmoA amino acid sequences whose taxonomic information were already reviewed (Ettwig et al., 2010, Stoecker et al., 2006, Tavormina et al., 2011)using FrameBot (parameter: -N -l 30) (Wang et al., 2013) in RDP Tools (https://github.com/rdpstaff/RDPTools) (Cole et al., 2013).

The meaning of files:
amoApmoAfromNCBISRA_nucl.zip and ssu_merge_66666.silva.wang.taxonomy.zip #Metagenomic and metatranscriptomic data were collected from NCBI SRA and corrected using FrameBot. DNA format.

amoApmoAfromNCBISRA_prot.zip #Metagenomic and metatranscriptomic data were collected from NCBI SRA and corrected using FrameBot. Protein format.

bigref.fasta #The reference database of 381 representing sequences of AmoA/pmoA.

smallref.fasta #The reference database of manually identified 63 full-length AmoA/PmoA amino acid sequences whose taxonomic information were already reviewed.

ssu_merge_01045.fasta and ssu_merge_01045.silva.wang.taxonomy #Metagenomic data collected from CAMERA database.

ssu_merge_14972.fasta and ssu_merge_14972.silva.wang.taxonomy #Metatranscriptomic data collected from CAMERA database.
