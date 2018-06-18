# deep_seq_analysis
The project uses reference based alignment as well as de novo assembly and summarizes the results from WGS analysis of a dataset obtained from SRA database.
The experimental design involved trimming the sequence using BRAT [http://compbio.cs.ucr.edu/brat/BRAT_USER_MANUAL_1_2_3.pdf].
Reference based alignment was done using bowtie and the output files were indexed using Samtools. 
The De novo assembly was assesed using Velvet. Both the assemblies were assessed by contig N50/N90 values, percentage coverage and average depth. The reference based assembly was also used to find out the number of SNPs/Indels.
