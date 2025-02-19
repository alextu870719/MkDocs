## **Materials**
* 250 ml LB in 500 ml erlenmeyer flask

    !!! info "Note"
        250 ml LB can produce 250 tube of competent cell (100 μl).


* 1/10 original volume of mTSS (25 ml).

=== "mTSS" 
    | Ingredients | Weight (g) for 100 ml |
    | --- | --- |
    | Tryptone | 1 |
    | Yeast extract | 0.5 |
    | NaCl | 1 |
    | PEG3350 | 10 |
    | DMSO | 5 ml |
    | MgSO4.7H2O | 1.232 |
    | Glycerol | 10 ml |

    !!! note
        Filter sterilization

## **Day 1**

* Streak *E. coli* stock from -80℃ on LB agar with appropriate antibiotic to get single colony at 37˚C.

Choose suitable *E. coli* strain

??? info "Lab strains of *E. coli*"
    | Strain | Natural resistance | Primary Use | Genotype |
    | --- | --- | --- | --- |
    | ccdB Survival 2 T1R |   | TOP10 derivative. For propagating plasmids expressing the ccdB gene (important in Gateway cloning). | F-mcrA Δ(mrr-hsdRMS-mcrBC) Φ80lacZΔM15 ΔlacX74 recA1 araΔ139 Δ(ara-leu)7697 galU galK rpsL (StrR) endA1 nupG fhuA::IS2 |
    | DB3.1 | Streptomycin  | HB101 derivative. For propagating plasmids expressing the ccdB gene (important in Gateway cloning). | F- gyrA462 endA1 glnV44 Δ(sr1-recA) mcrB mrr hsdS20(rB-, mB-) ara14 galK2 lacY1 proA2 rpsL20(Smr) xyl5 Δleu mtl1 |
    | DH10B | Streptomycin | MC1061 derivative. General cloning and storage, blue/white screening, leucine auxotroph. | F- endA1 recA1 galE15 galK16 nupG rpsL ΔlacX74 Φ80lacZΔM15 araD139 Δ(ara,leu)7697 mcrA Δ(mrr-hsdRMS-mcrBC) λ- |
    | DH5alpha |   | General cloning and storage of common plasmids, blue/white screening. | F- endA1 glnV44 thi-1 recA1 relA1 gyrA96 deoR nupG Φ80dlacZΔM15 Δ(lacZYA-argF)U169, hsdR17(rK- mK+), λ– |
    | HB101 | Streptomycin | Hybrid of E. coli K12 and E. coli B (mostly K12, though), common lab strain for cloning and storage of pBR322 plasmids.  | F- mcrB mrr hsdS20(rB- mB-) recA13 leuB6 ara-14 proA2 lacY1 galK2 xyl-5 mtl-1 rpsL20(SmR) glnV44 λ- |
    | JM109 |   | General cloning and plasmid maintenance, blue/white screening, partly restriction-deficient; good strain for cloning repetitive DNA. | endA1 glnV44 thi-1 relA1 gyrA96 recA1 mcrB+ Δ(lac-proAB) e14- [F' traD36 proAB+ lacIq lacZΔM15] hsdR17(rK-mK+) |
    | JM110  | Streptomycin  | For storing plasmids that should not be Dam or Dcm methylated, allows for methylation sensitive restriction enzymes to cut the plasmid after preparation. | rpsL thr leu thi lacY galK galT ara tonA tsx dam dcm glnV44 Δ(lac-proAB) e14- [F' traD36 proAB+ lacIq lacZΔM15] hsdR17(rK-mK+)  |
    | MC1061 | Streptomycin | Parent of DH10B/TOP10 and derived strains, common lab cloning and storage strain. | F- Δ(ara-leu)7697 [araD139]B/r Δ(codB-lacI)3 galK16 galE15 λ- e14- mcrA0 relA1 rpsL150(strR) spoT1 mcrB1 hsdR2(r-m+)  |
    | MG1655  |   | Wild type K-12 strain; first published sequence of an E. coli K-12 strain. | F- λ- ilvG- rfb-50 rph-1 |
    | NEB Stable |   | For cloning into and storage of lentiviral and retroviral vectors or cloning or repeated sequences with the potential to recombine.  | F' proA+B+ lacIq ∆(lacZ)M15 zzf::Tn10 (TetR) ∆(ara-leu) 7697 araD139 fhuA ∆lacX74 galK16 galE15 e14-  Φ80dlacZ∆M15 recA1 relA1 endA1 nupG rpsL (StrR) rph spoT1 ∆(mrr-hsdRMS-mcrBC) |
    | Pir1  |   | For cloning and maintenance of a plasmids with R6Kγ origin; contains a mutant allele of the pir gene that maintains the plasmids at ~250 copies per cell.  | F- ∆lac169 rpoS(Am) robA1 creC510 hsdR514 endA recA1 uidA(∆MluI)::pir-116  |
    | Stbl2 |   | JM109-derived. For cloning into and storage of lentiviral and retroviral vectors or cloning or repeated sequences with the potential to recombine.  | F- endA1 glnV44 thi-1 recA1 gyrA96 relA1 Δ(lac-proAB) mcrA Δ(mcrBC-hsdRMS-mrr) λ-  |
    | Stbl3  | Streptomycin | Derived from HB101. For cloning into and storage of lentiviral and retroviral vectors or cloning or repeated sequences with the potential to recombine. This strain is endA+, so column-based DNA preps require an additional wash step. | F- glnV44 recA13 mcrB mrr hsdS20(rB-, mB-) ara-14 galK2 lacY1 proA2 rpsL20 xyl-5 leu mtl-1 |
    | Stbl4 |   | Electrocompetent cells for cloning and storage of unstable DNA and lentiviral/retroviral vectors. Used by Addgene for pooled library amplification. | F' mcrA Δ(mcrBC-hsdRMS-mrr) recA1 endA1 gyrA96 gal-thi-1 supE44 λ-relA1 Δ(lac-proAB)/F' proAB+lacIqZΔM15 Tn10 (TetR) |
    | TOP10 | Streptomycin | MC1061 derivative. General cloning and storage, blue/white screening. | F- mcrA Δ(mrr-hsdRMS-mcrBC) φ80lacZΔM15 ΔlacX74 nupG recA1 araD139 Δ(ara-leu)7697 galE15 galK16 rpsL(StrR) endA1 λ- |
    | XL1 Blue | Tetracycline | Blue/white screening and routine cloning, nalidixic acid resistant. | endA1 gyrA96(nalR) thi-1 recA1 relA1 lac glnV44 F'[ ::Tn10 proAB+ lacIq Δ(lacZ)M15] hsdR17(rK- mK+)  |
    | XL10 Gold | Tetracycline and Chloramphenicol | High competency cloning and propagation of large plasmids, ligated DNA, and libraries, nalidixic acid resistant.  | endA1 glnV44 recA1 thi-1 gyrA96 relA1 lac Hte Δ(mcrA)183 Δ(mcrCB-hsdSMR-mrr)173 tetR F'[proAB lacIqZΔM15 Tn10(TetR Amy CmR)]  |


## **Day 2**

* Pick a single colony and culture in 5-10 ml LB containing appropriate antibiotic at 37℃, 200 rpm, overnight.

## **Day 3**

1. Transfer 2.5 ml overnight *E. coli* culture to 250 ml LB in 500 ml erlenmeyer flask.
2. Culture 2-3 hours at 37℃, 200 rpm to reach OD600 = **0.3-0.4.**

    !!! note
        * *E. coli* generation time is ~20 min.

        * Measure the OD600 value every 0.5-1 hour.

3.  Incubate the *E. coli* culture on ice and pre-chill the refrigerated centrifuge at 4˚C, 1000 g, 10 min.

    !!! note
        **The following steps are all on ice.**

4. Centrifuge *E. coli* culture at 4℃, 1000 g, 10 min.
5. Remove the supernatant.
6. Resuspend all the pellet in 25 ml ice-cold mTSS with pipette carefully.
    
    !!! note
        If you need high concentration competent cell, resuspend in 12.5 ml mTSS.

7. Aliquot the competent cell for 100 μl in 1.7 ml microtube.

    !!! note
        All materials need to be ice-cold and performed on ice.

8. Freeze the competent cell in liquid nitrogen and store at -80℃.


## **Reference**
1. Chung, C. T., Niemela, S. L., & Miller, R. H. (1989). One-step preparation of competent Escherichia coli: transformation and storage of bacterial cells in the same solution. Proceedings of the National Academy of Sciences, 86(7), 2172-2175.