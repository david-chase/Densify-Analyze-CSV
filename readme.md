<img src="https://www.densify.com/wp-content/uploads/densify.png" width="250">

# Densify-Analyze-CSV

This repository contains several Excel templates you can use to view, format, and analyze the output of Densify-Export-CSV.   

## Related projects

These two projects are intended to work closely hand-in-hand:

1. [Densify-Export-CSV](https://github.com/dbc13543/Densify-Export-CSV) 
2. [Densify-Analyze-CSV](https://github.com/dbc13543/Densify-Analyze-CSV) (This project)

## Repository contents:

1. Cloud and Containers.xlsb
2. Tags and Labels.xlsb
3. Software Identified.xlsb

These are three Excel templates that allow you to view, slice, and dice the data output by Densify-Export-CSV.

## Input files:

These Excel files require the output of the Densify-Export-CSV command.  

yyyy-mm-dd <instancename> Analyses.csv -- A list of the analyses in your Densify instance.  In most cases this is a list of accounts or subscriptions in which services were found that can be analyzed by the Densify engine. <br/>
yyyy-mm-dd <instancename> Cloud Recommendations.csv -- A list of all cloud recommendations across all CSP. <br/>
yyyy-mm-dd <instancename> Container Recommendations.csv -- A list of all container recommendations across all clusters. <br/>
yyyy-mm-dd <instancename> Tags.csv -- A raw dump of all tags and values found in all instances.  One line per tag. <br/>
yyyy-mm-dd <instancename> Software Identified.csv -- A raw dump of all software found in all instances and the confidence of the match.  One line per piece of software. <br/>


v1.0<br/>
---<br/>
* Split the Excel files out into a separate project so that Densify-Export-CSV stands on its own as an export tool<br/>
