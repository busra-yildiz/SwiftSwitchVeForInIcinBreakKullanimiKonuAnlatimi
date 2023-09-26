# SwiftSwitchVeForInIcinBreakKullanimiKonuAnlatimi
Swift programlama dilinde break ifadesi, döngüleri veya switch ifadelerini aniden sonlandırmak için kullanılır. break, döngü içinde veya
switch ifadesi içinde çalıştırıldığında, o anki döngüyü veya switch ifadesini terk eder ve döngüden veya switch ifadesinden çıkar.

İşte break ifadesinin for-in döngüsü ve switch ifadesi içinde nasıl kullanılacağına dair örnekler:

for-in Döngüsünde break Kullanımı:
for-in döngüsünde break kullanarak döngüyü sonlandırabilirsiniz. Örneğin, bir dizi üzerinde dolaşırken belirli
bir koşulu sağlayan bir öğeyi bulduğunuzda döngüyü sonlandırmak için break kullanabilirsiniz:

let sayilar = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
let aranacakSayi = 5

for sayi in sayilar {
    if sayi == aranacakSayi {
        print("Sayı bulundu!")
        break // Döngüyü sonlandır
    }
}

Bu örnekte, break ifadesi, aranacakSayi'yi bulduğumuzda döngüyü sonlandırır.

switch İfadesinde break Kullanımı:
switch ifadesinde break kullanarak, eşleşen bir durumun işlendikten sonra switch ifadesini sonlandırabilirsiniz. Örneğin, farklı meyve türlerini 
kontrol eden bir switch ifadesinde break kullanabilirsiniz:

let meyve = "elma"

switch meyve {
case "elma":
    print("Bu bir elmadır.")
    break // Switch ifadesini sonlandır
case "armut":
    print("Bu bir armuttur.")
    break // Switch ifadesini sonlandır
case "muz":
    print("Bu bir muzdur.")
    break // Switch ifadesini sonlandır
default:
    print("Bu bir bilinmeyen meyvedir.")
}

Bu örnekte, her bir case ifadesi içinde break kullanarak, eşleşen bir durum işlendikten sonra switch ifadesini sonlandırıyoruz.

break ifadesi, belirli koşullar altında döngüleri veya switch ifadelerini kontrol etmek için kullanılır ve programın daha temiz ve etkili bir şekilde çalışmasına yardımcı olur. Ancak dikkatli olmalısınız, 
yanlış yerlerde kullanıldığında beklenmeyen sonuçlara neden olabilir.
