# Situs hukum Catch Cast (GitHub Pages)

Folder ini berisi halaman publik yang dibutuhkan Google Play dan Facebook:

| Halaman | Alamat setelah dipublikasikan |
| --- | --- |
| Beranda | https://codinganpromt-creator.github.io/catch-cast/ |
| Kebijakan Privasi | https://codinganpromt-creator.github.io/catch-cast/privacy/ |
| Ketentuan Layanan | https://codinganpromt-creator.github.io/catch-cast/terms/ |
| Hapus Akun | https://codinganpromt-creator.github.io/catch-cast/delete-account/ |

## Cara publikasi

1. Masuk ke GitHub sebagai **codinganpromt-creator**, buat repository **publik** bernama **`catch-cast`**.
   Repository ini cukup berisi isi folder `site/` saja, bukan seluruh kode aplikasi.
2. Unggah semua isi folder `site/` ke akar (root) repository: `index.html`, `style.css`, `icon.png`, dan folder `privacy/`, `terms/`, `delete-account/`.
   Lewat web: **Add file → Upload files**, seret semua isinya, lalu **Commit changes**.
3. Buka **Settings → Pages**. Pada *Build and deployment*, pilih **Deploy from a branch**, branch **main**, folder **/ (root)**, lalu **Save**.
4. Tunggu 1–2 menit, lalu buka alamat di atas untuk memastikan halaman tampil.

Alamat ini sudah dipasang di aplikasi (`lib/core/config.dart` → `legalBaseUrl`). Jika nama akun atau repository berbeda, ubah nilai itu lalu build ulang aplikasi.
