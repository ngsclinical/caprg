

&lt;H1&gt;

CAPRG SUMMARY

&lt;/H1&gt;


<p>
“Contigs Assembly Pipeline using Reference Genome” (CAPRG) assemble long sequence reads for non-model organisms by leveraging a reference genome of a closely-related phylogenetic relative. With the advent of NGS, the assembling of millions of reads is computationally expensive. Various clustering method like megablast, cd-hit have been employed to reduce the memory and processing time. CAPRG utilizes mapping the raw reads of genome/transcriptome against a reference genome and then assembling them to longer contigs that can be utilized for 'gene-hunting'.<br>
The Pipeline consist of three step:<br>
1. Map the transcriptome raw sequences against the reference genome<br>
2. Store the mapped reads in RDBMS database<br>
3. Assemble reads based on its chromosomal position<br>
</p>