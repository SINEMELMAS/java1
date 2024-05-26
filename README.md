# java1
package lab1;

public class ArrayProcessingExample {


	    public static void main(String[] args) {
	        // İki boyutlu bir dizi tanımlama ve oluşturma
	        int[][] ikiBoyutluDizi = new int[3][4];

	        // Değerleri atama
	        for (int i = 0; i < ikiBoyutluDizi.length; i++) {
	            for (int j = 0; j < ikiBoyutluDizi[i].length; j++) {
	                ikiBoyutluDizi[i][j] = i + j;
	            }
	        }

	        // Değerleri ekrana yazdırma (geliştirilmiş for döngüsü)
	        for (int[] satir : ikiBoyutluDizi) {
	            for (int eleman : satir) {
	                System.out.print(eleman + " ");
	            }
	            System.out.println(); // Her satırın sonunda yeni bir satıra geç
	        }
	    }
	}

