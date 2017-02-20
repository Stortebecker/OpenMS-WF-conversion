# Open MS Workflow Conversion Status

A table to keep up with the conversion status in Toppas v2.1, KNIME and Galaxy. Status in the `Conversion` columns may be either `empty` (not started), `WIP by XXX` (work in progress by whom?), `completed by XXX` (conversion completed, but no test data run) or `tested by XXX` (test results are equal to TOPPAS results).

Please keep the file up to date as far as it concerns other team members, so we can avoid redundant work. Thanks a lot!

## Misc
WF | Test data (with location on server) | Conversion v2.1 | Conversion KNIME | Conversion Galaxy
:-- | :--: | :--: | :--: | :--:
GenerateShuffledDatabase_20150926 | |||
QualityControl_20151104 | |||

## Sciex, TripleTOF 6600
WF | Test data with location on N: | Conversion v2.1 | Conversion KNIME | Conversion Galaxy
:-- | :--: | :--: | :--: | :--:
LabelFree_SciexTripleTOF_CentroidMode_20170111 | |||
PeptideQuantification_SciexTripleTOF6600_centroided_20170109 | |||
PeptideFeatureDetection_SciexTripleTOF6600_20170107 | |||
SILACLys8Arg10_PeptideQuantification_SciexTripleTOF6600_20170107 ||||

## Thermo, LTQ Orbitrap XL
WF | Test data with location on N: | Conversion v2.1 | Conversion KNIME | Conversion Galaxy
:-- | :--: | :--: | :--: | :--:
LabelFree_LTQOrbitrapXL_20170126 | D:/data/Lars/2015/20151111_BookChapterRSC/label_free/strepto_human_mix/data | tested @eppinglen ||
protein_quantification_Leu3SILAC_LTQOrbiXL_20160627 | N:/data-NAS/BM/BM40-48_Marius-Hefe | tested @eppinglen ||

## Thermo, Orbitrap Velos
WF | Test data with location on N: | Conversion v2.1 | Conversion KNIME | Conversion Galaxy
:-- | :--: | :--: | :--: | :--:
iTRAQ_LTQOrbitrapVelos_20151116 ||||
QualityControl_20151106 ||||

## Thermo, Q Exactive
WF | Test data with location on N: | Conversion v2.1 | Conversion KNIME | Conversion Galaxy
:-- | :--: | :--: | :--: | :--:
LabelFree_QExactive_20151015 | | tested @eppinglen ||
LabelFreeMultipleFractions_QExactive_20151016  | | WIP @Stortebecker ||
SILACArg6Lys6Labelling_QExactive_20151126 ||||
SILAC_Lys4Arg6_Lys8Arg10_QExactive20160627 |||| 
DoubleDimethylLabelling_QExactive_20150707 ||||
TripleDimethylLabelling_QExactive_20151115 ||||
TAILS_QExactive_20160609 ||||
TAILS_triple_QExactive_20161127 ||||