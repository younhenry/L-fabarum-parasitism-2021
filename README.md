# R_script_parasitism
Analysing parasitism data of Youn's postdoc

This repo contains data and code needed to perform the analyses and figures in our manuscript:

"A test of parasitoid local adaptation to symbiont-conferred host resistance" (by Youn Henry, Maxime Dahirel, Jesper Wallisch, Paula Rodriguez, Sandro Ginesi & Christoph Vorburger)

*The 'raw_data' folder contains the coma-delimited files of all the datasets we generated in the study, with extensive metadata, and unformated for use in R. Column headers are individually explained. 

*data in .txt format are in the `data` folder, R script in Rmd format (including detailed information about the analysis) in the `R` folder.

*The R code uses the `here` package (see also [here](https://github.com/jennybc/here_here)). This means all file paths are relative, and the analysis should work on your computer no questions asked, whether you use the R project or not, no code line to change as long as you download the entire repo (you just need to install all the needed packages first, of course).

*If you run the script for the first time, time-consuming outputs like models will be saved in the `R_output` folder so you don't have to re-run them everytime.

