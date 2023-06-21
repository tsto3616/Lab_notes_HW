# Lab_notes_HW

All June files will be uploaded here! Finals will be uploaded to a final folder

On the 31/5/2023 reanalysed the VC_AUS_NZ data from the start of the year (2023). First sequences were blasted and labelled if they were junk reads. For the ITS2 we applied a 0.05% cut off in R (within the DADA2 file for ITS2). Then used ML phylogeny to assign the rest of the ASVs. Those samples with pure hookworm species composition and at least 90% hookworm reads (the rest representing junk reads) were used to identify beta-tubulin-1 sequences- sequences from those samples were used for phylogeny to identify the species of beta-tubulin-1. For those BZ that extend past the primers in CLC mainworkbench when aligned to a full acan beta tubulin-1 gene (Accession# DQ459314) were removed as we cannot guarantee that they are hookworms, instead they are changed to Junk. Ones that were too small were kept as they often ended up being Uste. Any reference sequences for the beta tubulin-1 assays that were isolated were removed from the reference database for the phylogenies.

For SNP 134, 167, 198 and 200 respectively the position of these SNPs are 984-986, 1083-1085, 2393-2395, 2399-2401. The susceptible codons are glutamine (Q), Phenylalanine (F), Glutamate (E) and Phenylalanine (F). 

Then for the June results (QLD hookworms from Swaid/  TS.01- TS.13) used assign species function for ID of BZ assay and ITS2 assay- using the data from the VC/Aus/NZ at the start of the 2023 to inform assign species (perfect matches). Those unassigned despite that are used in a phylogeny to confirm species. The files for AssignSpecies are HW_167_as_ref, HW_200_as_ref, HW_ITS2_as_ref. Which will be found in this branch!

For the speadsheets if there is "Ancylostoma" in genus column and "Junk" in the species column then that means that there is a BLAST result for hookworms but following that (eg in alignment step) it was removed as it was outside the primers. As for those with a long genus name (eg. VC_NZ...) then it means its an exact match from AssignSpecies. 

On the 9th of June checked Winston 9405 (TS004) and Toby 9302 (TS005). A few days later did Aurora 9407 (TS006) and Cleo 9007 (TS007) both had hookworms. Non hookworm samples that were checked were Shaxx 5978, George 9019, Destiny 9016, Roachie 5633. Basil 9388 was checked as well but was negative for hookworms. 

On the 14th of june processed Ian's TS008-TS014 eggs by centrifuging with force, then removing as much ethanol with a pipette then evaporating off the ethanol. On the 16th of June i isolated DNA from samples TS008-TS0012 where it awaits PCR reactions. Might do more FECs too. 19th isolated DNA from the rest. 

Also chipping away at the nemabiome project bit by bit. Will update at a later day. For the nemabiome emily assigned species. 

Amplified ITS2 from TS001-TS014 on the 21/06/2023. TS001-TS007 amplified, TS008-TS014 did not, QLD10 did not either
