# SnpsInPdb

This project contains supplemental  material for a manuscript that is under review. The dataset contained in the manuscript is available through the file [dataset.csv](dataset.csv).

## Documentation

The columns in the file are:

PDB ID = PDB ID of the variant
SNP ID = dbSNP ID of the mutation 
WILDTYPE PDB ID = PDB ID of the wildtype structure (if available in PDB)
Surface = 1, if the mutation lies on the surface of the protein.
Surface-Loop = 1, if the surface mutation lies on a loop (secondary structural element).
Surface-Alpha helix = 1, if the surface mutation lies on alpha helix (secondary structural element).
Surface-Beta sheet = 1, if the surface mutation lies on a beta strand (secondary structural element).
Buried = 1, if the mutation is buried in the interior of the protein.
Buried-Alpha helix = 1, if the buried mutation lies on alpha helix (secondary structural element).
Buried-Beta sheet = 1, if the buried mutation lies on beta strand (secondary structural element).
Buried-Loop = 1, if the surface mutation lies on a loop (secondary structural element).
No structural consequence found = No information regarding the structural consequence of the SNP found from literature.
Common = 1, if MAF( Minor Allele Frequency) of the mutation > 1%
Rare = 1, if MAF( Minor Allele Frequency) of the mutation <= 1% 
No_Freq = 1, if Frequency information is not available for the mutation
Disease = 1, if the mutation is disease causing.
Risk = 1, if the mutation increases the risk of developing a disease
Enzyme Activity = 1, if the mutation affects activity of the protein
Aggregates = 1, if the mutation facilitates aggregate formation
Stability = 1,if the mutation affects stability of the protein 
Binding/Dissociation= 1,if the mutation affects the binding properties of the protein 
Assembly =1, if the mutation affects the biological assembly
Rearrangement = 1, if the mutation causes local conformational changes
No Functional consequence found= No information regarding the functional consequence of the SNP found from literature 
Reference 

