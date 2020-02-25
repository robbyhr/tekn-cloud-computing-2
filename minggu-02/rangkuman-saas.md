SaaS: Perangkat Lunak sebagai Layanan
	Merupakan layanan menjalankan aplikasi di cloud publik. Pengguna menggunakan aplikasi ini melalui Internet. Aplikasi ini dikelola oleh Penyedia Layanan. Seperti SalesForce, Microsoft (Office 365), Oracle, Google (Google Apps), dll.
		Salesforce adalah perusahaan pertama yang mengubah dunia Saas, dan sejak saat itu, perusahaan lain telah melihat potensi di pasar ini dan meluncurkan aplikasi mereka.

Iaas: Infrastruktur sebagai Layanan
	Layanan ini menyediakan lingkungan bagi pengembang untuk membangun aplikasi yang dapat digunakan pengguna. 
	IaaS meliputi:
		1. Pengguna membuat mesin virtual (VM) sesuai permintaan.
		2. Dari perpustakaan gambar VM.
	Amazon (AWS) adalah vendor terkemuka dalam menyediakan IaaS.

PaaS: Platform sebagai Layanan
	Ini agak mirip dengan IaaS tetapi perbedaannya adalah:
		1. Pengembang menyediakan aplikasi yang dijalankan platform.
		2. Mereka tidak secara langsung membuat VM.
	Paas terlihat sederhana dan itulah sebabnya banyak digunakan. Namun sebernarnya Iaas 10x lebih populer dari Paas. 


SAAS (Software as a Service) Platform Architecture
	SaaS adalah model lisensi dan pengiriman perangkat lunak di mana perangkat lunak dilisensikan berdasarkan berlangganan dan di-host secara terpusat. Pengguna dapat mengaksesnya dengan bantuan browser web. SaaS adalah model pengiriman umum untuk banyak aplikasi bisnis, termasuk perangkat lunak perkantoran dan pesan, perangkat lunak manajemen, virtualisasi dll. Ini adalah bagian dari nomenklatur komputasi awan, bersama dengan infrastruktur sebagai layanan (IaaS), platform sebagai layanan (PaaS) , desktop sebagai layanan (DaaS).

	Ada dua varietas utama SaaS:
		1. SaaS Vertikal
		2. Perangkat Lunak yang menjawab kebutuhan industri tertentu seperti Perangkat lunak untuk kesehatan, pertanian, real estat, industri keuangan)
		3. SaaS Horisontal
		4. Produk-produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik industri.

	Kesimpulan :
	Perusahaan sebaiknya mempertimbangkan fleksibilitas dan implikasi manajemen risiko dalam menambahkan SaaS ke portofolio layanan TI . Integrasi dan komposisi adalah komponen penting dalam strategi arsitektur Anda untuk menggabungkan SaaS dengan sukses sebagai anggota yang berpartisipasi penuh dari infrastruktur TI  yang berpusat pada layanan. 

SAAS (Software as a Service) Platform Architecture
	SaaS adalah cara untuk mengirimkan perangkat lunak, penyedia perangkat lunak ini secara sentral menampung satu atau lebih aplikasi dan membuatnya tersedia bagi pelanggan melalui internet.

	SaaS juga merupakan salah satu pilar utama komputasi awan. Sebuah ledakan dalam komputasi Cloud, didorong oleh penyedia cloud seperti Microsoft dengan Azure atau Amazon dengan AWS, telah melihat pertumbuhan produk dan layanan lain yang disampaikan melalui internet seperti:
		1. Infrastruktur sebagai Layanan
		2. Platform sebagai Layanan
		3. Pembelajaran Mesin sebagai Layanan

How to build a cloud-based SaaS application
	Saat membangun aplikasi SaaS (global), ada kemungkinan besar bahwa Anda membangunnya di cloud. Cloud memiliki banyak keunggulan - pikirkan skalabilitas - berbeda dengan lingkungan server lokal.

	Membangun a cloud-based Saas application
		1. Pilih bahasa pemrograman, dalam hal ini menggunakan bahasa pemrograman python
		2. Memilih database yang sempurna, dalam hal ini menggunakan MongoDB sebagai database untuk aplikasi web
		3. memilih Queuning system yang tepat, dalan hal ini queuing system yang gunakan yaitu RabbitMQ