# Virus_Graphs

Making Representative Genome Graphs from Eukaryotic Viruses and Phages


<img src="Screen Shot 2019-11-04 at 5.56.51 PM.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />

HIV inference based on NGS data. 

## Ideas

* k-mer idea

HIV inference

n = 170 references

n = 39 without non-recombinants

env, V1-V5

pol

How much variation can we have in a reference graph genome?

Tools considered: [VG](https://github.com/vgteam/vg), [NovoGraph](https://github.com/NCBI-Hackathons/NovoGraph), [SWIGG](https://github.com/NCBI-Codeathons/SWIGG).

## Outline, plan of action

hey

Day 2: 

Genome graphs with:
T-virus
HIV-1
         
Day 3:

# Datasets #

## HIV-1 Genome assemblies ##

HIV-1 datasets (as mutli-sequence alignments (MSA)/with gaps, and as multi-FASTA/gappless) from Los Alamos National Laboratory's [HIV Sequence Database](https://www.hiv.lanl.gov/content/sequence/HIV/mainpage.html) on November 5th-6th, 2019. Files set to include HXB2 K03455 as reference.

All complete genomes (n=10568).

**Tissue type**

CD4+ T cell (n=) vs PBMC (n=1555).

**Tropism**

Only CCR5 (n= 456) vs only CXCR4 (n= 43) vs R5X4 (n=51).

**Patient Information**

Acute infection (n=525)
AIDS (n=6)
Asymptomatic (n=33)
(n=)
(n=)
(n=)
(n=)
(n=)


## Sequencing data ##

<img src="igv_snapshot_HXB2-mapping_reads_from_SRR3472915_v2.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
**Figure: cDNA+PCR DNAseq ("classic RNAseq").** A. Coverage summary of reads mapped to HXB2 K03455 with minimap2 with usegalaxy.eu. B. RmDup-processed reads, controling for PCR duplicates after initial alignment. Search strategy = SRA. Searchterms: "HIV-1 and RNAseq and virus". Bioproject: PRJNA320293, specifically SRR3472915. Viewed in IGV.


<img src="igv_snapshot_HXB2_4000_read_subset.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
**Figure: Unpublished HXB2 ONT dataset.** [Gener, 2019](https://www.biorxiv.org/content/10.1101/611848v1). Coverage summary with reads. Viewed in IGV. (Note, "4000 reads" denotes the FASTQ subsetting from Guppy basecaller.)


### Discussions today, 4th November 2019

Too busy..

### Discussions today, 5th November 2019

### Discussions today, 6th November 2019



