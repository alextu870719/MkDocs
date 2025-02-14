# KingFisher Flex Plant Genomic DNA Extraction

## **Buffers and Stocks**
=== "Extraction buffer"
    | **Component**              | **Final conc.** | **For 100.00 ml** |
    |----------------------------|-----------------|-------------------|
    | **CTAB**                   | 2%              | 2.00 g            |
    | **1 M Tris-HCl, pH 8.0**   | 100 mM          | 10.00 ml          |
    | **0.5 M EDTA, pH 8.0**     | 20 mM           | 4.00 ml           |
    | **5 M NaCl**               | 1.4 M           | 28.00 ml          |
    | **PVP40**                  | 1%              | 1.00 g            |
    | **ß-ME***                  | 0.50%           | 0.50 ml           |
    | **10 mg/ml RNase A***      | 100 µg/ml       | 1.00 ml           |
    | **20 mg/ml Proteinase K*** | 200 µg/ml       | 1.00 ml           |
    | **Add water to**           |                 | 100.00 ml         |
    
    *Add right before mixing with the sample.

=== "Binding buffer"
    | **Component**              | **Final conc.** | **For 1 L**       |
    |----------------------------|-----------------|-------------------|
    | **GuHCl**                  | 4.2 M           | 401.268 g         |
    | **EtOH**                   | 90%             | 900 ml            |
    | **Add water to**           |                 | 1 L               |

    *Dissolve and stir at 65˚C overnight.

=== "Wash buffer"
    | **Component**              | **Final conc.** | **For 1 L**       |
    |----------------------------|-----------------|-------------------|
    | **Ethanol**                | 80%             | 800 ml            |
    | **Add water to**           |                 | 1 L               |

=== "TE buffer"
    | **Component**              | **Final conc.** | **For 100.00 ml** |
    |----------------------------|-----------------|-------------------|
    | **1 M Tris-HCl, pH 8.0**   | 10 mM           | 1 ml              |
    | **0.5 M EDTA, pH 8.0**     | 1 mM            | 0.2 ml            |
    | **Add water to**           |                 | 100.00 ml         |

## **Other materials:**
- Isopropanol
- Magnetic bead: any silica-coated beads

## Procedure:
1. Collect approximately 100 mg of plant tissue in two 2 ml collection tubes with two 4 mm beads. Freeze the samples at -80˚C in a refrigerator or liquid nitrogen.
2. (Optional) Lyophilize the samples overnight to enhance extraction, especially for root samples (Open the lid and cover with press ‘n seal wrap and poke a hole in it).
3. Homogenize the samples using a MiniG at 1000 rpm for 15 seconds. Re-freeze the samples and repeat the homogenization process until all the samples are ground into a powder.
4. Add 700 µL of extraction buffer to the homogenized samples and mix by vortex.
5. Incubate the samples at 65 °C for at least 30 minutes. A longer incubation time (3 hours or overnight) is recommended to extract more DNA.
6. (Optional) Centrifuge at top speed for 5 minutes and transfer the supernatant into a new tube.
7. Add 700 µL of chloroform to the samples and mix by vortex.
8. Spin the samples at 12,000 g for 5 minutes.
9. Prepare the following plates:
    - **Sample-plate** ([96-deep well plate](https://www.thermofisher.com/order/catalog/product/95040450)):
        - 400 µL supernatant from step 8
        - 400 µL binding buffer
        - 160 µL isopropanol
        - 40 µL magnetic beads (Mix well!!!!!)
    - **Wash-plate-1** (96-deep well plate): 1 ml isopropanol
    - **Wash-plate-2** (96-deep well plate): 1 ml wash buffer
    - **Wash-plate-3** (96-deep well plate): 1 ml wash buffer
    - **Wash-plate-4** (96-deep well plate): 1 ml wash buffer
    - **Elution-plate** ([Standard 96-well plate](https://www.thermofisher.com/order/catalog/product/97002540)): 100 µL / 150 µl TE buffer (after evaporation, only ~70 µl / 110 µl remain)
    - **Tip-comb-plate:** [KingFisher 96 Tip Comb for DW Magnets](https://www.thermofisher.com/order/catalog/product/97002534) in a Standard 96-well plate.
10. Run the DNA_Extraction_100 µl/150 µl protocol (1 hour) located in KingFisher Flex machine.
        
    !!! info "Note"
        **The protocol is based on elution volumes.**

## Notes:
1. **Multichannel Pipette and Reservoir Usage:**
    - A multichannel pipette with reservoirs is utilized to dispense reagents efficiently.
2. **3D-Printed Rack Compatibility:**
    - You can use a 3D-printed rack designed for multichannel pipettes to transfer sample supernatant. The numbering system follows:
        - No.1, 3, 5, 7 for Row A, C, E, G.
        - No.2, 4, 6, 8 for Column B, D, F, H.
    - This setup allows transferring 8 samples within just 2 pipetting steps.
3. **Plate Preparation:**
    - Plates can be prepared and sealed with Press’n Seal to prevent evaporation during processing.
4. **Wash Buffer Information:**
    - The wash buffer is formulated with 80% EtOH. Even when evaporated, it retains more than 70% EtOH concentration, ensuring sufficient potency for its intended use.
5. **TE Buffer Recommendation:**
    - TE buffer is highly recommended for DNA elution due to the following reasons:
        - DNA is not very soluble in pure water.
        - TE buffer ensures compatibility with downstream applications such as PCR, qPCR, and enzymatic assays.
6. **Sample volume:**
    - Although 700 µL of extraction buffer is used, only 400 µL is required for DNA binding. This amount is adequate because the binding buffer must maintain a 1:1 ratio with the DNA supernatant. Additionally, the maximum volume per well in a 96-well deep plate is 1 mL, and using 400 µL ensures you stay within this limit while simplifying pipetting to prevent moving debris.