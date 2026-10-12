# GSLC Deep Learning --- Oxford-IIIT Pet Classification

Eksperimen klasifikasi gambar untuk 10 kelas ras kucing dan anjing menggunakan PyTorch dan ResNet-18. 



Isi proyek

* `2802392816\_GSLC\_DeepLearning.ipynb`
* `requirements.txt`: dependensi Python.
* `Training History.json`: riwayat loss dan akurasi per epoch.
* `Results Summary.csv`: ringkasan metrik eksperimen.
* `C1\_loss\_curves.png`: grafik training loss dan validation loss.
* `C3\_failures.png`: contoh citra yang salah diklasifikasikan.
* `C5\_gradcam.png`: visualisasi Grad-CAM, jika dibuat/ditambahkan.

Berkas hasil selain notebook tidak harus tersedia sebelum menjalankan eksperimen;`Training History.json`, `Results Summary.csv`, serta grafik C1 dan C3.



## Instalasi

Disarankan membuat virtual environment terlebih dahulu.

### Windows

``` bash
py -m venv .venv
.venv\\\\Scripts\\\\activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### macOS / Linux

``` bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

