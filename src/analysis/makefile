analyze: ../../gen/analysis/output/analysis.pdf

../../gen/analysis/output/analysis.pdf: ../../gen/data-preparation/output/data_scientist_clean.csv ../../gen/data-preparation/output/data_analist_clean.csv ../../gen/data-preparation/output/marketing_analist_clean.csv ../../gen/data-preparation/output/marketeer_clean.csv
	mkdir "../../gen/analysis"
	mkdir "../../gen/analysis/output"
	R -e "rmarkdown::render('analysis.Rmd', output_file = '../../gen/analysis/output/analysis.pdf')"
