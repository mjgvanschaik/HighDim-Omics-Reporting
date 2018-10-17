# HighDim-Omics-Reporting
This repository contains a collection of ideas and scripts to report output from models analysing high-dimensional omics. Focus lies on questions such as how to report model output for many variables and models, etc. 

## Example of a table

<table style="text-align:center"><caption><strong>Fake data glycan peaks p-values</strong></caption>
<tr><td colspan="7" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td>GP</td><td>Age</td><td>Complications1</td><td>CTR_DIAB1</td><td>Metabolic1</td><td>Sex1</td></tr>
<tr><td colspan="7" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">1</td><td>GP1</td><td>0.685</td><td>0.796</td><td>0.654</td><td>0.402</td><td>0.616</td></tr>
<tr><td style="text-align:left">2</td><td>GP10</td><td>0.593</td><td>0.055</td><td>0.495</td><td>0.891</td><td>0.062</td></tr>
<tr><td style="text-align:left">3</td><td>GP2</td><td>0.198</td><td>0.667</td><td>0.295</td><td>0.670</td><td>0.626</td></tr>
<tr><td style="text-align:left">4</td><td>GP3</td><td>0.908</td><td>0.297</td><td>0.554</td><td>0.469</td><td>0.095</td></tr>
<tr><td style="text-align:left">5</td><td>GP4</td><td>0.989</td><td>0.732</td><td>0.244</td><td>0.798</td><td>0.197</td></tr>
<tr><td style="text-align:left">6</td><td>GP5</td><td>0.552</td><td>0.008</td><td>0.567</td><td>0.067</td><td>0.909</td></tr>
<tr><td style="text-align:left">7</td><td>GP6</td><td>0.989</td><td>0.087</td><td>0.501</td><td>0.307</td><td>0.937</td></tr>
<tr><td style="text-align:left">8</td><td>GP7</td><td>0.600</td><td>0.553</td><td>0.892</td><td>0.566</td><td>0.334</td></tr>
<tr><td style="text-align:left">9</td><td>GP8</td><td>0.551</td><td>0.637</td><td>0.433</td><td>0.097</td><td>0.145</td></tr>
<tr><td style="text-align:left">10</td><td>GP9</td><td>0.331</td><td>0.824</td><td>0.425</td><td>0.140</td><td>0.866</td></tr>
<tr><td colspan="7" style="border-bottom: 1px solid black"></td></tr><tr><td colspan="7" style="text-align:left">alpha = 0.05</td></tr>
</table>

## Example of a plot

![Gene effects](https://raw.githubusercontent.com/mjgvanschaik/HighDim-Omics-Reporting/master/plots/30genes_effectsize.png)
