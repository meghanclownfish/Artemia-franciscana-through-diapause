# assembly for both

<img width="3000" height="1800" alt="busco_figure" src="https://github.com/user-attachments/assets/3c29367e-ffe4-4cbf-8b1e-fe7b8d266ffb" />


# denovo

Trinity Version:      v2.1.1
Compiler:             GCC
Trinity Parameters:   --seqType fq --max_memory 195G --left /home/meghan/reads/0hR1.fastq.gz,/home/meghan/reads/6hR1.fastq.gz,/home/meghan/reads/10hR1.fastq.gz,/home/meghan/reads/12hR1.fastq.gz,/home/meghan/reads/14hR1.fastq.gz,/home/meghan/reads/24hR1.fastq.gz,/home/meghan/reads/70hR1.fastq.gz --right /home/meghan/reads/0hR2.fastq.gz,/home/meghan/reads/6hR2.fastq.gz,/home/meghan/reads/10hR2.fastq.gz,/home/meghan/reads/12hR2.fastq.gz,/home/meghan/reads/14hR2.fastq.gz,/home/meghan/reads/24hR2.fastq.gz,/home/meghan/reads/70hR2.fastq.gz --CPU 15 --trimmomatic --normalize_by_read_set

# genome-guided 

Trinity Version:      v2.1.1
Compiler:             GCC
Trinity Parameters:   --genome_guided_bam /home/meghan/GG/merged.bam --genome_guided_max_intron 10000 --max_memory 250G --CPU 15
