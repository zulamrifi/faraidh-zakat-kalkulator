### Panduan Deploy Kalkulator KUA (Metode Upload Browser)

**Persiapan Awal di Local Storage (HP/Tablet):**
1. Cari file `web waris.html` yang sudah final di penyimpanan internal Anda.
2. **Wajib:** Ubah nama (Rename) file tersebut menjadi `index.html`. *(Vercel membutuhkan nama ini agar otomatis mengenali file sebagai halaman utama).*

**Langkah 1: Upload ke GitHub dari Local Storage**
1. Buka browser dan login ke akun [GitHub](https://github.com/).
2. Buat repositori baru: Klik ikon **+** di pojok kanan atas, pilih **New repository**.
3. Beri nama repositori (misal: `kalkulator-kua`), biarkan pengaturan lainnya, lalu klik tombol hijau **Create repository**.
4. Di halaman berikutnya, perhatikan bagian tengah layar. Jangan gunakan kode. Cukup klik tulisan biru: **"uploading an existing file"**.
5. Klik **"choose your files"**. Manajer file (Local Storage) HP Anda akan terbuka. Pilih file `index.html` yang tadi sudah disiapkan.
6. Tunggu proses *upload* selesai (loading bar hijau).
7. Gulir ke bagian paling bawah, lalu klik tombol hijau **Commit changes**. Sekarang file Anda sudah aman di GitHub!

**Langkah 2: Sambungkan dan Deploy di Vercel**
1. Buka tab baru di browser, buka [Vercel](https://vercel.com/) dan login (pilih opsi *Continue with GitHub* agar otomatis terhubung).
2. Di halaman utama Vercel, klik tombol **Add New...** lalu pilih **Project**.
3. Di bagian *Import Git Repository*, Vercel akan otomatis menampilkan daftar proyek GitHub Anda. Cari repositori `kalkulator-kua` yang baru dibuat di Langkah 1, lalu klik **Import**.
4. Anda akan masuk ke halaman *Configure Project*. **Jangan ubah apa pun** (biarkan *Framework Preset* tetap "Other").
5. Langsung klik tombol biru **Deploy**.

**Langkah 3: Selesai!**
Tunggu sekitar 10 hingga 20 detik. Vercel akan memunculkan animasi kembang api tanda aplikasi Anda sudah tayang (Live). 

Klik tombol **Continue to Dashboard** atau klik pratinjau layarnya. Anda akan mendapatkan tautan (link) publik (misalnya: `https://kalkulator-kua.vercel.app`). Link inilah yang siap Anda bagikan ke grup WhatsApp warga atau jamaah KUA Kecamatan Sekongkang!
