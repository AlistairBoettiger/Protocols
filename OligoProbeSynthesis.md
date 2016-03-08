## Rapid Oligo Probe Synthesis

### Limited Cycle PCR (50 uL)
1. Prepare on ice:
 * 15 uL ddH2O
 * 25 uL [Phusion Hot-start Master Mix](https://www.neb.com/products/m0536-phusion-hot-start-flex-2x-master-mix)
 * 2.5 uL Fwd primer (10 uM)
 * 2.5 uL Rev-T7 primer (10 uM)
 * 2.5 uL library (1:50 dilution)
 * 2.5 uL 20x EvaGreen (Biotium)
2. Run reaction on QPCR machine, stop reactions for each tube while amplification is still in the exponential growth phase (before it reaches the saturation phase).  A calibration run may be necessary first to identify when this will happen.
3. **Recommended:** Test PCR by running 2 uL out on a 2% agarose Na Borax gel.  Use gel green spiked 6x orange loading dye. There should only be a single band if the reaction does not saturate. 

### PCR cleanup
1. in a 1.5 uL tube, add 350 uL Zymo DNA binding buffer to 50 uL of PCR product
2. Transfer to a zymo DCC-5 column, spin at >10,000g, 30s
3. Add 200 uL DNA Wash Buffer to column, spin at >10,000g, 30s
4. Repeat the wash step.
5. Discard flow-through by aspirating dry the collection tube. Then spin at >10,000g 1 min to remove residual buffer.
6. Transfer column to clean 1.5 mL tube and elute DNA in 11 uL ddH2O

###  T7 reaction (30 uL reaction)
1. Prepare on ice in RNase free environment:
  * 10 uL DNA from PCR 
  * 10 uL of NEB NTP buffer mix ([NEB T7 Quick High Yield kit](https://www.neb.com/products/e2050-hiscribe-t7-quick-high-yield-rna-synthesis-kit))
  * 2uL T7 Pol Mix (NEB T7 High Yield kit)
  * 1 uL [RNasin Plus](https://www.promega.com/resources/protocols/product-information-sheets/n/rnasin-plus-rnase-inhibitor-protocol/) (RNase inhibitor)
2. Incubate at 37C for 4 - 16 hrs.

### RT reaction (70 uL reaction)
1. Prepare on ice in RNase free environment:
 * 0 uL Nuclease free H2O
 * 7 uL dNTPs
 * 14 uL RT buffer
 * 10 uL 100 uM labeled primer 
 * 5 uL or less [Maxima](https://www.thermofisher.com/order/catalog/product/EP0751) RT enzyme
 * 4 uL [RNasin Plus](https://www.promega.com/resources/protocols/product-information-sheets/n/rnasin-plus-rnase-inhibitor-protocol/) (RNase inhibitor)
 * 30 uL RNA from T7 reaction 
2. Incubate at 50C for 1 hour.  (No pre-denaturing step)
3. Digest remaining RNA 
    * mix 1:1 0.5 M EDTA and 1 M NaOH.  Add 50 uL per sample
    * Heat at 95C for 10 min 
4. **Recommended:** Test RT by running 2 uL out on a 15% urea TBE gel.  Use urea loading buffer.  Run gel in 60C waterbath to ensure probe is denatured.

### Probe Cleanup

1. add 240 uL Oligo Binding buffer to each tube (2x the volume of sample) and mix. 
2. Split volume evenly into two 1.5 mL tubes (120 uL each), each containing containing 480 uL of 100% EtOH and mix (the total ethanol volume should be 8x the original sample volume).
3. Transfer the solution to a DCC-25 column (can reuse, see below*), spin to elute and discard flow-through. Run sequentially to bind both volumes (600 uL each). 
4. Add 750 uL DNA Wash Buffer.  Spin at >10,000g and discard flow through.
5. Spin column to remove excess buffer (an empty, resusable waste column is recommended)
6. Transfer column to clean 1.5 uL tube and elute in 30 uL ddH2O.
7. Measure final probe concentration
8.  **NOTE:** Use Zymo DCC-100 columns if using a larger scale RT prep (1-10 nmol of primer).  Elute in 100 uL and concentrate sample using seedVac. Scale up washes as directed.

