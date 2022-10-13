## Nama : Mukhtarijal   NIM : 21343009   Prodi : Informatika
1. Pada pertemuan ke-8 ini, saya belajar tentang Array dalam pemograman java. Sama dengan konsep array pada bahasa pemograman lain, Array merupakan sebuah variabel yang menyimpan sekumpulan data yang memiliki tipe data sama. Setiap data tersebut menempati lokasi atau alamat memori yang berbeda-beda dan selanjutnya disebut dengan elemen array. Elemen array itu kemudian dapat diakses melalui indeks yang terdapat di dalamnya. Indeks array selalu dimulai dari 0.
2. Contoh penerapan Array pada java yaitu misal pada src Tugas2 JS-08
3. /*
 * Created by 21343009_Mukhtarijal
 */
public class Tugas1 {
    public static void main(String[] args) {
        String days[] = {"Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday",};
        for (int i =0;i < days.length; i++) {
            System.out.println(days[i]);
        }
    }
}

4. Pada program tsb, saya membuat variable array dengan tipe string dan menampung nilai yaitu nama-nama hari. Kemudian ditampilkan dengan perulangan for
