# Tugas Kelas Pembelajaran Mesin - _Multi Layer Perceptron Flower Classifier_
## Apa ini?
Sebuah model kecerdasan artifisial jaringan saraf untuk mengelompokkan citra digital yang mengandung citra bunga mawar, bunga matahari, dan bunga _dandelion_ dengan arsitektur _multi layer perceptron_.
## _Dataset_ yang digunakan
[Kaggle](https://www.kaggle.com/alxmamaev/flowers-recognition)
## Bagaimana cara menggunakannya?
1. _Clone_ repositori ini
2. Pastikan _dataset_ sudah dimasukkan ke Google Drive anda
3. Buka berkas berekstensi *.ipynb* dengan Google Colaboratory anda
4. Jalankan seluruh _cell_
## Bagaimana cara kerjanya?
1. Citra digital dari _dataset_ dikelompokkan menurut kategori (mawar, matahari, _dandelion_)
2. Citra digital diolah menjadi ukuran 320x240 pixel
3. Citra digital dikonversi menjadi _grayscale_
4. Citra digital dibagi menjadi data pembelajaran dan tes dengan rasio 80:20
5. Citra digital dimasukkan ke dalam struktur data Numpy Array
6. Model dilatih dengan data pembelajaran selama 50 repetisi
7. Model melakukan prediksi pada data tes
8. Visualisasi akurasi dan _error_ dari prediksi model
## Pembuat
* [Alexius Adhitya K](https://github.com/debugvelop)
* [Daniel Suranta Sitepu](https://github.com/danielsitepu36)
* [Fransiskus Rian Wardana Putra](https://github.com/RianWardanaPutra)
## Referensi
* [How to Code a Neural Network with Backpropagation In Python (from scratch)](https://machinelearningmastery.com/implement-backpropagation-algorithm-scratch-python)
* [3 Beginner-Friendly Techniques to Extract Features from Image Data using Python](https://www.analyticsvidhya.com/blog/2019/08/3-techniques-extract-features-from-image-data-machine-learning-python)
* [How to Build a Deep Neural Network without a Framework](https://towardsdatascience.com/how-to-build-a-deep-neural-network-without-a-framework-5d46067754d5)
* [Deep Learning AI Repository by marcopeix](https://github.com/marcopeix/Deep_Learning_AI/tree/master/1.Neural%20Networks%20and%20Deep%20Learning/4.Deep%20Neural%20Networks)
* [Building a Neural Network with a Single Hidden Layer using Numpy](https://towardsdatascience.com/building-a-neural-network-with-a-single-hidden-layer-using-numpy-923be1180dbf)
* [A Gentle Introduction to Cross-Entropy for Machine Learning](machinelearningmastery.com)
