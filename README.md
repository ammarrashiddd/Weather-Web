# Weather Web

Aplikasi web untuk membantu pengguna mendapatkan informasi cuaca secara cepat dan mudah dipahami.

## Manfaat Utama

### 1. Mengurangi waktu pencarian informasi cuaca

Sebelum menggunakan aplikasi, pengguna perlu membuka beberapa halaman atau aplikasi untuk menemukan informasi cuaca. Weather Web menampilkan informasi cuaca dalam satu tampilan.

| Kondisi                           |        Sebelum |                      Sesudah |
| --------------------------------- | -------------: | ---------------------------: |
| Waktu mendapatkan informasi cuaca |       ±3 menit |                    ±30 detik |
| Jumlah halaman yang perlu dibuka  |    3–5 halaman |                    1 halaman |
| Informasi cuaca yang tersedia     | Tidak terpusat | Terpusat dalam satu tampilan |

### 2. Membantu pengguna mengambil keputusan harian

Informasi suhu, kondisi cuaca, dan prakiraan membantu pengguna menentukan aktivitas seperti bepergian, bekerja, atau membawa perlengkapan tertentu.

| Indikator                                |  Sebelum |      Sesudah |
| ---------------------------------------- | -------: | -----------: |
| Waktu memahami kondisi cuaca             | ±2 menit |     <1 menit |
| Informasi yang harus dibandingkan manual | 3 sumber |     1 sumber |
| Risiko lupa memeriksa cuaca              |   Tinggi | Lebih rendah |

### 3. Menyediakan pengalaman yang responsif

Aplikasi dirancang agar dapat digunakan melalui desktop maupun perangkat mobile. Tampilan yang responsif mengurangi kebutuhan memperbesar atau menggulir halaman secara berlebihan.

| Indikator                |       Sebelum |            Sesudah |
| ------------------------ | ------------: | -----------------: |
| Perangkat yang didukung  |  Desktop saja | Desktop dan mobile |
| Waktu memuat halaman     |      ±5 detik |    Target <2 detik |
| Layout pada layar mobile | Tidak optimal |          Responsif |

> Catatan: angka pada tabel di atas adalah baseline dan target dokumentasi. Ganti dengan hasil pengujian sebenarnya sebelum digunakan sebagai klaim produksi.

## Teknologi

- [Next.js](https://nextjs.org/)
- React
- TypeScript
- CSS
- Weather API

## Menjalankan Project

Instal dependensi:

```bash
npm install
```

Jalankan development server:

```bash
npm run dev
```

Buka [http://localhost:3000](http://localhost:3000).

## Pengukuran Performa

Untuk memvalidasi manfaat aplikasi, ukur:

- Waktu hingga halaman dapat digunakan.
- Waktu pencarian informasi cuaca.
- Jumlah halaman atau langkah yang diperlukan pengguna.
- Performa pada perangkat desktop dan mobile.
- Tingkat keberhasilan pengguna menemukan informasi cuaca.

## Pengembangan

Edit halaman utama pada:

```text
app/page.tsx
```

Perubahan akan ditampilkan otomatis selama development server berjalan.

## Referensi

- [Dokumentasi Next.js](https://nextjs.org/docs)
- [Learn Next.js](https://nextjs.org/learn)
