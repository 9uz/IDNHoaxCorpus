# IDNHoaxCorpus
Dataset Berita Palsu bahasa Indonesia (Hoax), Dataset Berita Palsu untuk Klasifikasi Teks dalam Bahasa Indonesia pada platform X

# Bagaimana korpus ini dibuat??
Data ini dikumpulkan team Universitas Muhammadiya Ponorogo pada tahun 2020.
Korpus dibuat dengan mengguanaka data yang ada pada platform  https://x.com/. Kemudian semua konten HTML murni diproses untuk mengekstrak teks artikel dengan beberapa kolom tambahan (tercantum di bawah). Setiap komentar/tweet telah diberi label yang sama dengan label yang terkait dengan domainnya. Data berisi 4617 baris × 6 kolom dengan 3 label hoax,?,dan valid

# Formatiing ??
Korpus disimpan dalam format CSV dan berisi kolom berikut:
<ul>
  <li>id</li>
  <li>topik</li>
  <li>keyword</li>
  <li>tweet</li>
  <li>gambar</li>
  <li>url</li>
  <li>label</li>
</ul>

Informasi lebih lanjut :
<table>
  <tr> 
    <th>Label</th>
    <th>Jumlah</th>
  </tr>
  <tr> 
    <td>Valid</td>
    <td>730</td>
  </tr>
  <tr> 
    <td>Hoax</td>
    <td>3042</td>
  </tr>
  <tr> 
    <td>?</td>
    <td>845</td>
  </tr>
</table>

# Citation
Please include the following citation when using this dataset for a paper, in addition to any citation specific to the used datasets.
```
@article{
author = { andRizal Arifinand and and and and },
title = {Hoax Identification of Indonesian Tweeters using Ensemble Classifier},
journal = {Journal of Information Systems and Telecommunication (JIST) },
volume = {11},
number = {2},
page = {94-101},
year = {2023},
publisher = {Iranian Academic Center for Education,Culture and Research },
issn = {2322-1437},
eissn = {2345-2773},
doi = {10.52547/jist.33532.11.42.94},
URL = {rimag.ir/fa/Article/33532},
eprint = {rimag.ir/fa/Article/Download/33532},
```
```
@article{arifin2023highly,
  title={A Highly Accurate Internet-Based Fake Information Detection Tool for Indonesian Twitter},
  author={Arifin, Rizal and Syaifuddiin, Gus Nanang and Desriyanti, Desriyanti and Rosyidin, Zulkham Umar and Buntoro, Ghulam Asrofi},
  journal={Informatica},
  volume={46},
  number={9},
  year={2023}
}
```
