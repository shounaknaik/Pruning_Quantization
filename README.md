# Pruning, Quantization

Pruning and Quantization of VGG16 Network for Image Classification on CIFAR10 dataset. This involves both fine-grained pruning and channel pruning. The model is also K-means quantized.

## VGG Network 
<img src="./images/vggnet.png" align = "center">

## Pruning Visualization

<table>
  <tr>
      <td align = "center"> <img src="./images/weight_pruning.png"> </td>
  </tr>
  <tr>
      <td align = "center"> Magnitude based Fine Grained Pruning </td>
  </tr>
</table>

<table>
  <tr>
      <td align = "center"> <img src="./images/before_histo.png"> </td>
      <td align = "center"> <img src="./images/after_histo.png"> </td>
  </tr>
  <tr>
      <td align = "center"> Before Pruning </td>
      <td align = "center"> After Pruning </td>
  </tr>
</table>

## Quantization Visualization

<table>
  <tr>
      <td align = "center"> <img src="./images/quantization.png"> </td>
  </tr>
  <tr>
      <td align = "center"> K-means Quantization for 2 bits </td>
  </tr>
</table>
