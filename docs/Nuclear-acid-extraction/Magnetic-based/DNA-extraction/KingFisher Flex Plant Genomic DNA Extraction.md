## **Buffers and Stocks**
**5X diluted Silica-coated Magnetic Beads**

| Component                     | For 50 ml |
|-------------------------------|-----------|
| Silica-coated Magnetic Beads  | 10 ml     |
| Add TE buffer to              | 50 ml     |

* [Home-Made Magnetic Beads](../Home-made-magnetic-beads.md)

**TE buffer**

| Component              | Final conc. | For 50 ml |
|------------------------|-------------|-----------|
| 1 M Tris-HCl, pH 8.0   | 10 mM       | 0.5 ml    |
| 0.5 M EDTA, pH 8.0     | 1 mM        | 0.1 ml    |
| Add water to           |             | 50 ml     |

**1.5X GITC Lysis Buffer**

| Component       | Final conc. | For 50 ml |
|-----------------|-------------|-----------|
| GITC [(G54000)](https://www.rpicorp.com/products/biochemicals/biochemical-reagents/guanidine-thiocyanate-250-g.html) | 6 M         | 35.46 g   |
| 1 M Tris HCl, pH 8.0 | 75 mM       | 3.75 ml   |
| Sarkosyl        | 3%          | 1.5 g     |
| EDTA            | 30 mM       | 3 ml of 0.5 M stock |
| Adjust pH with HCl to 7.6-8.0 and adjust the volume with water to 50 ml |

* Heat at 65˚C to dissolve.

**TNES Buffer**

| Component       | Final conc. | For 50 ml |
|-----------------|-------------|-----------|
| 1 M Tris HCl, pH 8.0 | 100 mM      | 5 ml      |
| 5 M NaCl            | 25 mM       | 0.25 ml   |
| 0.5 M EDTA          | 10 mM       | 1 ml      |
| SDS                 | 10% w/v     | 5 g       |

* Add 25 µl of RNase A (10 mg/ml) per 1 ml TNES Buffer before use.

**Wash Buffer**

| Component              | Final conc. | For 1 L |
|------------------------|-------------|---------|
| Ethanol                | 80%         | 800 ml  |
| Add water to           |             | 1 L     |

## **Other materials**

- Isopropanol

## **Procedures**

1. Collect approximately 100 mg of plant tissue in two 2 ml collection tubes or 8 strip collection tube with two 4 mm beads. Freeze the samples at -80˚C in a refrigerator or liquid nitrogen.

    !!! info "For 8 strip collection tube, don't sample excessive tissue"


2. (**Highly recommend**) Lyophilize the samples overnight to enhance extraction, especially for root samples (Open the lid and cover with press ‘n seal wrap and poke a hole in it).

3. Homogenize the samples using a MiniG at 1500 rpm for 45 seconds. Re-freeze the samples and repeat the homogenization process until all the samples are ground into a powder.

    !!! info "Make sure the cap is completely sealed"

4. Add 200 µl of TNES Buffer with RNase A to the homogenized samples and mix by vortex.

    !!! info "When using 8 strip collection tube, tilt-tap the tube first to prevent powder aggregate at the bottom"

5. Incubate the samples at 37 °C for 15 minutes. A longer incubation time could degrade DNA.

    !!! info "When using 8 strip collection tube, briefly spin down the sample to prevent cross contamination"

6. Add 400 µl of 1.5X GITC Lysis Buffer, mix by vortex, and incubate for 5 min at RT.

    !!! info "When using 8 strip collection tube, briefly spin down the sample to prevent cross contamination"

7. Add 300 µl of Chloroform and mix by vortex.

8. Centrifuge at top speed for 5 min or 4000 g for 10 min (8 strip collection tube).

9. Prepare the following plates:
    - **Sample-plate** ([96-deep well plate](https://www.thermofisher.com/order/catalog/product/95040450){target="_blank"}):
        - 444 µL isopropanol
        - 222 µL 5X Silica-coated diluted magnetic beads (Mix well!!!!!)
        - 333 µL DNA sample supernatant from step 8
    - **IPA-plate** (96-deep well plate): 1 ml Isopropanol
    - **Wash-plate-1** (96-deep well plate): 1 ml Wash Buffer
    - **Wash-plate-2** (96-deep well plate): 1 ml Wash Buffer
    - **Wash-plate-3** (96-deep well plate): 1 ml Wash Buffer
    - **Elution-plate** ([Standard 96-well plate](https://www.thermofisher.com/order/catalog/product/97002540){target="_blank"}): 100 µL / 150 µl nuclease-free Water (after evaporation, only ~40 µl / 90 µl remain)
    - **Tip-comb-plate:** [KingFisher 96 Tip Comb for DW Magnets](https://www.thermofisher.com/order/catalog/product/97002534){target="_blank"} in a Standard 96-well plate.

10. Run the **DNA_Extraction_General** protocol (1 hour) located in KingFisher Flex machine.
        
## **Notes**

* In this method, magnetic beads were diluted with TE buffer, therefore, you can use multichannel pipetteman to dispense.
