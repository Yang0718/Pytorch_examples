# Simple deep learning practices with Pytorch.

## CNN
[Download Dataset](https://drive.google.com/drive/folders/1nUZ344CpivCFiOCs7l4RRGoBGi-2OddB?usp=sharing) <br>
Classify 10 kinds of animals. Training results and misclassified images are shown below.<br>
用CNN做10種動物照片的分類。<br>
![Result](https://github.com/Yang0718/Pytorch_examples/raw/master/CNN/result.PNG)

## RNN
[Download Dataset](https://drive.google.com/drive/folders/18I1WDmJpJJ52Wn4uBYogk5zCrOQ4KtHC?usp=sharing)<br>
Predict whether the submitted ICLR papers will be accepted.<br>
資料集是投稿到期刊的文章之標題，把文字輸入到RNN中預測該篇文章會被期刊接受還是拒絕。

## VAE
[Download Dataset](https://drive.google.com/drive/folders/1QfoNz5rnQQtXv5nH3mZ9YW1UeUrRN75q?usp=sharing)<br>
* Use VAE to create fake outputs of cartoon style pictures.<br>把卡通圖片輸入到VAE中訓練，產出假的新卡通圖片
![VAE structure](https://github.com/Yang0718/Pytorch_examples/raw/master/VAE/model.PNG "model structure of VAE")
* Reconstructed images<br>
On the left is the input, on the right is the output.<br>讓VAE學習重構(reconstruct)照片的能力。每個格子裡面的左邊是輸入，右邊是輸出。<br>
![reconstruct](https://github.com/Yang0718/Pytorch_examples/raw/master/VAE/reconstruct.PNG "reconstructed image")<br>
* Output fake images.<br>最終結果為輸出假的圖片<br>
![fake](https://github.com/Yang0718/Pytorch_examples/raw/master/VAE/fake.PNG "fake image")
