# Georeferencing ArcMap (Image to Image and Image to Map)
Georeferencing digunakan untuk data peta yang belum memiliki koordinat menjadi memiliki koordinat,
Georeferencing bisa dilakukan dengan 2 cara yaitu Image to Map dan Image to Image


## Langkah-langkah
1.Masukkan data peta ke arcmap ![image](https://user-images.githubusercontent.com/87703066/154121937-765268f2-c2d2-447b-a7c2-a25df3192b5a.png)

2.Cari Tools Project Raster 

![image](https://user-images.githubusercontent.com/87703066/154122072-09e6777c-9a0f-4246-99e8-de4b80fb16f9.png)

3. Masukkan input peta RBI dan pilih koordinat sistem sesuai lokasi masing-masing

![image](https://user-images.githubusercontent.com/87703066/154122883-ab8b95c4-eacd-4dee-a8fe-3991c527208f.png)

4. Kalau sudah akan muncul gambar seperti ini dan kita akan fokus ke hasil data raster. remove data awal yang sudah tidak terpakai agar lebih ringan
 
![image](https://user-images.githubusercontent.com/87703066/154123246-6732ba10-fdb3-45f7-8263-17f8225a117c.png)
 
5. Tools ini membantu kita untuk memperbesar lokasi yang kita inginkan, untuk menggeser gunakan tools bergambar tangan
 
 ![image](https://user-images.githubusercontent.com/87703066/154123456-99dfa70a-d3e9-4167-8922-0fc94f62ae00.png)
 
6. Munculkan menu Georeferencing dengan cara klik kanan dan centang bagian georeferencing

![image](https://user-images.githubusercontent.com/87703066/154123606-6417714b-bf10-485f-bed3-42c28ee80c74.png)

7. Pakai Tools add control point lalu arahkan ke sudut yang ada DMSnya(Degree Minutes Secondnya) atau kita sering sebut koordinat

![image](https://user-images.githubusercontent.com/87703066/154128160-81c6af92-87d0-4148-a514-9765e25a42b5.png)

8. Masukkan DMS

![image](https://user-images.githubusercontent.com/87703066/154128219-ca9082b5-3b91-4db5-be40-c097a651163f.png)

9. cek link table untuk melihat residual dari titik yang kita buat

![image](https://user-images.githubusercontent.com/87703066/154129125-cb034b13-ec27-4453-8438-59f5bbd06f7f.png)

10. Kalau sudah klik georeferencing lalu Rectify

![image](https://user-images.githubusercontent.com/87703066/154129247-63647b7a-5cb7-4f55-a173-f32484d6d24d.png)

11. Sesuaikan file dan save

![image](https://user-images.githubusercontent.com/87703066/154129451-6e1c954c-ff38-4fc7-9976-af4b26ff3805.png)


## Image To Map
1. Masukan Peta RBI dan Peta Citra
 
![image](https://user-images.githubusercontent.com/87703066/154129769-665b2650-ac96-49ec-9cda-39f46503af77.png)

2. Masukkan Titik pada lokasi yang strategis seperti sungai dll agar mudah diingat dan mudah disambungkan dengan peta Map. Perlu diingat bahwa jika target kita ada peta NonGeo maka pada tools menu georeference kita pilih Peta Non GEO, (JANGAN SAMPAI TERBALIK) Lanjut hingga 10-30 titik (Titik ambil dibagian strategis saja sepergi sungai dll. Usahakan Menyebar

![image](https://user-images.githubusercontent.com/87703066/154130479-902fcfbe-fa03-41ca-9d90-c579de9783c3.png)


## Image to Image

1. Masukkan data Citra yang sudah digeorefencing dan belum ke dalam Arcmap

![image](https://user-images.githubusercontent.com/87703066/154131049-53747584-3165-4837-957c-a69cdf248e53.png)

2. Tools ini arahkan ke citra NonGeo, atau citra target yang ingin di georeferencing

![image](https://user-images.githubusercontent.com/87703066/154131157-7eda90cb-3331-41e2-bc81-c9fd0c789a62.png)

3. Titik Pertama pada non Geo

![image](https://user-images.githubusercontent.com/87703066/154131263-a9e33f48-a8b4-4a32-b9e2-708539b0760d.png)

4. Titik Sambungan pada citraGeo (Ingat Bahwa Lokasinya sama,yaitu di pinggir muara sungai)

![image](https://user-images.githubusercontent.com/87703066/154131536-a7bf1db3-09bd-48af-a61c-86708c813e56.png)

5. Usahakan Mendapatkan Residual sedikit-dikitnya dan seakurat akuratnya

![image](https://user-images.githubusercontent.com/87703066/154132452-3482812a-3a1e-4f94-9f42-355227774942.png)



