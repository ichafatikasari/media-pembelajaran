# E-Learning HTML & CSS untuk SMP/MTs (CP: Berpikir Komputasional)

Aplikasi pembelajaran interaktif berbasis React untuk membantu siswa SMP memahami konsep dasar Web, HTML, dan CSS melalui materi, video, game, dan misi coding langsung.

## Fitur Utama
- **Halaman Login**: Menggunakan akun siswa yang terdaftar di `src/data/users.ts`.
- **Materi Interaktif**: Penjelasan dengan analogi sederhana yang mudah dipahami anak SMP.
- **Video Tutorial**: Integrasi video YouTube pembelajaran HTML & CSS.
- **Game Edukasi**:
  - `Tag Pop`: Tes kecepatan mengenal tag HTML valid.
  - `CSS Painter`: Belajar properti styling CSS secara visual.
  - `Tag Builder`: Menyusun struktur kode dengan blok interaktif.
- **Misi Coding**: Latihan ngoding langsung dengan Monaco Editor dan live preview.
- **Portofolio**: Menyimpan dan menampilkan hasil karya coding siswa.
- **Leaderboard**: Papan peringkat poin (tersimpan di `localStorage` masing-masing browser).

## Teknologi
- **Framework**: React 19 + Vite
- **Styling**: Tailwind CSS 4
- **State**: Zustand (Persistence via localStorage)
- **Icons**: Lucide React
- **Animations**: Framer Motion (Motion)
- **Editor**: Monaco Editor (@monaco-editor/react)

## Cara Jalankan Lokal
1. Install dependensi:
   ```bash
   npm install
   ```
2. Jalankan mode pengembangan:
   ```bash
   npm run dev
   ```
3. Build untuk produksi:
   ```bash
   npm run build
   ```

## Kustomisasi Akun Siswa
Untuk menambah atau mengubah daftar akun siswa, edit file:
`src/data/users.ts`

---
Dibuat untuk membantu literasi digital siswa Indonesia! 🚀
