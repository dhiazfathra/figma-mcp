# Dermaesthetic Super App - Figma Features Inventory

**Date:** 2026-06-17
**Source:** [Figma Design](https://www.figma.com/design/qyBbEWy7V8v62219jwrRDT/Dermaesthetics-Super-App?node-id=386-4162)
**Page:** 1. User Onboarding Module 2 - Final Design
**Node:** `386:4162`

---

## Section 1: Start Journey (Before Login)

**Node:** `386:4163`

### Screens

| # | Screen | Node ID | Description |
|---|--------|---------|-------------|
| 1 | Homepage | `386:4164` | Main homepage before login — promo slides, brand carousel, voucher selection, quick-action buttons |
| 2 | Profil Belum Login | `386:4275` | Profile screen when NOT logged in — login prompt, promo slides, bottom nav |
| 3 | Aktivitas | `386:4385` | Activity/History screen before login — empty notifications state |
| 4 | Notification - Empty State | `386:4431` | Notifications empty state — "Tidak ada notifikasi tersedia" |

### Features

- **Promo Banner Carousel** — Promo Slide 2, 3, 4, 5 (auto-rotating)
- **Exclusive Voucher Selection** — "Pilihan Voucher Eksklusif" section with voucher cards
  - Voucher cards: "Free Pico Derma Treatment", "Voucher Rp12.000.000 fractional rf laser treatment"
  - Each card shows: image, title, validity date, "See Detail" CTA
- **Brand Carousel** — Horizontal scrollable brand cards:
  - Dermaster, Derma Express, Dermalicious, Dexskin, Dermaklin, Dexbeauty, Filterbaby, Lainnya (Others)
  - Sub-brands: Dermaster Plastic Surgery, Dermaster Hair Surgery
- **Quick Action Buttons** — "Booking Treatment" and "Produk Kecantikan" navigation cards
- **Membership Card** — "Green Member" badge with tier indicator
- **Search Bar** — "Cari Kebutuhan mu..." (Find your needs...)
- **Header** — Greeting "Hi, John Doe" + cart icon + notification bell
- **Bottom Navigation Bar** — 4 tabs: Home, Aktivitas, Bantuan (icon only), Profil

---

## Section 2: Login, Register, Forgot Password

**Node:** `386:4488`

### Screens

| # | Screen | Node ID | Description |
|---|--------|---------|-------------|
| 1 | Daftar (Register) | `386:4489` | Registration form — "Informasi Pribadi" fields |
| 2 | Informasi Tidak Valid (x2) | `386:4614`, `386:4675` | Registration with validation errors |
| 3 | Registrasi Berhasil | `386:4746` | Registration success screen |
| 4 | Alur Registrasi Akun | `386:4766` | Registration flow diagram |
| 5 | Alur Login | `386:4768` | Login flow diagram |
| 6 | Alur Forgot Password | `386:4770` | Forgot password flow diagram |
| 7 | Masuk (Login) | `386:5009` | Login form — phone/email + password |
| 8 | Forgot Password-1 (x2) | `386:5210`, `386:5211` | "Masukan Informasi Akun" — enter email/phone |
| 9 | Forgot Password-2 | `386:5212` | "Lupa Password" — enter reset info, WhatsApp option |
| 10 | Forgot Password-3 | `386:5213` | OTP verification via WhatsApp |
| 11 | Forgot Password-4 | `386:5214` | OTP verification via SMS |
| 12 | Forgot Password-5 | `386:5263` | Reset password form |
| 13 | Forgot Password-6 | — | OTP verification via SMS |
| 14 | Forgot Password-7 | — | OTP verification |
| 15 | Forgot Password-email (x2) | `386:5352`, `386:5381` | OTP verification via email |
| 16 | Forgot Password-8 | `386:5483` | OTP verification |
| 17 | Forgot Password-9 | `386:5485` | OTP verification |
| 18 | Forgot Password-10 | — | Login flow with password reset |
| 19 | Forgot Password-11 | — | Email OTP for password reset |
| 20 | Login Berhasil | — | Login success screen |

### Features

- **Registration Form Fields:**
  - Full Name* (John Doe)
  - Phone Number* (08212323264656)
  - Gender* (Male dropdown)
  - Tanggal Lahir* (Date of Birth: 01/01/1990)
  - Password* (eye toggle for visibility)
  - "Lanjutkan" (Continue) button

- **Login Flow States:**
  - Mengecek Informasi → Informasi Valid / Informasi Tidak Valid
  - Mengecek OTP → OTP Sesuai / OTP Tidak Sesuai
  - Data Sesuai / Data Tidak Sesuai

- **OTP Delivery Channels:**
  - WhatsApp (to 082123****898)
  - SMS (to 082123****898)
  - Email (to john***@mail.com)

- **Forgot Password Features:**
  - Multiple OTP delivery options (WhatsApp, SMS, Email)
  - Countdown timer "01:00"
  - "Belum dapat kode?" (Haven't received code?) link
  - "ganti nomor" (change number) option
  - Password validation: must contain special characters (!@$%)

---

## Section 3: Homepage Condition After Login

**Node:** `386:5494`

### Screens

| # | Screen | Node ID | Description |
|---|--------|---------|-------------|
| 1 | Notification - isi | `386:5495` | Homepage with notifications populated |
| 2 | Profil | `386:5570` | Profile page after login — user info, menu items |
| 3 | Aktivitas | `386:5681` | Activity page with transaction history |
| 4 | Frame 3390 | `386:5929` | Summary/overview of homepage conditions after login |

### Features

- **Profile Screen (after login):**
  - "Ubah Profil" (Edit Profile) button
  - "Voucher & Reward" menu item
  - "Aktivitas" (Activity) menu with dropdown
  - "Daftar Alamat" (Address List) menu with dropdown
  - "Bahasa" (Language) — ID / EN toggle
  - "Bantuan" (Help) with dropdown
  - "Kebijakan & Privasi" (Privacy Policy)
  - "Tentang Dermaesthetics" (About Dermaesthetics)
  - "Pengaturan Akun" (Account Settings) with dropdown
  - Membership tier: "Gold" — "30 Points"

- **Activity Screen States:**
  - "Menunggu Pembayaran" (Awaiting Payment) — "Nikmati diskon spesial bulan maret"
  - "Transaksi dalam proses" (Transaction in progress)
  - "Sedang dalam pengiriman" (Being shipped)
  - "Pembelian Selesai" (Purchase Complete)
  - Tab filters: Order, Appointment

- **Notification Pop-up Features:**
  - "Promo 3.3" promotional banners
  - "Notifikasi" (Notification) badge
  - Chat icon, shopping-cart icon, bell icon

---

## Section 4: Profile Menu and Authentication

**Node:** `386:5931`

### Screens

| # | Screen | Node ID | Description |
|---|--------|---------|-------------|
| 1 | Profil (edit success) | `386:5932` | Profile with edit success toast |
| 2 | Profile Before (Edit form) | `386:6053` | "Ubah Profil" (Edit Profile) form |
| 3 | Profile Before (Change Password) | `386:6353` | "Ubah Password" form |
| 4 | Profile Before (Edit + Save) | `386:6501` | Edit profile with "Simpan Data" button |
| 5 | Update Profile modal | `386:6507` | "Update Profile" modal/dialog |
| 6 | Sign Out Confirmation | `386:6509` | "Sign Out Confirmation" dialog |
| 7 | Help Center | `386:6511` | "Help Center" screen |
| 8 | Delete Account Confirmation | `386:6513` | "Delete Account Confirmation" dialog |
| 9 | Ubah Password | `386:6515` | "Ubah Password" (Change Password) form |
| 10 | Ubah Nomor Telepon | `386:6517` | "Ubah Nomor Telepon" (Change Phone Number) |
| 11 | Profile variants | `386:6550`–`386:7318` | Multiple profile edit states |
| 12 | Profil Menu | `386:6816` | Full profile menu with all options expanded |
| 13 | Logout confirmation | `386:6927` | Logout confirmation screen |
| 14 | Profil (with menu) | `386:7060` | Profile with account settings open |
| 15 | Logout question | `386:7193` | "Keluar dari Dermaesthetics" — "Apa anda yakin akan keluar" |
| 16 | Delete Account Question | `386:7318` | "Hapus Akun Dermaesthetics" — permanent deletion warning |

### Features

- **Profile Menu Items:**
  - Ubah Profil (Edit Profile)
  - Aktivitas (Activity) — dropdown
  - Daftar Alamat (Address List) — dropdown
  - Bahasa (Language): ID / EN
  - Bantuan (Help) — dropdown
  - Kebijakan & Privasi (Privacy Policy) — dropdown
  - Tentang Dermaesthetics (About) — dropdown
  - Pengaturan Akun (Account Settings) — dropdown

- **Edit Profile Form Fields:**
  - Name
  - Phone number (ubah nomor telepon)
  - Password (ubah password)
  - "Simpan Data" (Save Data) button

- **Password Change Form:**
  - Password Lama (Old Password)
  - Password Baru (New Password)
  - Konfirmasi Password (Confirm Password)
  - Validation: must contain special characters (!@$%)
  - Success toast: "Penggantian password berhasil"

- **Phone Number Change Flow:**
  - "Kami akan mengirimkan verifikasi ke nomor telepon baru Anda"
  - Nomor telepon (current) → Nomor telepon Baru (new)
  - OTP verification
  - Success toast: "Penggantian nomor telepon berhasil"

- **Account Settings (Pengaturan Akun):**
  - "Keluar" (Logout) with log-in icon
  - "Hapus Akun" (Delete Account) with trash icon

- **Logout Dialog:**
  - "Keluar dari Dermaesthetics"
  - "Apa anda yakin akan keluar dari aplikasi Dermaesthetics"
  - "Tidak" / "Ya, Keluar"

- **Delete Account Dialog:**
  - "Hapus Akun Dermaesthetics"
  - "Seluruh data (profil, riwayat transaksi, dll.) akan terhapus permanen"
  - "Tidak" / "Ya, Hapus akun"

---

## Section 5: Create, Update, Delete Address

**Node:** `386:7816`

### Screens

| # | Screen | Node ID | Description |
|---|--------|---------|-------------|
| 1 | Profil | `386:7817` | Profile page in address management flow |
| 2 | Empty State - Address (x2) | `386:8039`, `386:8088` | "Akses lokasi tidak di izinkan" — location permission denied |
| 3 | Tambah Alamat action sheet | `386:8138` | "Tambah Alamat Baru" action sheet |
| 4 | Ubah Jadi alamat utama | `386:8140` | "Ubah Jadi alamat utama" action sheet |
| 5 | Edit alamat | `386:8142` | "Edit alamat" action sheet |
| 6 | Hapus alamat | `386:8144` | "Hapus alamat" action sheet |
| 7 | Daftar Alamat (empty + form) | `386:8217` | Address list with "Tambah Alamat" form |
| 8 | Daftar Alamat (with pin) | `386:8287` | Address with location pinned |
| 9 | Data Alamat form (x2) | `386:8361`, `386:8429` | "Tambah alamat" form with full details |
| 10 | Daftar Alamat (single) | `386:8454` | Address list with one address |
| 11 | Daftar Alamat lebih dari satu | `386:8482` | Address list with multiple addresses |
| 12 | Daftar Alamat (swipe actions) | `386:8548`, `386:8604`, `386:8673` | Address cards with edit/delete/make-primary |
| 13 | Konfirmasi alamat utama | `386:8742` | "Apakah anda ingin mengubah jadi alamat utama" |
| 14 | Daftar Alamat (after edit) | `386:8808` | Updated address list |
| 15 | Daftar Alamat (after delete) | `386:8856` | Address list after deletion |
| 16 | Pin Lokasi | `386:8929` | Map/location pinning screen |
| 17 | Profil (after address changes) | `386:9161` | Profile with updated address count |

### Features

- **Address Form Fields (Tambah Alamat):**
  - Label alamat* (Address label — e.g., "Rumah")
  - Nama penerima* (Recipient name — e.g., "John Doe")
  - Nomor telepon penerima* (Recipient phone — e.g., "081788055858")
  - Kota atau Kecamatan* (City/District — e.g., "DKI Jakarta, Jakarta Timur, Duren Sawit")
  - Kelurahan* (Sub-district — e.g., "Duren Sawit")
  - Kode Pos* (Postal code — e.g., "13440")
  - Pin Lokasi (Location pin with map)
  - Tetapkan koordinat lokasi (Set location coordinates)
  - Alamat lengkap dan catatan kurir (Full address & courier notes)
  - Jadikan alamat utama (Make primary address) toggle
  - "Simpan Alamat" (Save Address) button

- **Address Card Display:**
  - Label: "Rumah" (Home)
  - Badge: "Alamat Utama" (Primary Address)
  - Name & Phone: "John Doe - 08211233214"
  - Full address text
  - "Ubah Alamat" (Edit Address) button
  - Swipe actions: "Jadikan alamat utama" / "Ubah alamat" / "Hapus"

- **Address Action Sheets:**
  - "Tambah Alamat Baru" (Add New Address)
  - "Ubah Jadi alamat utama" (Change to Primary)
  - "Edit alamat" (Edit Address)
  - "Hapus alamat" (Delete Address)

- **Address Delete Confirmation:**
  - "Apakah anda yakin ingin menghapus alamat"
  - "Tidak" / "Ya, Hapus alamat"

- **Location Permission States:**
  - "Akses lokasi tidak di izinkan" (Location access denied)
  - "Izinkan akses lokasi untuk tambah alamat dengan cepat"
  - Two CTAs: "Minta akses lokasi" / "Lanjut isi alamat"

- **Map/Location Pinning:**
  - Interactive map for pinning address location
  - "Tetapkan koordinat lokasi" (Set location coordinates)

- **Success Toasts:**
  - "Berhasil mengubah jadi alamat utama"
  - "Berhasil mengubah alamat"
  - "Berhasil menghapus alamat"

---

## Section 6: Membership & Voucher

**Node:** `386:9162`

### Screens

| # | Screen | Node ID | Description |
|---|--------|---------|-------------|
| 1 | Voucher Homepage | `386:9274` | Main voucher/membership page |
| 2 | Voucher Detail (x3 variants) | `386:9328`, `386:9376`, `386:9424` | Voucher detail page with terms & usage |

### Features

- **Voucher Homepage:**
  - Header: "Voucher"
  - Membership card: "Green Member" — "100 Points"
  - Voucher icon + "50 Vouchers" count
  - "Klaim voucher anda" (Claim your voucher) link
  - Progress bar: "Lakukan transaksi Rp900.000 lagi untuk mencapai level membership berikutnya"
  - Voucher cards list

- **Voucher Detail:**
  - Page title: "Voucher Detail"
  - Voucher name: "Voucher Rp12.000.000 fractional rf laser treatment"
  - Validity: "Valid sampai 27 Januari 2026"
  - "Gunakan Voucher" (Use Voucher) CTA button
  - Expandable sections:
    - "Syarat dan ketentuan" (Terms & Conditions)
    - "Cara Pakai" (How to Use)
    - "Deskripsi Voucher" (Voucher Description)

- **Membership Tiers:**
  - Green Member (entry level)
  - Gold (higher tier)
  - Points system: "100 Points" / "30 Points"
  - Progress to next tier: "Lakukan transaksi Rp900.000 lagi untuk mencapai level membership berikutnya"

---

## Cross-Cutting Features & UI Patterns

### Brand Ecosystem (8+ brands)

| # | Brand | Notes |
|---|-------|-------|
| 1 | Dermaster | Primary brand |
| 2 | Derma Express | Sub-brand |
| 3 | Dermalicious | Sub-brand |
| 4 | Dexskin | Sub-brand |
| 5 | Dermaklin | Sub-brand |
| 6 | Dexbeauty | Sub-brand |
| 7 | Filterbaby | Sub-brand |
| 8 | Lainnya (Others) | Contains: Dermaster Plastic Surgery, Dermaster Hair Surgery |

### Product/Service Features

- "Booking Treatment" (Book Treatment) — navigation item
- "Produk Kecantikan" (Beauty Products) — navigation item
- "Keranjang" (Shopping Cart)
- "Semua Produk" (All Products)
- "Rekomendasi Produk" (Recommended Products)
- "Free Pico Derma Treatment" promotion
- "See Detail" links on product/treatment cards
- "100K+ Review" badge on product cards
- "Kode Promo" (Promo Code) input
- "Klaim Voucher" (Claim Voucher) button

### Promotional Features

- "Promo 3.3" promotional banners
- Promo carousel slides (Promo Slide 2, 3, 4, 5)
- "Pilihan Voucher Eksklusif" (Exclusive Voucher Selection) section
- "Nikmati diskon spesial bulan maret" (Enjoy special March discount)

### Shipping Features

- "Informasi Pengiriman" (Shipping Information)
- "Metode Pengiriman" (Shipping Method)
- "Menunggu Pembayaran" (Awaiting Payment)

### Help/Support

- "Help Center" screen
- "Chat Sekarang" (Chat Now) — live chat
- "Kebijakan & Privasi" (Privacy Policy)
- "Tentang Dermaesthetics" (About Dermaesthetics)

### Common UI Elements

- Android-status-bar (device status bar)
- Navbar Buat Janji (bottom navigation bar — "Make Appointment")
- Back button ("arrow-left 1" / "Kembali")
- "Lanjutkan" (Continue) button
- "Simpan Data" (Save Data) button
- "Simpan Password" (Save Password) button
- Loading state: "Mengecek Informasi" (Checking Information)
- Success toasts: "Berhasil Mengubah Profil", "Registrasi Berhasil", "Login Berhasil"
- Error states: "Informasi Tidak Valid", "Data Akun Tidak Sesuai", "Informasi Belum Lengkap"
