# CARA INSTALL TransFlow Python3 
## 1. Install Python 3 dan venv
#### Cek Versi Python
```python
# python --version
output : Python 3.7.6
# sudo apt install python3-venv
```
## 2. Menciptakan Lingkungan Virtual
```py
# mkdir coba_tensorflow && cd coba_tensorflow 
```
#### Setelah di dalam direktori, jalankan perintah berikut untuk membuat virtual environment:
```py
# python3 -m venv venv
```
#### Untuk mulai menggunakan virtual environment, Anda harus mengaktifkannya dengan menjalankan skrip activate dengan perintah source:
```py
# source venv/bin/activate
Output : (venv) (base) home@namauser-pc:~/my_tensorflow/
```
Setelah itu Tingkatkan pip ke versi terbaru untuk menghindari masalah saat instalasi paket:
```py
# pip install --upgrade pip
```
## 3. Instal TensorFlow
Sekarang setelah lvirtual environment diaktifkan, saatnya untuk menginstal paket TensorFlow.
```py
# pip3 instal --upgrade tensorflow
```
Untuk melihat versi TensorFlow:
```py
# python -c 'import tensorflow as tf; print(tf.__version__)'
```
Jika sudah tidak digunakan, untuk menon aktifkan ketikan perintah :
```py
# deactivate
```
