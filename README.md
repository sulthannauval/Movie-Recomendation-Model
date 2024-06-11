# Movie-Recomendation-Model
Tugas Riset Rekrutasi I-Smile Laboratory

## Movie Recommender Systems:

1) Movie Description Based Recommender
2) Movie Metadata Based Recommender
3) User Rating Based Recommender

## Cara Penggunaan:

1) Import Library yang digunakan dalam Source Code.
2) Load Dataset
   Terdapat 4 Dataset yang digunakan, dapat dilihat pada Folder 'Dataset'
   * Dataset yang digunakan untuk 'Movie Description Based' dan 'Movie Metadata Based' adalah 'tmdb_5000_credits.csv' dan 'tmdb_5000_movies.csv'.
   * Dataset yang digunakan untuk 'User Rating Based' adalah movie.csv dan rating.csv.
   * Note : Jika ingin menggunakan Dataset baru atau ingin menambahkan Dataset, perlu dilakukan penyesuaian. (Ketentuan Dataset ada di bawah).
3) Pada setiap Jenis Recommender terdapat bagian 'Preprocessing', harap running Cell tersebut dalam Source Code pada Sub-Bagian Jenis Recommender yang ingin digunakan.
4) Running Cell bagian 'Recommender' dalam Source Code pada Sub-Bagian Jenis Recommender tersebut, kemudian masukkan judul Film yang ingin dibuatkan rekomendasi
5) Sistem akan menampilkan rekomendasi berdasarkan Jenis Recommender yang digunakan.

## Ketentuan Dataset:

1) Dataset yang digunakan untuk Movie Description Based Recommender harus terdapat kolom:
   - Judul Film
   - Deskripsi/Overview/Sinopsis Film
2) Dataset yang digunakan untuk Movie Metadata Based Recommender harus terdapat kolom:
   - Judul Film
   - Director
   - Cast
   - Keywords
   - Genres
   * Note : Cast, Keywords, dan Genre dalam bentuk list dengan isi maksimal 3
3) Dataset yang digunakan untuk User Rating Based Recommender harus terdapat kolom:
   - Judul Film
   - Rating
   - User ID
   - Movie ID
