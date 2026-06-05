# Klasifikasi Gabah sebagai Anomali Visual pada Tumpukan Beras Menggunakan Convolutional Neural Network Berbasis MobileNetV2
Dataset: Dataset terdiri dari 1.000 citra hasil akuisisi mandiri yang terbagi secara seimbang ke dalam dua kelas: 500 citra Beras Normal dan 500 citra Gabah Anomali.  Model: Menggunakan arsitektur MobileNetV2 dengan pendekatan transfer learning. Teknik praproses yang diterapkan meliputi background removal menggunakan pustaka rembg dan random background simulation dengan lima variasi warna latar belakang. Augmentasi data pada data latih meliputi horizontal flip, vertical flip, rotasi 90°, dan penyesuaian kecerahan.  Hasil: Model terbaik (Fase 1) berhasil mencapai akurasi sebesar 90,67% pada data uji. Model ini menunjukkan performa yang stabil dengan nilai false positive sebesar 0, yang berarti tidak ada beras normal yang salah dideteksi sebagai gabah. 

## Citation

If you find this dataset or code useful for your research, please cite our paper published in *Sinkron*:

**APA 7th Edition Format:**
> Saadah, B., & Saputri, T. A. (2026). Classification of Paddy as Visual Anomaly in Rice Piles Using MobileNetV2-Based Convolutional Neural Network. *Sinkron: Jurnal dan Penelitian Teknik Informatika*, xx(xx). https://doi.org/10.33395/sinkron.xxx.xxx

**BibTeX Format (For Zotero, Mendeley, or LaTeX):**
```bibtex
@article{saadah2026classification,
  author    = {Saadah, Barokah and Saputri, Tri Aristi},
  title     = {Classification of Paddy as Visual Anomaly in Rice Piles Using MobileNetV2-Based Convolutional Neural Network},
  journal   = {Sinkron: Jurnal dan Penelitian Teknik Informatika},
  volume    = {xx},
  number    = {xx},
  year      = {2026},
  doi       = {10.33395/sinkron.xxx.xxx},
  publisher = {Politeknik Ganesha Medan}
}
