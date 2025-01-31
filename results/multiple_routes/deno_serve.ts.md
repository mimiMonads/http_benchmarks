# Name: Deno.serve 
  
  ### Version: Deno 1.35.0
  ### Deno version: 1.35.0

## Summary
<table>
<tr>
    <td align="center" colspan="4">Throughput (rps)</td>
    <td align="center" colspan="3">Latency (ms)</td>
</tr>
<tr>
    <td align="center">Mean</td>
    <td align="center">Max</td>
    <td align="center">Standard deviation</td>
    <td align="center">Size per second</td>
    <td align="center">Avg</td>
    <td align="center">Min</td>
    <td align="center">Max</td>
</tr>
<tr>
    <td>120.29k</td>
    <td>129.16k</td>
    <td>14.13k</td>
    <td>2.17 MiB</td>
    <td>0.51</td>
    <td>0.41</td>
    <td>1.32</td>
</tr>
</table>

## Percentiles

<table>
<tr>
  <td align="center">Mesaure</td>
  <td align="center">p10</td>
  <td align="center">p25</td>
  <td align="center">p50</td>
  <td align="center">p75</td>
  <td align="center">p90</td>
  <td align="center">p95</td>
  <td align="center">p99</td>
</tr>
<tr>
  <td>Throughput (rps)</td>
  <td>86433.65k</td>
  <td>86433.65k</td>
  <td>86433.65k</td>
  <td>86433.65k</td>
  <td>129159.96k</td>
  <td>129159.96k</td>
  <td>129159.96k</td>
</tr>
<tr>
  <td>Latency (ms)</td>
  <td>0.45</td>
  <td>0.45</td>
  <td>0.45</td>
  <td>0.45</td>
  <td>0.60</td>
  <td>0.66</td>
  <td>0.80</td>
</tr>
</table>

## Individual test steps

### Throughput

<table>
<tr>
  <td align="center" rowspan="2">Step</td>
  <td align="center" rowspan="2">Mean</td>
  <td align="center" rowspan="2">Max</td>
  <td align="center" rowspan="2">Standard deviation</td>
  <td align="center" rowspan="2">Size per second</td>
  <td align="center" colspan="7">Percentiles</td>
</tr>
<tr>
  <!-- still Step -->
  <!-- still Mean -->
  <!-- still Max -->
  <!-- still Standard deviation -->
  <!-- still Size per second -->
  <td align="center">p10</td>
  <td align="center">p25</td>
  <td align="center">p50</td>
  <td align="center">p75</td>
  <td align="center">p90</td>
  <td align="center">p95</td>
  <td align="center">p99</td>
</tr>
<tr>
  <td>/random_number</td>
  <td>120.29k</td>
  <td>129.16k</td>
  <td>14.13k</td>
  <td>2.17</td>
  <td>86433.65k</td>
  <td>86433.65k</td>
  <td>86433.65k</td>
  <td>86433.65k</td>
  <td>129159.96k</td>
  <td>129159.96k</td>
  <td>129159.96k</td>
</tr><tr>
  <td>/hello_world</td>
  <td>136.47k</td>
  <td>145.54k</td>
  <td>13.20k</td>
  <td>1.47</td>
  <td>109736.38k</td>
  <td>109736.38k</td>
  <td>109736.38k</td>
  <td>109736.38k</td>
  <td>145538.96k</td>
  <td>145538.96k</td>
  <td>145538.96k</td>
</tr><tr>
  <td>/plus_1</td>
  <td>136.40k</td>
  <td>147.05k</td>
  <td>18.67k</td>
  <td>0.27</td>
  <td>94064.53k</td>
  <td>94064.53k</td>
  <td>94064.53k</td>
  <td>94064.53k</td>
  <td>147049.97k</td>
  <td>147049.97k</td>
  <td>147049.97k</td>
</tr><tr>
  <td>/count</td>
  <td>134.10k</td>
  <td>147.13k</td>
  <td>25.20k</td>
  <td>0.14</td>
  <td>74266.79k</td>
  <td>74266.79k</td>
  <td>74266.79k</td>
  <td>74266.79k</td>
  <td>147125.32k</td>
  <td>147125.32k</td>
  <td>147125.32k</td>
</tr><tr>
  <td>/minus_1</td>
  <td>137.45k</td>
  <td>147.34k</td>
  <td>13.28k</td>
  <td>0.27</td>
  <td>110964.58k</td>
  <td>110964.58k</td>
  <td>110964.58k</td>
  <td>110964.58k</td>
  <td>147337.62k</td>
  <td>147337.62k</td>
  <td>147337.62k</td>
</tr></table>

### Latency

<table>
<tr>
  <td align="center" rowspan="2">Step</td>
  <td align="center" rowspan="2">Avg</td>
  <td align="center" rowspan="2">Min</td>
  <td align="center" rowspan="2">Max</td>
  <td align="center" colspan="7">Percentiles</td>
</tr>
<tr>
  <!-- still Avg -->
  <!-- still Min -->
  <!-- still Max -->
  <td>p10</td>
  <td>p25</td>
  <td>p50</td>
  <td>p75</td>
  <td>p90</td>
  <td>p95</td>
  <td>p99</td>
</tr>
<tr>
  <td>/random_number</td>
  <td>0.51</td>
  <td>0.41</td>
  <td>1.32</td>
  <td>0.45</td>
  <td>0.45</td>
  <td>0.45</td>
  <td>0.45</td>
  <td>0.60</td>
  <td>0.66</td>
  <td>0.80</td>
</tr><tr>
  <td>/hello_world</td>
  <td>0.45</td>
  <td>0.37</td>
  <td>1.24</td>
  <td>0.41</td>
  <td>0.41</td>
  <td>0.41</td>
  <td>0.41</td>
  <td>0.49</td>
  <td>0.54</td>
  <td>0.63</td>
</tr><tr>
  <td>/plus_1</td>
  <td>0.44</td>
  <td>0.37</td>
  <td>1.48</td>
  <td>0.40</td>
  <td>0.40</td>
  <td>0.40</td>
  <td>0.40</td>
  <td>0.48</td>
  <td>0.52</td>
  <td>0.61</td>
</tr><tr>
  <td>/count</td>
  <td>0.44</td>
  <td>0.37</td>
  <td>1.12</td>
  <td>0.40</td>
  <td>0.40</td>
  <td>0.40</td>
  <td>0.40</td>
  <td>0.48</td>
  <td>0.53</td>
  <td>0.61</td>
</tr><tr>
  <td>/minus_1</td>
  <td>0.45</td>
  <td>0.37</td>
  <td>1.19</td>
  <td>0.41</td>
  <td>0.41</td>
  <td>0.41</td>
  <td>0.41</td>
  <td>0.49</td>
  <td>0.53</td>
  <td>0.62</td>
</tr></table>