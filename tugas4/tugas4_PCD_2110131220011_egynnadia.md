# NIM   :2110131220011
# NAMA  :Egyn T. Nadia

## Tugas 4.1 
## MENENTUKAN POLA PADA PATTERNING DAN DITHERNING

<br>
<h2 align = "center">DITHERING</h2>
<p align = "justify"> Dengan menggunakan matriks 2x2 piksel, lima nilai intensitas "efektif" yang berbeda dapat terwakili. Demikian dengan matriks 4x4 piksel, sepuluh buah tingkat kabuan yang berbeda dapat terwakili. Metode ini disebut dengan <i>dithering</i>, dalam proses <i>dithering</i> blok asli pada citra kemudian akan diganti dengan jenis pola biner.</p>

![dithering]()

<p align = "justify"><i>Ordered dithering</i> dilakukan dengan membandingkan tiap blok dari citra asli dengan sebuah matriks pembatas yang disebut dengan matriks <i>dither</i>. Masing-masing elemen dari blok asli dikuantisasi sesuai dengan nilai batas pada <i>dither</i>. Nilai-nilai pada matriks <i>dither</i> adalah tetap, tetapi bisa bervariasi sesuai dengan jenis citra.<br>
Matriks <i>dither</i> pertama yang digunakan dalam metode ini adalah:

![rumus1]()

