# IDENTIFIKASI PLAT NOMOR KENDARAAN BERBASIS CNN

Pada November 2018 lalu program E-tilang mulai diperkenalkan kepada masyarkat Indonesia oleh Ditlantas Polda Metro Jaya, diberlakukannya E-tilang di Indonesia bertujuan agar pendataan atas penilangan kendaraan bermotor di Indonesia semakin baik kedepannya. Selain itu efisiensi juga didapatkan dari pemberlakuan E-tilang karena petugas tidak perlu lagi turun ke lapangan untuk melakukan pemberhentian yang mengakibatkan penumpukan kendaraan pada lalu lintas serta menambah kesadaran masyarakat untuk selalu menaati aturan lalu lintas yang berlaku karena merasa selalu diawasi.

Kamera statis digunakan untuk merekam kejadian pelanggaran dan disimpan, kamera statis tersebut dipasang pada tiang-tiang lampu penerangan maupun lampu pengatur lalu lintas pada tempat-tempat yang strategis. Kamera statis/perangkat E-tilang tersebut akan merekam/menangkap gambar pelanggar lalu lintas kemudian dikirim ke kantor tilang elektronik di Regional Traffic Management Centre (RTMC) Polda setempat baru setelah itu petugas akan mengidentifikasi data dari kendaraan pelanggar lalu lintas.

Dari cara kerja E-tilang tersebut, peneliti menemukan inefisiensi yang terdapat pada sistem E-tilang di Indonesia yaitu identifikasi data kendaraan secara manual oleh petugas kepolisian. Identifikasi data kendaraan pelanggar lalu lintas seharusnya dapat dilakukan oleh sistem cerdas sehingga efisiensi dapat dimaksimalkan serta tingkat akurasi dan presisi dapat terjaga karena tidak terpengaruh oleh faktor manusia dengan digantikan oleh artificial intelligence (kecerdasan buatan) agar pemrosesan data dapat dilakukan lebih cepat.

Artificial Intelligence atau kecerdasan buatan merupakan sistem-sistem yang memperlihatkan perilaku kecerdasan berdasarkan kemampuannya menganalisa lingkungan dan mengambil tindakan-tindakan dengan beberapa tingkatan untuk mencapai tujuan tertentu. Untuk dapat membantu efisiensi dalam identifikasi plat nomor kendaraan pelanggar lalu lintas melalui citra atau gambar, diperlukan subset dari AI itu sendiri yaitu deep learning. Deep learning merupakan bagian dari machine learning yang berbasis jaringan saraf tiruan dengan tiga layer atau lebih untuk mensimulasikan kebiasaan atau kemampuan otak manusia untuk belajar dari banyaknya data yang diberikan.

Dari pemaparan latar belakang di atas peneliti tertarik untuk menciptakan suatu sistem cerdas yang mampu mendeteksi dan mengenali plat nomor kendaraan bermotor menggunakan Convolution Neural Network. Penelitian tersebut dipaparkan ke dalam suatu karya tulis ilmiah dengan judul SISTEM IDENTIFIKASI PLAT NOMOR KENDARAAN BERBASIS CONVOLUTION NEURAL NETWORK.

Pengenalan plat nomor kendaraan memerlukan tahap awal yang disebut pengolahan citra. Teknik-teknik seperti segmentasi, normalisasi warna, dan deteksi tepi digunakan untuk mempersiapkan gambar plat nomor sebelum dianalisis lebih lanjut oleh CNN. Segmentasi membantu dalam pemisahan plat nomor dari latar belakang, sedangkan normalisasi warna memastikan konsistensi dalam representasi warna karakter. Deteksi tepi membantu mengidentifikasi tepi-tepi karakter, yang akan membantu dalam proses pengenalan karakter berikutnya. Dengan memahami dan menerapkan teknik-teknik ini, sistem dapat meningkatkan akurasi dalam pengenalan plat nomor.

Pengenalan karakter pada plat nomor adalah tahap kunci dalam identifikasi plat nomor kendaraan. Ini melibatkan pengolahan teks, yang mencakup segmentasi karakter dan pengenalan pola karakter. Segmentasi karakter merupakan proses pemisahan karakter-karakter pada plat nomor, yang sering kali memiliki tingkat variasi dalam bentuk, ukuran, dan orientasi karakter. Pengenalan pola karakter melibatkan pemahaman dan klasifikasi karakter-karakter tersebut menjadi karakter yang dapat diinterpretasikan. Pengolahan citra dan pengolahan teks saling melengkapi untuk menghasilkan hasil yang akurat dalam pengenalan plat nomor.