# Kurulum Rehberi

Bu rehber, **PuzzleCans** projesini yerel makinenize kurup Unity Editor üzerinde çalıştırmanız için gerekli adımları içermektedir.

##  Gereksinimler

Projeyi sorunsuz bir şekilde açabilmek için aşağıdaki yazılımların sisteminizde kurulu olması gerekmektedir:

*   **Unity Hub:** Unity projelerini ve versiyonlarını yönetmek için kullanılır.

*   **Unity Editor 2022.3.15f1:** Projenin geliştirildiği Unity versiyonu.

*   **Android Build Support** modülü (APK çıktısı alabilmek için).


##  Adım Adım Kurulum

1.  **Web sitemizi açın**
Aşağıda linki verilen web sitesine girip yapıp Hemen indir butonuyla gelecek olan APK indir butonuna tıklamanız yeterli:
https://osmanaydogan.github.io/PuzzleCans_Websitee/

2.  **Projeyi Unity Hub ile Açın:**
    *   Unity Hub'ı başlatın.
    *   `Projects` sekmesindeyken sağ üstteki `Open` düğmesine tıklayın.
    *   Açılan dosya gezgini penceresinden, 1. adımda klonladığınız `PuzzleCans` proje klasörünü seçin.

3.  **Unity Editor'ün Açılmasını Bekleyin:**
    *   Unity Hub, projeyi doğru editör versiyonuyla (2022.3.15f1) açacaktır.
    *   Editör ilk açılışta projeyi içeri aktaracak (import) ve gerekli `Library` klasörünü oluşturacaktır. Bu işlem projenin büyüklüğüne ve bilgisayarınızın performansına göre birkaç dakika sürebilir.

4.  **Projeyi Çalıştırın:**
    *   Proje başarıyla açıldıktan sonra, `Assets/Scenes/MainMenu.unity` sahnesini açın.
    *   Unity Editor'ün üst kısmındaki  (Play) düğmesine basarak oyunu başlatabilirsiniz.

## 🔧 Sorun Giderme (Troubleshooting)

*   **Hata: "Project has been moved or deleted"**
    *   **Çözüm:** Projeyi klonladığınız yerden taşımadığınızdan emin olun. Eğer taşıdıysanız, Unity Hub listesinden projeyi kaldırıp `Open` ile yeniden ekleyin.

*   **Hata: "Script compilation errors"**
    *   **Çözüm:** Projenin doğru Unity versiyonu (2022.3.15f1) ile açıldığından emin olun. Farklı bir versiyon, API uyumsuzluklarına neden olabilir. Unity Hub üzerinden doğru versiyonu yükleyebilirsiniz.

*   **Hata: "Missing packages"**
    *   **Çözüm:** Unity Editor'de `Window > Package Manager` menüsünü açın. Sağ üstteki `Packages: In Project` seçeneğini kontrol edin ve eksik paketler varsa yeniden yüklemeyi deneyin. 