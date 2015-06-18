# Barcoding-Scripts
Scripts for Barcoding workflow
Scripts are run to bring raw data files to various analysis of the data

Scripts are run in the order:

R4-Generator
R4-Parser
-> 3rd party alignment script
-> 3rd party assembly script
SAMparser
ContigsParser
-> SAMtools to convert alignments to "=" signs using -ecalmd option
ConvertedSAMparser
