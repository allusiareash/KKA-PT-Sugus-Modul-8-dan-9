# Audit Simulator PT SUGUS

## Struktur File
```
audit-sugus/
├── index.html          ← Buka file ini di browser (halaman portal utama)
└── modules/
    ├── modul8.html     ← Simulator Modul 8 (PPh 21 & Beban Operasional)
    └── modul9.html     ← Simulator Modul 9 (JKK, ARP, Representation Letter)
```

## Cara Menjalankan di VS Code (localhost)

### Metode 1 — Live Server Extension (Direkomendasikan)
1. Install ekstensi **"Live Server"** oleh Ritwick Dey di VS Code
2. Buka folder `audit-sugus` di VS Code (`File > Open Folder`)
3. Klik kanan pada `index.html` di Explorer
4. Pilih **"Open with Live Server"**
5. Browser akan terbuka di `http://127.0.0.1:5500`

### Metode 2 — Python (jika sudah terinstall)
Buka terminal di folder `audit-sugus`, lalu jalankan:
```bash
# Python 3
python -m http.server 8080

# Buka di browser: http://localhost:8080
```

### Metode 3 — Node.js
```bash
npx serve .
# Buka di browser: http://localhost:3000
```

## Fitur
- Portal landing page dengan navigasi ke kedua modul
- Tombol "Kembali ke Portal" di setiap modul
- Sistem penilaian otomatis (skor 0–100)
- Kunci jawaban tersembunyi, muncul setelah submit
- Ekspor ke PDF dari masing-masing modul
