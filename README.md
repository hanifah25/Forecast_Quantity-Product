## Problem Statement 

* Salah satu tantangan yang dihadapi oleh bisnis adalah ketidakpastian dalam forecast quantity permintaan dan persediaan product. Jika bisnis tidak dapat memperkirakan permintaan dan persediaan dengan tepat, ini dapat menyebabkan overstocking atau understocking. Dengan mengembangkan model yang dapat memprediksi Quantity dengan akurasi yang baik dapat membantu bisnis untuk mengoptimalkan persediaan dan mengurangi biaya yang terkait dengan overstocking dan understocking.


## Objective

* Mampu forecast Quanity pada periode berikutnya dari dataset ParagonCorp.
* Model kerja dapat mencapai Tingkat Akurasi yang baik.
* Mampu menjelaskan metodologi yang digunakan untuk setiap langkah, algoritma, manipulasi data, pembersihan data, dll.
* Mampu memberikan bagan atau metode terukur lainnya untuk membuktikan kesimpulan Anda.


## Kesimpulan

1. Pada forecast dataset ini melakukan uji 3 model dengan tingkatan mape yaitu :
    * Model Arima MAPE yang di hasilkan 10 % yang sama dengan 90% accuracy model 
    * Model Holt Winter MAPE yang di hasilkan 15 % yang sama dengan 85% accuracy model
    * Model Sarimax MAPE yang di hasilkan 27 % yang sama dengan 73% accuracy model 

Dengan demikian dapat disimpulkan bahwa model terbaik untuk forecast adalah Arima dengan accuracy 90%

2. Dengan hasil forecast tersebut, yaitu bahwa jumlah quantity diprediksi akan menurun pada minggu ke-2 dan ke-4, namun akan meningkat pada minggu ke-3 dengan nilai yang cukup tinggi. Selanjutnya, pada minggu ke-5, nilai quantity diprediksi akan kembali ke nilai rata-rata yang ada. Namun, dengan akurasi model 90%, kita dapat lebih yakin bahwa prediksi tersebut lebih akurat dan dapat diandalkan untuk membuat keputusan bisnis dan perencanaan produksi di masa depan.

3. Tujuan bisnis dari forecast quantity adalah untuk membantu perusahaan dalam merencanakan strategi bisnis dan mengambil keputusan yang tepat terkait dengan produksi, persediaan, pemasaran, dan penjualan. Dengan memprediksi jumlah quantity yang akan terjual di masa depan, perusahaan dapat mengetahui permintaan pasar dan mempersiapkan persediaan produk yang cukup, sehingga dapat meningkatkan efisiensi produksi dan meminimalkan risiko kerugian akibat kekurangan atau kelebihan stok. Selain itu, perusahaan juga dapat menyesuaikan strategi pemasaran dan penjualan untuk meningkatkan pangsa pasar dan keuntungan.


## Data Fields

sample_dataset_timeseries_noarea.csv

* week_number: contained information about week of specific product sold, (2021-52 to 2023-14).
* week_start_date: contained information about week start date of specific product sold.
* week_end_date: contained information about week end date of specific product sold.
* product_item: contained information about product item/product code (Variabel Bebas).
* quantity: contained information about quantity of product in respective week.
