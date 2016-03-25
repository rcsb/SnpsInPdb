# SnpsInPdb

This project contains supplemental  material for a manuscript that is under review. The dataset contained in the manuscript is available through the file [dataset.csv](dataset.csv).

## Documentation

The columns in the file are:

*PDB ID*: PDB ID of the variant <br />
*SNP ID*: dbSNP ID of the mutation <br />
*WILDTYPE PDB ID*: PDB ID of the wildtype structure (if available in PDB) <br />
*Surface*: 1, if the mutation lies on the surface of the protein. <br />
*Surface-Loop*: 1, if the surface mutation lies on a loop (secondary structural element). <br />
*Surface-Alpha helix*: 1, if the surface mutation lies on alpha helix (secondary structural element). <br />
*Surface-Beta sheet*: 1, if the surface mutation lies on a beta strand (secondary structural element). <br />
*Buried*: 1, if the mutation is buried in the interior of the protein. <br />
*Buried-Alpha helix*: 1, if the buried mutation lies on alpha helix (secondary structural element). <br />
*Buried-Beta sheet*: 1, if the buried mutation lies on beta strand (secondary structural element). <br />
*Buried-Loop*: 1, if the surface mutation lies on a loop (secondary structural element). <br />
*No structural consequence found*: No information regarding the structural consequence of the SNP found from literature. <br />
*Common*: 1, if MAF( Minor Allele Frequency) of the mutation &gt; 1%. <br />
*Rare*: 1, if MAF( Minor Allele Frequency) of the mutation &lt; = 1%. <br />
*No_Freq*: 1, if Frequency information is not available for the mutation. <br />
*Disease*: 1, if the mutation is disease causing. <br />
*Risk*: 1, if the mutation increases the risk of developing a disease. <br />
*Enzyme Activity*: 1, if the mutation affects activity of the protein. <br />
*Aggregates*: 1, if the mutation facilitates aggregate formation <br />
*Stability*: 1,if the mutation affects stability of the protein <br />
*Binding/Dissociation*: 1,if the mutation affects the binding properties of the protein <br />
*Assembly: 1, if the mutation affects the biological assembly <br />
*Rearrangement*: 1, if the mutation causes local conformational changes <br /> 
*No Functional consequence found*: No information regarding the functional consequence of the SNP found from literature reference <br />

