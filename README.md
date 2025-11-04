# Latihan-ukl-sedang-2

Bagian 1 

    public class HitungVolume {

    static double volumeTabung(double jariJari, double tinggi) {
        double volume = Math.PI * jariJari * jariJari * tinggi;
        return volume;
    }

Program ini digunakan untuk **menghitung volume tabung** berdasarkan jari-jari dan tinggi yang diberikan pengguna.

   public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.println("Masukkan jari-jari tabung: ");
        double r = input.nextDouble();

        System.out.println("Masukkan tinggi tabung: ");
        double t = input.nextDouble();

        double hasilVolume = volumeTabung(r, t);

        System.out.println("\n=== HASIL PERHITUNGAN ===");
        System.out.println("Jari-jari : " + r + " cm");
        System.out.println("Tinggi    : " + t + " cm");
        System.out.println("Volume tabung : " + hasilVolume + " cm³");

        input.close();
    }
    }

  Program ini digunakan untuk menghitung volume tabung secara interaktif. Pertama, program meminta pengguna memasukkan jari-jari dan tinggi tabung,
  kemudian nilai-nilai tersebut dikirim ke fungsi `volumeTabung` untuk dihitung volumenya. Setelah perhitungan selesai, program menampilkan jari-jari,
  tinggi, dan volume tabung secara rapi di layar.
  
 OUTPUT 
 
  <img width="670" height="306" alt="Screenshot 2025-11-05 002834" src="https://github.com/user-attachments/assets/8a8250ca-49a7-4692-bda6-6dc939599915" />






