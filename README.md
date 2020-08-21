# CNN for Malaria Detection

In this project, a simple CNN will be built using Tensorflow to detect Malaria from thin blood slide images. The Dataset is taken from the official [NIH Website](https://ceb.nlm.nih.gov/repositories/malaria-datasets/).

## Dataset Preview

<table>
  <tr>
    <td style="text-align:center; font-weight: bold; font-size: 17px;" >Parasitized Cell</td>
     <td style="text-align:center; font-weight: bold; font-size: 17px;" >Uninfected Cell</td>
  </tr>
  <tr>
    <td style="text-align:center" ><img width=330 height=330 src="./res/parasitized.png"  alt="Parasitized" title="Parasitized Cell"/> </td>
    <td style="text-align:center" ><img width=330 height=330 src="./res/uninfected.png"  alt="Uninfected" title="Uninfected Cell"/></td>
  </tr>
 </table>



## Evalutation

<table>
  <tr>
    <td style="text-align:center; font-weight: bold; font-size: 17px;" >Classes</td>
    <td style="text-align:center; font-weight: bold; font-size: 17px;" >Precision</td>
     <td style="text-align:center; font-weight: bold; font-size: 17px;" >Recall</td>
    <td style="text-align:center; font-weight: bold; font-size: 17px;" >F1 score </td>
  </tr>
  <tr>
    <td style="text-align:center" >Parasitized (0)</td>
    <td style="text-align:center" >0.96</td>
    <td style="text-align:center" >0.93</td>
    <td style="text-align:center" >0.95</td>
  </tr>
  <tr>
    <td style="text-align:center" >Uninfected (1)</td>
    <td style="text-align:center" >0.93</td>
    <td style="text-align:center" >0.97</td>
    <td style="text-align:center" >0.95</td>
  </tr>
 </table>

