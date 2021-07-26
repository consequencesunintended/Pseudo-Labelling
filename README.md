# Pseudo-Labelling
<a href="https://www.buymeacoffee.com/banterless" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

Pseudo Labelling on MNIST dataset

They are three different jupyter notebook files, one seems to be failing to achieve any improvements (Pseudo-Labelling-MNIST-1st), the second one achieves a maximum 7 percent increase of accuracy (Pseudo-Labelling-MNIST-2nd) and the third model, which relies on augemntation, an increase of 14 percent (Pseudo-Labelling-MNIST-3rd)

<table style="width:100%">
   <tr>
    <th></th>
    <td>Pre-trained with labelled images</td>
    <td>Trained with Pseudo labelled images</td>
  </tr>
  <tr>
    <th>1st</th>
    <td>67.7 %</td>
    <td>67.85 % (+0.15)</td>
  </tr>
  <tr>
    <th>2nd</th>
    <td>73.95 %</td>
    <td>81.75 % (+7.8‬)</td>
  </tr>
    <tr>
    <th>3rd</th>
    <td>73.95 %</td>
    <td>88.65 % (14.61)‬</td>
  </tr>
</table>

References:

1 - Pseudo-Label : The Simple and Efficient Semi-Supervised Learning Method for Deep Neural Networks, Dong-Hyun Lee http://deeplearning.net/wp-content/uploads/2013/03/pseudo_label_final.pdf

2 - Naive semi-supervised deep learning using pseudo-label, Zhun Li, ByungSoo Ko & Ho-Jin Choi https://link.springer.com/article/10.1007/s12083-018-0702-9

3 - The Illustrated FixMatch for Semi-Supervised Learning 
https://amitness.com/2020/03/fixmatch-semi-supervised/
