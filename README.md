# Latihan-Eksplorasi-Materi-Graphical-User-Interface-pada-Java
Nama : Sarah Amelia Agustina Putri
NIM : F1D02510133

Deskripsi
Program GUI sederhana dengan Java Swing. Pengguna mengisi nama, lalu menekan tombol Tampilkan untuk memunculkan tulisan "Halo, (nama)", atau tombol Hapus untuk mengosongkan kembali.

5 Komponen Utama GUI yang digunakan:
1. Top-level Container Class (FrameUtama (extends Jframe)) sebagai jendela utama aplikasi.
2. Intermediate Container Class	(PanelForm (extends JPanel)) sebagai wadah yang mengelompokkan label, kolom nama, dan tombol.
3. Atomic Component Class	(TombolKu (extends JButton), JLabel, JTextField) sebagai komponen dasar yang tidak bisa diisi komponen lain.
4. Layout Classes	(BorderLayout, FlowLayout, GridLayout) untuk mengatur posisi komponen di dalam container.
5. Event Listener	(AksiTampil (implements ActionListener), AksiHapus (extends MouseAdapter)) untuk menangani klik tombol dengan meng-override (actionPerformed) dan (mouseClicked).

Penggunaan Layout
BorderLayout: membagi FrameUtama dan PanelForm menjadi bagian atas, tengah, dan bawah.
FlowLayout: menyusun label "Nama" dan kolom nama berjajar ke samping.
GridLayout: membagi dua tombol (Tampilkan dan Hapus) menjadi sama lebar.


<img width="472" height="232" alt="Tampilan_Awal" src="https://github.com/user-attachments/assets/ce653b32-097c-40d9-9889-ac57ffcaf2c1" />

<img width="472" height="232" alt="Tampilan_GUI" src="https://github.com/user-attachments/assets/2a07e4b8-1ed1-4b09-97be-1cde76753a2c" />

