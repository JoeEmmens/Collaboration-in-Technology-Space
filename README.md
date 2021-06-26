# Collaboration-in-Technology-Space

The relevant code to re-produce the results included in my master's thesis.

There are four relevant note books which accomplish different stages. They are designed to be read in this order. Using
jupyter notebooks provides the relevant output for each cell and you do not need to download the code to be run again. The data set and running times for the code are very large. Some sections include an measure for the length of time it took to run on my system. If you would like further detail on data or code please contact me.

  1) DataMerging : Builds the full dataset by merging the USPTO patent data which can be found here https://patentsview.org/download/data-download-tables
  2) ProdtoTechSpace : This produces the measure between technology spaces from the product space presented here https://dataverse.harvard.edu/dataverse/atlas and then uses the concordance presented here : https://sites.google.com/site/nikolaszolas/PatentCrosswalk
  3) InventorDistances : This first builds the inventor skill vectors of all active inventors of the period 2003-2018. Then it measures the team proximity using the methods outlined in the paper. It presents various results and merges the data to be used in the empirical analysis
  4) CollaborationNetwork : This presents the argument that local search can explain an increase in team proximity by building the existing collaboration network and measuring proximity across this network. This replicates the results presented in section 6 of the thesis.
