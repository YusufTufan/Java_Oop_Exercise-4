#Daire Sınıfı
```java
public class Main {
    public static void main(String[] args) {
        // Daire nesnesi oluşturma ve başlangıç değerlerini atama
        Daire daire1 = new Daire(5, 3, 4);

        // Alan ve çevre hesaplamalarını yazdırma
        System.out.println("Dairenin Alanı: " + daire1.alan());
        System.out.println("Dairenin Çevresi: " + daire1.cevre());

        // Merkezden orijine uzaklığı yazdırma
        System.out.println("Merkezden Orijine Uzaklık: " + daire1.merkezeUzaklik());

        // Başka bir daireye olan uzaklığı hesaplama ve yazdırma
        Daire daire2 = new Daire(3, -1, 2);
        System.out.println("Başka Bir Daireye Olan Uzaklık: " + daire1.digerDaireyeUzaklik(daire2));

        // Dairenin özelliklerini güzel bir şekilde yazdırma
        System.out.println(daire1);
    }
}
```

Bu kod parçası `Daire` sınıfını kullanarak bir dairenin alanını, çevresini, merkezinden orijine olan uzaklığını ve başka bir daireye olan uzaklığını hesaplar ve yazdırır. Ayrıca, `toString()` metodunun nasıl kullanılabileceğini de gösterir.
