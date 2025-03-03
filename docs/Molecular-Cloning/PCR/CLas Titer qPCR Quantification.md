# CLas Titer qPCR Quantification

<script>
function calculateVolumes() {
    var tubes = document.getElementById("numTubes").value;
    document.getElementById("iTaq").innerText = (5.0 * tubes).toFixed(1) + " µl";
    document.getElementById("forwardPrimer").innerText = (0.4 * tubes).toFixed(1) + " µl";
    document.getElementById("reversePrimer").innerText = (0.4 * tubes).toFixed(1) + " µl";
    document.getElementById("h2o").innerText = (2.2 * tubes).toFixed(1) + " µl";
    document.getElementById("dna").innerText = (2.0 * tubes).toFixed(1) + " µl";
    document.getElementById("h2oExtract").innerText = (3.2 * tubes).toFixed(1) + " µl";
    document.getElementById("dnaExtract").innerText = (1.0 * tubes).toFixed(1) + " µl";
    document.getElementById("iTaqExtract").innerText = (5.0 * tubes).toFixed(1) + " µl";
    document.getElementById("forwardPrimerExtract").innerText = (0.4 * tubes).toFixed(1) + " µl";
    document.getElementById("reversePrimerExtract").innerText = (0.4 * tubes).toFixed(1) + " µl";
}
</script>

<label for="numTubes">Number of Tubes:</label>
<input type="number" id="numTubes" name="numTubes" min="1" value="1" oninput="calculateVolumes()">

### Standard PCR Mix

| Component                                                                                                                   | Volume per Tube | Total Volume | Notes                                               |
|-----------------------------------------------------------------------------------------------------------------------------|-----------------|--------------|-----------------------------------------------------|
| iTaq Universal SYBR Green Supermix [1725125](https://www.bio-rad.com/en-us/sku/1725125-itaq-universal-sybr-green-supermix-5-000-x-20-ul-rxns-50-ml-10-x-5-ml?ID=1725125) | 5.0 µl          | <span id="iTaq">5.0 µl</span> |                                                     |
| Forward Primer                                                                                                              | 0.4 µl          | <span id="forwardPrimer">0.4 µl</span> |                       |
| Reverse Primer                                                                                                              | 0.4 µl          | <span id="reversePrimer">0.4 µl</span> |                      |
| H2O                                                                                                                         | 2.2 µl          | <span id="h2o">2.2 µl</span> |                                                     |
| DNA                                                                                                                         | 2.0 µl          | <span id="dna">2.0 µl</span> | (12.5 ng/µl citrus DNA extraction, total 25 ng)     |

### Extract PCR Mix

| Component                                                                                                                   | Volume per Tube | Total Volume | Notes                                               |
|-----------------------------------------------------------------------------------------------------------------------------|-----------------|--------------|-----------------------------------------------------|
| iTaq Universal SYBR Green Supermix [1725125](https://www.bio-rad.com/en-us/sku/1725125-itaq-universal-sybr-green-supermix-5-000-x-20-ul-rxns-50-ml-10-x-5-ml?ID=1725125) | 5.0 µl          | <span id="iTaqExtract">5.0 µl</span> |                                                     |
| Forward Primer                                                                                                              | 0.4 µl          | <span id="forwardPrimerExtract">0.4 µl</span> |                       |
| Reverse Primer                                                                                                              | 0.4 µl          | <span id="reversePrimerExtract">0.4 µl</span> |                      |
| H2O                                                                                                                         | 3.2 µl          | <span id="h2oExtract">3.2 µl</span> |                                                     |
| DNA                                                                                                                         | 1.0 µl          | <span id="dnaExtract">1.0 µl</span> | (12.5 ng/µl citrus DNA extraction, total 12.5 ng)   |

### Primers

| ID  | Primer       | Sequence                       | Description                                                                                                      |
|-----|--------------|-------------------------------|------------------------------------------------------------------------------------------------------------------|
| 304 | RNRf         | CATGCTCCATGAAGCTACCC          | Forward primer for the 5-copy nrdB gene of CLas, for qPCR reactions. Amplicon size 80bp                           |
| 305 | RNRr         | GGAGCATTTAACCCCACGAA          | Reverse primer for the 5-copy nrdB gene of CLas, to be used in qPCR. Amplicon size 80bp                           |
| 29  | CsiGAPC2-F   | TCTTGCCTGCTTTGAATGGA          | Forward primer for the glyceraldehyde 3-phosphate dehydrogenase (GAPC2 based on Mafra et al. 2012; orange1.1g024565m.g) of Citrus species. Used as an internal control in PCR reactions. Amplicon size is 78 bp |
| 30  | CsiGAPC2-R   | TGTGAGGTCAACCACTGCGACAT       | Reverse primer for the glyceraldehyde 3-phosphate dehydrogenase (GAPC2 based on Mafra et al. 2012; orange1.1g024565m.g) of Citrus species. Used as an internal control in PCR reactions. |