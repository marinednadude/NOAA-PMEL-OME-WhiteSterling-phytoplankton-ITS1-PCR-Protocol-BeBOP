## This is a draft document and has not been finalized or version controlled.

----------

# Protocol Template


### Quick Links:

- [MIOP](#Minimum-Information-about-an-Omics-Protocol-(MIOP))
- [Background](#BACKGROUND)
- [Equipment](#EQUIPMENT)
- [Standard Operating Procedure](#STANDARD-OPERATING-PROCEDURE)

## Minimum Information about an Omics Protocol (MIOP)

See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

| MIOP Term  | Value |
| ------------- | ------------- | 
| methodology category  | omics analysis |
| project  | NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program Protocols |
| purpose  | PCR [OBI:0000415] |
| analyses  | PCR [OBI:0000415] |
| geographic location  | North East Pacific Ocean [GAZ:00013765], Bering Sea [GAZ:00008990], Arctic Ocean [GAZ:00000323] |
| broad-scale environmental context  | oceanic epipelagic zone biome [ENVO:01000035], marine biome [ENVO:00000447], marine benthic biome [ENVO:01000024] |
| local environmental context  | oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024] |
| environmental medium  | sea water [ENVO:00002149] , DNA extraction [OBI:0000257] |
| target  | internal transcribed spacer region [SO:0000639] |
| creator  | [Shannon Brown](https://github.com/Brown-NOAA), [Han Weinrich](https://github.com/HanWeinrich), and [Zachary Gold](https://github.com/marinednadude) |
| materials required  | agarose gel electrophoresis system [OBI:0001134] , PCR instrument [OBI:0000989] |
| skills required  | sterile technique, pipetting skills, and standard molecular technique |
| time required  |170 |
| personnel required  | 1 |
| language  | en |
| issued  | TBD	 |
| audience  | scientists |
| publisher  | NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies |
| hasVersion  | 1 |
| license  | CC0 1.0 Universal |
| maturity level  | mature |

--------


## AUTHORS

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0000-0001-9808-2638 |2024-02-02|
| Han Weinrich  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0009-0007-6063-0986 |2024-02-02|
|Sean McAllister	|Ocean Molecular Ecology, NOAA PMEL & UW CICOES	|0000-0001-6654-3495	|2024-02-02|
|Matt Galaska	|Ocean Molecular Ecology, NOAA PMEL|	0000-0002-4257-0170	|2024-02-02|
|Zachary Gold	|Ocean Molecular Ecology, NOAA PMEL	|0000-0003-0490-7630	|2024-02-02|


-------------

## RELATED PROTOCOLS

| PROTOCOL NAME                                                      | LINK | VERSION | RELEASE DATE |
| ------------- | ------------ | ------- | ------------ |
| [Sterling et al. 2022](https://aslopubs.onlinelibrary.wiley.com/doi/10.1002/lno.12189) Appendix S1  | [Link](https://aslopubs.onlinelibrary.wiley.com/doi/10.1002/lno.12189) |   1.0      | 2022-10-07     |
| [NOAA Northwest Fisheries Science Center](https://www.fisheries.noaa.gov/about/conservation-biology-division-northwest-fisheries-science-center) & [MMARINeDNA: Marine Mammal Remote detection via INnovative environmental DNA sampling](https://www.ednacollab.org/mmarinedna-about) MiFish 12S Universal Teleost Protocol | [Pending Shaffer et al. 2024 publication](https://drive.google.com/file/d/15s1KfLccbXUQExfHI0RWwWSu1QNImBCt/view?usp=drive_link) |         | Pending      |




---
# BACKGROUND

## Summary

This protocol is for amplifying the internal transcribed spacer 1 (ITS1) gene in eukaryotes. The primers (forward: White ITS1 F, reverse: Pn-ITS1R) were first presented in White et al. 1990 (forward) and Sterling et al. 2022 (reverse). The target amplicon size is 235–370 base pairs.

This primer set targets *Pseudo-nitzschia* spp. diatoms. Important note, this primer also amplifies non-target organisms including other single-celled phytoplankton (Sterling et al. 2022).

The protocol presented here is intended as the first PCR of a two-step PCR next generation sequencing library preparation using Illumina Nextera Unique Dual Indices. Our written protocol does not include the second PCR step in which unique library-specific barcodes are attached to each round 1 PCR product. 

## Method description and rationale

This protocol was chosen because it successfully identifies *Pseudo-nitzschia* diatom species and has been used to generate successful marine diatom eDNA time series. Our protocol uses the same primers as Sterling et al. 2022. Our protocol uses the same polymerase and thermocycling conditions as MMARINeDNA 12S MiFish protocol, but is 25 µL in total reaction volume. We intentionally chose this protocol to facilitate identification of *Pseudo-nitzschia* diatom species from PMEL OME eDNA time series.


## Spatial coverage and environment(s) of relevance

This protocol has been used to amplify extracted DNA from thousands of filtered sea water samples taken from Northeastern Pacific coastal stations off the western coast of North America (primarily off California, Oregon, Washington,and Alaska).

## Personnel Required

One person with molecular biology experience.

## Safety

This protocol does not involve any hazardous chemicals, although standard precautions including wearing PPE should be taken to avoid skin and eye exposure to chemical reagents.

## Training requirements

Molecular biology training (including, at a minimum, sterile technique, pipetting small volumes, and programming and running PCR thermocyclers) is required to conduct this protocol.

## Time required to execute the procedure

PCR preparation and running the PCR protocol for a single 96-well plate takes 2.8 hours (170 minutes), of which 80 mins is the thermocycler run time. Additional plates can be run simultaneously without greatly increasing the time required. 

-----
# EQUIPMENT


| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment**|
|Pipetter: 1-10 μl|Pipetman P10L|Gilson|1|Can be substituted with any accurate pipettor.|
|Pipetter: 20 - 200 uL	|Pipetman P200L|Gilson|	1|Can be substituted with any accurate pipettor.|
|Pipetter: 100-1000 uL	|Pipetman P1000	|Gilson	|1|Can be substituted with any accurate pipettor.|
|BioSafety II cabinet|Biological safety cabinet (INT-1100A2)|Kewaunee|1|Can be substituted with generic; internal UV light required.|
|Thermocycler|Veriti 96-well thermal cycler |Applied Biosystems| 1|	Can be substituted with generic.|
| Mini-centrifuge | Personal mini centrifuge  | BioExcell | 1 | Can be substituted with generic, but needs to fit 1.5-2.0 mL tubes. |
| Vortex | Analog vortex mixer | Fisher Scientific | 1 | Can be substituted with generic. |
| Plate spinner | [Salad spinner]( https://doi.org/10.3390/mps3020041) | Cuisinart | 1| Can be substituted with generic or plate centrifuge. |
| Foil roller | Rubber roller | Generic | 1 ||
| PCR cooler rack | PCR cooler 0.2-0.5 mL | Eppendorf | 1 | Can be substituted with generic.|
| 1.5 mL tube cooler rack | Benchtop cooler | Thermo Scientific  | 1 | Can be subsituted with generic. Store in the fridge to avoid refreezing reagents. |
| 2 mL tube rack | Microcentrifuge tube rack | VWR | 1 | Can be substituted with generic. |
| 0.2 mL PCR plate rack | PCR tube rack for 0.2 mL micro-tubes | Fisher Scientific | 1 | Can be substituted with generic. |
|Wash bottle|Safety Wash Bottle for Ethanol 500mL|VWR|1|Can be substituted with generic (not labeled specifically for EtOH). Must be sterilized before use|
|Wash bottle|Safety Wash Bottle for Hypochlorite Bleach 500mL|VWR|1|Can be substituted with generic (not labeled specifically for bleach). Must be sterilized before use|
|Freezer|Freezer capable of reaching and maintaining -20°C|Generic|1|Used to store DNA and PCR reagents. **NOTE: a separate freezer should be used to store PCR products if possible.**|
|Fridge| Refrigerator capable of reaching and maintaining 4°C|Generic|1|Used to store some PCR reagents **NOTE: a separate fridge should be used to hold PCR products if possible.**|
|Trash bag holder|Bel-Art scienceware bench-top biohazard holders|Fisher Scientific|1|Can be substituted with generic.|
|Cryoboxes|TruCool hinged lid cryoboxes|VWR|2|Can be substituted with generic, but recommend set color for eDNA and reagents. Must be sterilized before use. Can be used to store DNA tubes (pre-PCR) and reagent aliquots. |
| **Consumable equipment** |
| 1000 μL pipette tips | TipOne RPT filter tips 1000 μL XL graduated | USA Scientific | 4 | Can be subsituted with generic. Must be sterile and filtered. |
| 200 μL pipette tips  | TipOne RPT filter tips 200 μL graduated| USA Scientific |4 | Can be subsituted with generic. Must be sterile and filtered. |
| 10 μL pipette tips  | TipOne RPT filter tips 10 μL graduated | USA Scientific | 96 | Can be subsituted with generic. Must be sterile and filtered. |
| PCR plates | Twin.tec LoBind PCR plates, semi-skirted (96-wells)| Eppendorf | 1 | Can be subsituted with generic. Must be DNA low retention. |
| PCR aluminum foil | Adhesive sterile PCR foil seals | VWR| 1 | Can be subsituted with generic. Must be sterile. |
| 2 mL tubes | Snap cap DNA LoBind 2.0 mL tubes, PCR-clean| Eppendorf |5 | Can be substituted with generic. Must be sterile. |
| 1.5 mL tubes | Snap cap DNA LoBind 1.5 mL tubes, PCR-clean| Eppendorf |2 | Can be substituted with generic. Must be sterile. |
| Kimwipes | Delicate task wipes | Kimtech | 5 | Can be substituted with generic. Must be lint-free.|
| Nitrile gloves | Powder Free Nitrile Gloves | Fisher Scientific | 4 | Can be subsituted with generic nitrile gloves. Does not come sterile, must be sterilized before use (10% bleach followed by 70% EtOH) |
|Trash bags for BSC|Teivio 1.2 Gallon 360 Counts Strong Trash Bags|Teivio|1|Can be substituted with generic.|
| Lab notebook | Durable, hardcover lab notebook | Generic | 1 | Dedicated to the lab space|
| Writing utensils | Sharpies and pens | Generic | 2| Dedicated to the lab extraction space. Not made of wood - must be able to be wiped down with bleach/EtOH.  |
|**Optional Equipment**|||			
|Repeater Pipetter: 10-300  μL|E1-ClipTip electronic single channel pipette, 10-300 μL|ThermoFisher|	1|Can be substituted with generic. Not required but reduces protocol time.|
| 300 μl repeater pipette tips | ClipTip 300 filtered sterile tips| Thermo Scientific| 2| Can be substituted with generic. Must fit repeater pipette. Must be sterile and filtered. |
|8-channel multichannel pipetter: 1-10 μL| Pipetman Multichannel P8X10|	Gilson|	1|Can be substituted with generic. Not required but reduces protocol time.|
| UV crosslinker | UV crosslinker AH (115V), 234100 | Boekel Scientific  | 1 | Recommended not required; can be substituted. |
| **Chemicals** |
| PCR master mix 2x|Phusion High-Fidelity PCR Master Mix with HF Buffer | New England BioLabs | 1300 |((μl per plate) Store at -20°C. |
| Forward primer | Custom oligo | IDT |130 |(μl per plate) Store at -20°C.|
| Reverse primer| Custom oligo | IDT | 130 |(μl per plate) Store at -20°C.
| Nuclease free water | UltraPure DNase/RNase-free distilled water | ThermoFisher | 689|(μl per plate) |
| rAlbumin |Molecular Biology Grade Recombinant Albumin | New England BioLabs | 65 |(μl per plate) Store at -20°C|
|DMSO|Phusion HF PCR Master Mix comes with DMSO|New England Biolabs| 78 |(μl per plate) Store at 4°C, must be warmed to room temperature to dissolve|
| Positive control| gBlocks HiFi Gene Fragments | IDT | 2 |(μl per plate) Store at -20°C |
| 70% EtOH | Molecular grade ethanol| Generic | 20 |(mL) |
| 10% bleach| Hypochlorite bleach |Clorox| 10 |(mL) Remake every ~5 days as bleach decomposes quickly at 10% concentration. |

------
# STANDARD OPERATING PROCEDURE

### Preparation


**Before PCR Setup:**

1. Sterilize workspaces and durable equipment, including pipettes within the BSC with 10% bleach. Then wipe down all surfaces and equipment with 70% EtOH.
4. If you have a UV crosslinker available, UV pipettes and tube racks regularly for 2 minutes.
5. Run the UV light in the BSC for 30 minutes before starting work.
6. Label all PCR plates both on the side of the plate and on the top of the foil (in the plate margins). Recommended labeling scheme includes plate name, primer, date of PCR and personnel initials.


### PCR

**Primer Sequences without Adapters**(not used): PCR primer sequences
(**target sequence bolded**)

| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
|ITS1 Sterling F| Forward |**TCCGTAGGTGAACCTGCGG** |
|ITS1 Sterling R| Reverse | **CATCCACCGCTGAAAGTTGTAA** |

**Primer Sequences Used**: PCR primer sequences with Illumina Adapters
(Adapter sequence + **target sequence bolded**)
| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
|ITS1 - Nex - F|Forward  | TCGTCGGCAGCGTCAGATGTGTATAAGAGACAG**TCCGTAGGTGAACCTGCGG** |
|Pn-ITS1 - Nex - R | Reverse | GTCTCGTGGGCTCGGAGATGTGTATAAGAGACAG**CATCCACCGCTGAAAGTTGTAA** |

**Reaction Mixture**: PCR reagents, volumes, initial and final concentrations

| Reagent |Volume (μL) per plate| Volume (μL) per reaction | Intial concentration| Final concentration|
| ----- | ----- | ----- |----- |----- |
| 2X Phusion Master Mix |1300| 12.5 |100% |50% |
| Forward Primer |130| 1.25|10 μM |0.5 μM |
| Reverse Primer |130|1.25 |10 μM | 0.5 μM |
| DMSO|78 | 0.75|100%|3% |
| Nuclease-Free Water |689|6.625 | N/A|N/A |
| rAlbumin|65| 0.625|20 µg/µL |0.5 µg/µL|
| Template DNA|N/A| 2 | 100%|8% |
| **Total**|**2392**| **25** | **N/A** |**N/A**|

This table breaks down the mixture per plate and per reaction. When running full plates (96-wells), each reagent volume was multipled by 104 (96+8 extra sample volumes to account for pipetting error) when preparing the final master mix.

**PCR Cycling Program**: 

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
|Initial denaturation|	98°C	|30s|	1X
|**Normal Cycling**||||
|Denaturation|	98°C|	10s|	35X|
|Annealing|	60°C|	30s	|35X|
|Extension 	|72°C	|45s	|35X|
|Final extension	|72°C	| 10min	|1X|
|Hold	|4°C	|∞	|1X|

**Step-by-Step Instructions:**

*Note: When possible, PCR set-up should be carried out in a separate pre-PCR space that is distinct from where the post-PCR space where thermocyclers are located and all post-PCR processing is performed. No equipment, consumables, or reagents should be shared between pre- and post-PCR spaces with a unidirectional flow of sample processing.*

1. Set out primers and positive control to thaw.
2. Vortex and spin down thawed positive control, primers, and nuclease free water. Then tap/flick AmpliTaq rather than vortexing before spinning down. Thawed reagents should be stored in a cooling block or fridge when not in use.
3. Pool reagents to make final master mix, as denoted in above in reagent mixture table.
4. Set out template DNA to thaw if frozen.
5. Aliquot 23 μL of final master mix into each well of the PCR plate. The plate should sit in a cold block to ensure the reagents remain at a low temperature.
6. Add 2 μL DNA template to each well (See [WhiteSterling phytoplankton ITS1 PCR Draft Protocol Sheet](https://docs.google.com/spreadsheets/d/15mxKM89S4NEhiMFIIUo3bYfYfHoavNpf0fki1TN-LCs/edit#gid=0)), but reserve two wells for the positive control and a no template control (NTC). 
8. To one well each, add 2 μL of the positive control and 2 μL of nuclease-free water for the NTC.
9. Seal the PCR plate with foil.
10. Spin down the plate, and then transport in cooler blocks before placing in thermocycler.
14.  Run thermocycler protocol.


## Quality control

1. Plates should be removed from the thermocycler  after the run completes and stored at 4°C until run on a gel. Storing the PCR product at -20˚C is ideal for 1-6 month term storage, while -80˚C is ideal for long-term storage.
2. Run gel visualization to confirm successful PCR. [NOAA-PMEL-OME-GelVisualization-Protocol pending]


**Positive Control**
A positive control is used in every PCR run to verify success of the PCR reaction. 2μL of positive control diluted to 10^3 copies/µL is used in place of template DNA. One well per plate is alotted for the positive control. The positive control used for WhiteSterling phytoplankton ITS1 is the Antartic freshwater diatom *Luticola ventricosa*. The reference sequence used to develop the positive control sequence can be found on GenBank: [Accession KY863469.1](https://www.ncbi.nlm.nih.gov/nuccore/KY863469.1)


|Positive Control Sequence|
|--------------------------|
|AAGTTGTTGCAGTTAAAAAGTCCGTAGGTGAACCTGCGGCTTAATTTGACTCAACACGGGGAAACTTACCAGGTCCAGACATAGTGAGGATTGACAGATTAAGAGCTCTTTCTTGATTCTATGGGTGGTGGTGCATGGCCGTTCTTAGTTGGTGGAGTGATTTGTCTGGTTAATTCCGTTAACGAACGAGACCTCTGCTTGCTAGTTACCCGCAGTAGTGATCCTTCACTGCTGTTTACCTTTACCGGTATAAGGGTTCTAGAAGTACATGTGCTTTGATAGGTGCAGGAAGATAGAGGCAATAACAGGTCTGTGATGCCCTTAGATGTTCTGGGCCGCACGCGCGCTACACTGATGCTTACAACTTTCAGCGGTGGATGAAAAGCCTGGGTAATCTTGA|

**Negative Control**

Nuclease-free water is used as a no template control (NTC) when setting up each PCR plate. One well per plate is alloted to a NTC. NTCs should be run in addition to both field blanks and extraction blanks.

## Basic troubleshooting guide

**Issue 1**: Streaking is observed for sample wells in gel but positive control band appears normal. 

**Solution**: Dilute the sample DNA to a 1:10 dilution with nuclease-free water. If smearing is still observed using a 1:10 dilution, dilute the DNA samples further to a 1:100 dilution. If the samples do not amplify under these conditions the sample likely is inhibited or has too little target DNA and thus is unlikely to yield valuable results. Alternative solutions include cleaning DNA extractions with a commercial clean up kit.

**Issue 2**: No bands were observed in the PCR, including the positive control.

**Solution**: The PCR likely failed. Check reagents to confirm they were not mishandled or expired and rerun the PCR. If positive control fails again, reagents or positive control are likely compromised. 

**Issue 3**: Band observed in no template control.

**Solution**: The PCR was likely contaminated. Sterilize lab space thoroughly and rerun with new aliquots of reagents.


## ACRONYMS AND ABBREVIATIONS

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|eDNA	|environmental DNA|
|PCR| Polymerase chain reaction |
|PPE    | Personal protective equipment |
|EtOH| Ethanol|
|ITS1  |Internal Transcribed Spacer region 1 |
|IDT| Integrated DNA Technologies
|NTC	|No template control
|BSC	|Biosafety cabinent
|OME	|Ocean Molecular Ecology
|PMEL	|Pacific Marine Environmental Laboratory
|NOAA|National Oceanic and Atmospheric Administration
|UW| University of Washington
|CICOES| Cooperative Institute for Climate, Ocean, & Ecosystem Studies
|MBON	|Marine Biodiversity Observation Network|
|MBARI| Monterey Bay Aquarium Research Institute|
|WC-OBON|West Coast Ocean Biomolecular Observing Network|

## GLOSSARY

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Field blank  | Sampling negative control. Typically distilled or reverse osmosis water run through a filter like an seawater eDNA sample to control for contamination in the field sampling step.  |
| Extraction blank  | Extraction negative control. Typically nuclease-free water or empty filter run through the DNA extraction process to control for contamination in the DNA extraction step.  |
| No template control | PCR negative control. Typically nuclease-free water loaded in place of a sample on a PCR to control for contamination in the PCR step. |
| Positive control  | PCR positive control. Typically a synthetic DNA strand, non-indigenous DNA extract, or intentionally designed mock community loaded in place of a sample on a PCR to control for contamination and index hopping in the PCR step. |

## REFERENCES

1. Sterling et al. (2022). Emerging harmful algal blooms caused by distinct seasonal assemblages of a toxic diatom. Limnology and Oceanography, 67(11), 2341–2359. https://doi.org/10.1002/lno.12189
2. White, T., T. Bruns, S. Lee, and J. Taylor. 1990. Amplification and direct sequencing of fungal ribosomal RNA genes for phylogenetics, p. 315–322. In PCR Protocols: A guide to methods and applications. Academic Press, Inc. [Link](https://msafungi.org/wp-content/uploads/2019/03/February-2013-Inoculum.pdf)

## APPENDIX A: DATASHEETS
Protocol Sample Sheet: [WhiteSterling phytoplankton ITS1 PCR Draft Protocol Sheet](https://docs.google.com/spreadsheets/d/15mxKM89S4NEhiMFIIUo3bYfYfHoavNpf0fki1TN-LCs/edit#gid=0)
