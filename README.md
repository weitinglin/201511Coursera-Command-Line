# Course: Command Line For Genomic Data
## 201511-12##
## Professor: Liliana Florea, PhD, John Hopskins University


- Unix commands
 - Basic commands
 - Pipes
- Sequences and genomic features
 - Formats: Fastq, BED, GTF, SAM 
 - Tools: Samtools, Bedtools 
- Alignment and sequence variation
 - Bowtie, BWA
 - Samtools, Bcftools
 - Application: variant calling
- Transcriptomics
 - Tophat
 - Cufflinks
 - IGV
 - Application: RNA-seq analysis


#Week1: Basic Command Line


sort months
sort -r months
sort -k2 months
sort -k 2n months
sort -k 2nr months
sort -k 3 months
sort -k 3 -k 2n months
cut -f1 months
cut -f1-3 months
cut -d '' -f1 months  # d 辨識特定的符號做為分別
sort -u months
uniq months
uniq seasons | sort -u
uniq -c
grep root */*.sample
grep " 12 winter" months
grep -n " 12 winter" months
diff orchard orchard.1
comm -1 -2 orchard orchard.1
#Week2


#Week3


#Week4: RNA-seq

