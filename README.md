# Exploratory-Data-Analysis-pada-E-Commerce-Behavior-Data
Melakukan Exploratory Data Analysis dengan menggunakan R Programming





# Data Understanding

Sumber data : https://www.kaggle.com/mkechinov/ecommerce-behavior-data-from-multi-category-store

Data yang digunakan kali ini berisi data perilaku konsumen selama bulan Oktober 2019 dari toko online multi-kategori produk yang terdiri dari 42 juta baris dan 9 kolom

![image](https://user-images.githubusercontent.com/85357151/133062600-c3fcbb03-830f-422a-bd29-bad7e50b26fb.png)

![image](https://user-images.githubusercontent.com/85357151/133062612-32e5f8ac-f74d-4a9f-9814-3a01457080e4.png)


# Exploratory Data Analysis

**Perilaku Konsumen**



![image](https://user-images.githubusercontent.com/85357151/133063082-40355107-96bc-4075-bac6-b83304276cf5.png)
![image](https://user-images.githubusercontent.com/85357151/133063088-ed609722-2400-42cb-9bf3-fe8667297ac5.png)


- Dari seluruh pengunjung toko, yang memasukan ke keranjang sebanyak 3,27% dan yang melakukan pembelian sebanyak 3.03%. 

- **Jika dikonversikan dari keranjang ke pembelian maka akan menghasilkan 92,73% yang artinya sebagian besar produk yang dimasukan ke keranjang akan dibeli oleh konsumen**


![image](https://user-images.githubusercontent.com/85357151/133064833-b9473f2d-bfa4-459a-a7d2-cf125a4b2424.png)

![image](https://user-images.githubusercontent.com/85357151/133064923-fcd304fb-5fd2-4808-99f7-db091fdd70a6.png)

- Kategori electronics smartphone menghasilkan total view dan total purchase terbanyak dari semua kategori


![image](https://user-images.githubusercontent.com/85357151/133065424-b64abcfb-66b0-469c-9012-19f3f6f0b66f.png)


- Dari GMV, kategori electronics smartphone juga menghasilkan penjualan paling besar. 

Jadi kita fokus untuk melihat kategori electronics smartphone


![image](https://user-images.githubusercontent.com/85357151/133065990-162b755d-1ea7-4a3c-8cea-30bc7ca54b44.png)

- Dari kategori electric smartphone, brand Samsung memiliki jumlah order paling banyak sebesar 42,36% kemudian diikuti oleh apple sebesar 34.11%
- Tetapi dari sisi GMV dari produk yang terjual, brand apple jauh menghasilkan GMV sebesar 65.33%, sedangkan Samsung 23.88%

![image](https://user-images.githubusercontent.com/85357151/133066265-ca6648e4-0014-400f-8c66-0f26df90d86e.png)

- Apple memiliki rentang harga yang paling tinggi.
- Pada rentang harga 1000-2000 hanya ada produk Apple dan Samsung, walaupun produk apple jauh lebih laku dibanding Samsung. 
- Pada rentang harga 500-1000 ada produk dari Huawei dan oppo juga tetapi terlihat masih kalah di banding apple dan Samsung 
- Persaingan ketat ada pada rentang harga 100-500. Xiaomi hanya fokus pada produk dengan harga 100-500

# Perilaku Konsumen untuk Kategori Electronics Smartphone

![image](https://user-images.githubusercontent.com/85357151/133066869-e630d379-ce1a-4cd5-8003-2280388685e8.png)


- Apple mempunyai jumlah view tertinggi pada awal bulan
- Samsung mempunyai jumlah view tertinggi pada pertengahan bulan
- Huawei dan oppo jumlah view nya condong antara pertengahan dan akhir bulan
- Xiaomi jumlah view nya tetap tinggi dari pertengahan bulan hingga akhir bulan


![image](https://user-images.githubusercontent.com/85357151/133067033-92d79fd3-7577-4549-b08d-258de5b4484a.png)

- Hampir semua brand mempunyai pola yang sama yaitu melakukan penggunaan keranjang pada awal bulan dan pertengahan bulan


![image](https://user-images.githubusercontent.com/85357151/133067157-baffff46-02bf-4f72-8f70-94c87c291dea.png)
- Pada semua brand, pembelian mengalami puncaknya pada pertengahan bulan. Tetapi untuk brand Huawei dan oppo juga mempunyai puncak lain yaitu pada awal bulan


# Rekomendasi

- Membuat campaign "Keranjingan" dengan tujuan mengajak konsumen memasukan barang yang dia lihat atau inginkan ke keranjang. Hal ini didasari bahwa konversi dari fungsi keranjang ke pembelian sangat tinggi mencapai 92.73%
- Beri promo diawal bulan untuk meningkatkan puncak penjualan di awal dan di tengah bulan
- Memberikan promo pada pembeli smartphone dengan brand apple, Samsung, Huawei, oppo, dan xiaomi sesuai dengan kelasnya



























  


