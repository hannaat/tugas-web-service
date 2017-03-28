analisa
?xml version="1.0" encoding="UTF-8"? ini merupakan untuk memulai suatu xml jiga tidak ada ini akan error
!DOCTYPE logbarang SYSTEM "logbarang.dtd" merupakan bahwa dtd dengan logbarang sudah terhubung dengan xmlnya.
Pada elemen logbarang terdapat elemen barang dengan didalamnya terdapat element kode, satuan, harga, asal, dan tujuan.Dan pada elemen harga terdapat atribut 'cur = "nmtoken"'. Dalam elemen asal terdapat elemen pt dan kodewil dan dalam elemen tujuan terdapat elemen pt dan kodewil. Dan ditutup dengan elemen penutul barang. Pada elemen kode diberi '?',tujuannya adalah agar tidak terjadi error apabila kodenya dihapus. di dalam logbarang.dtd dielemen harga attlist nya di tambahkan cur CDATA "nmtoken", agar di xml tidak terjadi error.
