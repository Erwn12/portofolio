# Panduan Penggunaan Portofolio

## Cara Menggunakan Portofolio

Berikut adalah panduan untuk menggunakan dan menyesuaikan portofolio profesional Anda:

### 1. Ekstrak File

- Ekstrak file `portfolio.zip` ke direktori di komputer Anda
- Struktur file akan terlihat seperti berikut:
  - `index.html` - Halaman utama portofolio
  - `/css` - Berisi file CSS untuk styling
  - `/js` - Berisi file JavaScript untuk interaktivitas
  - `/images` - Berisi screenshot dari proyek-proyek Anda

### 2. Menyesuaikan Konten

#### Informasi Pribadi
- Buka file `index.html` dengan editor teks (seperti Notepad++, Visual Studio Code, dll.)
- Perbarui informasi kontak Anda di bagian "Kontak"
- Sesuaikan biografi di bagian "Tentang Saya" jika diperlukan

#### Proyek
- Untuk menambah atau mengubah proyek, cari bagian "Projects Section" di file `index.html`
- Setiap proyek berada dalam elemen dengan class `project-card`
- Anda dapat menambah, menghapus, atau mengubah proyek sesuai kebutuhan

#### Keterampilan
- Untuk menyesuaikan keterampilan, cari bagian "Skills Section" di file `index.html`
- Setiap keterampilan berada dalam elemen dengan class `skill-item`
- Anda dapat mengubah persentase keahlian dengan mengubah nilai `width` pada class `skill-level`

### 3. Mengganti Gambar

- Untuk mengganti screenshot proyek, simpan gambar baru di folder `/images`
- Kemudian perbarui path gambar di file `index.html` pada bagian proyek yang sesuai

### 4. Melihat Portofolio

- Buka file `index.html` dengan browser web untuk melihat portofolio Anda
- Pastikan semua gambar dan tautan berfungsi dengan baik

### 5. Mengunggah ke Hosting

Untuk mengunggah portofolio ke internet:

1. Daftar di layanan hosting web (seperti Hostinger, Niagahoster, atau DomaiNesia)
2. Beli domain jika diperlukan (misalnya: erwannovrian.com)
3. Unggah semua file portofolio ke hosting menggunakan FTP atau panel kontrol hosting
4. Pastikan file `index.html` berada di direktori root

### 6. Pengoptimalan SEO (Opsional)

Untuk meningkatkan visibilitas portofolio Anda di mesin pencari:

1. Tambahkan meta tag yang relevan di bagian `<head>` file `index.html`:
   ```html
   <meta name="description" content="Portofolio Muhammad Erwan Novrian Putra - Web Developer & Freelancer">
   <meta name="keywords" content="web developer, freelancer, pengembang web, aplikasi web, PHP, JavaScript">
   ```

2. Pastikan judul halaman mencerminkan identitas profesional Anda:
   ```html
   <title>Muhammad Erwan Novrian Putra - Web Developer & Freelancer</title>
   ```

### 7. Pemeliharaan

- Perbarui portofolio secara berkala dengan proyek-proyek terbaru
- Pastikan informasi kontak selalu up-to-date
- Sesuaikan keterampilan seiring dengan perkembangan keahlian Anda

### Catatan Penting

- Semua tautan proyek saat ini mengarah ke website yang Anda berikan
- Pastikan website-website tersebut tetap aktif, atau perbarui tautan jika diperlukan
- Jika Anda ingin mengubah skema warna, edit variabel di bagian atas file `css/style.css`
