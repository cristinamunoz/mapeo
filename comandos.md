```
samtools view -Sb -f 1 1A10_sialidase_mapping.sam > 1A10_sialidase_mapping_mapped_proper_pairs.bam  

samtools sort -O bam -o 1A10_sialidase_mapping_mapped_proper_pairs_sorted.bam -T ./out_tmp 1A10_sialidase_mapping_mapped_proper_pairs.bam 

samtools index 1A10_sialidase_mapping_mapped_proper_pairs_sorted.bam                        
                       
samtools idxstats 1A10_sialidase_mapping_mapped_proper_pairs_sorted.bam > 1A10_sialidase_mapping_mapped_proper_pairs_sorted.stats⁠⁠⁠⁠
```
