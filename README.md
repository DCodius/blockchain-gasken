# **Platform Gassken: Ekosistem Perdagangan & Identitas Web3**

Platform Gassken adalah platform perdagangan generasi baru yang menjembatani sistem ERP tradisional (Odoo) dengan teknologi *blockchain* (Hyperledger Besu) dan identitas terdesentralisasi (Hyperledger Aries). Proyek ini dirancang untuk menciptakan ekosistem UMKM yang aman, transparan, dan efisien dengan fokus pada privasi data (sesuai UU PDP).

## **Pilar Teknologi**

Proyek ini mengintegrasikan teknologi modern WEB3:

* **Blockchain:** Hyperledger Besu (EVM-Compatible) sebagai buku besar global yang transparan dan *immutable*.  
* **Identitas (SSI):** Hyperledger Aries untuk pertukaran kredensial terverifikasi (ZKP) tanpa mengekspos data pribadi.  
* **Database:** YugabyteDB (Distributed SQL) untuk sinkronisasi data yang tangguh dan tahan bencana.  
* **Message Broker:** NATS JetStream untuk arsitektur berbasis kejadian (*event-driven*) yang berkinerja tinggi.

## **Fitur Utama**

1. **Triple-Entry Accounting:** Rekonsiliasi transaksi secara otomatis antara buku besar perusahaan, dompet digital pengguna, dan catatan *on-chain* yang terverifikasi.  
2. **Reputasi On-Chain (SCORE):** UMKM membangun reputasi melalui sejarah transaksi nyata, bukan sekadar ulasan subjektif.  
3. **Loyalitas Digital (CREDIT):** Token loyalitas yang dapat diprogram untuk memberi insentif pada partisipasi ekonomi.  
4. **Privasi Maksimal:** Menggunakan *Zero-Knowledge Proofs* (ZKP) sehingga informasi sensitif tidak pernah tersimpan di *blockchain*.  
5. **Audit Tanpa Intrusif:** Pemerintah/Regulator dapat mengaudit ekonomi regional melalui dasbor *real-time* tanpa perlu mengakses data pribadi warga.

*Panduan Memulai**

Untuk menjalankan lingkungan pengembangan lokal, pastikan Anda telah menginstal:

1. **Node.js (v18+)** dan **Yarn**.  
2. **Docker Desktop** (untuk NATS & YugabyteDB).  
3. **WSL2 atau VirtualBox** untuk menjalankan node Hyperledger Besu.

Lihat dokumentasi teknis di folder docs/ untuk instruksi instalasi mendalam.

*Proyek ini dirancang untuk skalabilitas tinggi, keamanan data yang ketat, dan pemberdayaan UMKM melalui teknologi Web3 yang inklusif.*
