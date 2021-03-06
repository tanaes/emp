Description of the notebooks in this directory: subdirectory, notebook filename, primary output, input files, subset of EMP used (if applicable), figure/table generated for EMP manuscript (if applicable).										
										
Subdirectory	|	Filename	|	Output	|	Input	|	Subset	|	Figure/Table
:-----:	|	-----	|	-----	|	-----	|	-----	|	-----
01-metadata-processing	|	metadata_refine.ipynb	|	Merged mapping files	|	Many input files	|	n/a	|	n/a
01-metadata-processing	|	map_samples_by_empo.ipynb	|	Map	|	emp_qiime_mapping_qc_filtered.tsv	|	qc_filtered	|	Fig. 1b
01-metadata-processing	|	physicochemical_pairplot.ipynb	|	Physicochemical pairplot	|	emp_qiime_mapping_qc_filtered.tsv	|	qc_filtered	|	Fig. S1
02-sequence-processing	|	sequence_length.ipynb	|	Sequence length	|	length_filtered_seqs_adaptor_cleanup.csv	|	all_emp	|	Fig. S2
02-sequence-processing	|	observation_table.ipynb	|	Sequence and OTU information	|	Biom files and summary files	|	n/a	|	n/a
03-otu-picking	|		|		|		|		|	
04-rarefaction-and-subsets	|	subset_samples_by_empo_and_study.ipynb	|	Subsets	|	emp_qiime_mapping_all_emp	|	all_emp	|	Fig. S13
05-alpha-diversity	|	alpha_diversity_boxplots.ipynb	|	Alpha-diversity boxplots	|	emp_deblur_90bp.qc_filtered.biom, closed-ref gg and silva tables	|	qc_filtered	|	Figs. 1c, S4
05-alpha-diversity	|	mle_curve_fits.ipynb	|	Laplace distributions	|	emp_deblur_90bp.qc_filtered.rare_5000.biom	|	qc_filtered	|	Fig. 1d
05-alpha-diversity	|	alpha_diversity_correlation.ipynb	|	Laplace distributions by sample type	|	emp_deblur_90bp.qc_filtered.rare_5000.biom	|	qc_filtered	|	Fig. S9
06-beta-diversity	|	unifrac_and_principal_coordinates.md	|	PCoA plots	|	emp_deblur_90bp.qc_filtered.biom	|	qc_filtered	|	Figs. 1e, S5, S7
06-beta-diversity	|	filter_biom_bdiv.ipynb	|	Beta-diversity results	|	emp_deblur_90bp.qc_filtered.biom	|	qc_filtered	|	Fig. 1e
06-beta-diversity	|	random-forest/	|	Random forest	|	training: emp_deblur_90bp.subset_2k.rare_5000.biom, classifying: emp_deblur_90bp.qc_filtered.rare_5000.biom	|	subset_2k	|	Table S4
06-beta-diversity	|	sourcetracker_mapping_file_and_execution.ipynb	|	SourceTracker 2 main code	|	emp_deblur_90bp.qc_filtered.rare_5000.biom	|	qc_filtered	|	Fig. S6
06-beta-diversity	|	sourcetracker_mixing_proportions.ipynb	|	SourceTracker 2 plots	|	emp_deblur_90bp.qc_filtered.rare_5000.biom	|	qc_filtered	|	Fig. S6
07-entropy-and-covariation	|	entropy_sample_type_vs_taxa.ipynb	|	Entropy calculations	|	emp_deblur_90bp.subset_2k.rare_5000.biom	|	subset_2k	|	Fig. 3b
07-entropy-and-covariation	|	entropy_plots.ipynb	|	Entropy plots	|	emp_deblur_90bp.subset_2k.rare_5000.biom	|	subset_2k	|	Fig. 3b
07-entropy-and-covariation	|	salinity_heatmap.ipynb	|	Salinity heatmap	|	emp_deblur_90bp.qc_filtered.biom	|	qc_filtered	|	Fig. S8
08-cooccurrence-and-nestedness	|	nestedness.md	|	Nestedness calculations	|	emp_deblur_90bp.subset_2k.rare_5000.biom	|	subset_2k	|	Fig. 2a
08-cooccurrence-and-nestedness	|	nestedness_binary_heatmaps.ipynb	|	Nestedness heatmaps	|	emp_deblur_90bp.subset_2k.rare_5000.biom	|	subset_2k	|	Fig. 2a
08-cooccurrence-and-nestedness	|	nestedness_nodf_plots.ipynb	|	Nestedness NODF plots	|	emp_deblur_90bp.subset_2k.rare_5000.biom	|	subset_2k	|	Figs. 2b, S11
08-cooccurrence-and-nestedness	|	cooccurrence-network/	|	Co-occurrence	|	emp_deblur_90bp.subset_2k.rare_5000.biom	|	subset_2k	|	Fig. 2c
09-sequence-lookup	|	otu_prevalence.ipynb	|	Tag sequence histogram	|	emp_deblur_90bp.qc_filtered.rare_5000.biom	|	qc_filtered	|	Fig. S3
09-sequence-lookup	|	summarize_otu_distributions.ipynb	|	Table of tag sequence distributions	|	emp_deblur_90bp.subset_2k.rare_5000.biom	|	subset_2k	|	Table 1
09-sequence-lookup	|	otu_trading_cards.ipynb	|	EMP trading cards	|	emp_deblur_90bp.subset_2k.rare_5000.biom	|	subset_2k	|	Fig. 14
09-sequence-lookup	|	trading-card-latex/	|	EMP trading cards LaTeX	|	emp_deblur_90bp.subset_2k.rare_5000.biom	|	subset_2k	|	Fig. 14
09-sequence-lookup	|	trading-card-html/	|	EMP trading cards HTML	|	emp_deblur_90bp.subset_2k.rare_5000.biom	|	subset_2k	|	Fig. 14
09-sequence-lookup	|	otu_entropy.ipynb	|	List of tag sequences with high entropy	|	emp_deblur_90bp.subset_2k.rare_5000.biom	|	subset_2k	|	Fig. 14, Table 1
09-sequence-lookup	|	mapping_deblur_to_dbs.ipynb	|	Overlap of EMP with GG and Silva	|	emp_deblur_90bp.qc_filtered.biom	|	qc_filtered	|	n/a
