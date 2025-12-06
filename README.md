Diagram Class

classDiagram
    class DaftarNilai {
        +data_nilai : Dictionary
        +__init__()
        -_hitung_nilai_akhir(tugas, uts, uas)
        +tambah(nama, nim, tugas, uts, uas)
        +tampilkan()
        +hapus(nama)
        +ubah(nama, nim, tugas, uts, uas)
    }
