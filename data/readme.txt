Original file names for back reference.



******
DMR_mutation.tsv = blocks_summary_block_position_0flank_0.7Proba_66868blocks_13143blocks2mr_4603blocks2dmr.tsv
(DMR overlapping to mutation blocks)

chrs	start_pos	end_pos	block_id	mr_chrs	mr_start_pos	mr_end_pos	mr_sites	mr_logReg_proba


*******
DMR_0.7.bed = 24_chroms_high_miniPercentChange_gt_0.0001_Pcutoff_0.05_isSmooth_2_isModTest_0__all_dmrRanking_top_0.95_minLogReg_proba_0.7
(All DMRs above 0.7 score)

Chr	start	end	mr_info(chr:mrID:mr_sites:Hyper_hypo_mix_dmr:type_of_DMR)	score(from 0 to 1)

*******

gene_summary.csv = out_gene_DMR_or_DEG_in_GO_KEGG_BIOC_pathways_p_ls0.05.csv


(final 159 gene list after applying DAVID/GO pathway enrichment analysis (p-values <0.05) on the unique genes for mutation blocks with overlapping to either DMR or DEG regions and with feature score>=0.5)

gene_name	gene_type	block_id	new_mr_sites	patients	isTAD	enhancers	patient_id	geneType_meanScore	num_of_patients	diffExp_pval	dmr_pval	median_scores	mean_scores



*******


mutation_blocks_summary.tsv = blocks_summary.tsv

(Detailed list of all mutation blocks identified by current study)

block_id	chrom	start_pos	end_pos	number_of_mutations	number_of_patients	mutation_distribution


*******



differentially_expressed_genes_1.25Fd.txt = differentially_expressed_genes_1.25Fd.txt
 (Differentially expressed genes in FL (14 tutor vs 4 normal) filtered on 1.25 fd.)

#gene	differential_expression_T_test_p_value	4170686/tumor	4177987_tumor	4160468_tumor	4121361_tumor	4159170_tumor	4134005_tumor	4139696_tumor	4177601_tumor	4105105_tumor	4175837_tumor	4158726_tumor	4189200_tumor	4174905_tumor	4188900_tumor	normal_gcb_cells_SRR834985	normal_gcb_cells_SRR834984	normal_gcb_cells_SRR834986	normal_gcb_cells_SRR834983




*******


TAD_summary.tsv = blocks_summary_block_position_0flank_0.7Proba_66868blocks_13143blocks2mr_4603blocks2dmr_deg_info_filtered_DMR_and_DEG_uniqGene_commonTAD_Boundary.tsv

Summary of TADs overlapping with gene, 
gene_name	patients	gene_type	block_id	new_mr_sites	patient_id	enhancers	TAD2gene	Boundary2gene	TAD2block	Boundary2block	isTAD


*******


GO_term_gene.csv = out_GO_DMR_or_DEG_in_GO_KEGG_BIOC_pathways_p_ls0.05.csv

(GO terms for the final 159 gene list after applying DAVID/GO pathway enrichment analysis (p-values <0.05) on the unique genes for mutation blocks with overlapping to either DMR or DEG regions and with feature score>=0.5)


Category	Term	Count	%	PValue	Genes	List Total	Pop Hits	Pop Total	Fold Enrichment	Bonferroni	Benjamini	FDR	total_patients

*******

differentially_expressed_genes_exon.txt = differentially_expressed_genes_0fold0min_newColName.txt

Differentially expressed genes in FL (14 tutor vs 4 normal) with RPKM values normalized on exon length.

*******

Folder named "chromatin_state_data" contains results for robustness analysis of mutation block-gene associations by evaluating seven chromatin states.
