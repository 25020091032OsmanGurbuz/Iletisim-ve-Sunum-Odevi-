Bu proje, İletişim ve Sunum Teknikleri dersi için C dilinde geliştirilmiş temel bir "Hoş Geldiniz" uygulamasıdır. Windows konsolunda Türkçe karakterlerin (İ, ş, ü vb.) doğru görüntülenmesi için UTF-8 (65001) kod sayfasını kullanır.

Özellikler:

Dil: C

Karakter Desteği: Windows API (SetConsoleOutputCP) kullanılarak sağlanan UTF-8 desteği.

İçerik: Konsol üzerinden karşılama mesajı çıktısı.

Seçenek 2: Teknik Detaylı
Başlık: C-Console-UTF8-Example
Açıklama:
Windows ortamında C dili ile yazılmış, konsol çıktı kodlamasını dinamik olarak değiştiren basit bir uygulama örneğidir. Proje, standart stdio.h kütüphanesinin yanı sıra, konsol ayarlarını yönetmek için windows.h kütüphanesini kullanır.

Teknik Notlar:

SetConsoleOutputCP(65001); fonksiyonu ile konsolun çıktı kodlaması UTF-8'e ayarlanmıştır.

Derlenmiş çalıştırılabilir dosya (library.exe) proje dizininde mevcuttur.

GitHub İçin Örnek README.md İçeriği
Aşağıdaki metni kopyalayıp projenizin ana dizinine README.md adıyla kaydedebilirsiniz:

Markdown
# İletişim ve Sunum Teknikleri Uygulaması

Bu depo, İletişim ve Sunum Teknikleri dersi kapsamında oluşturulmuş basit bir C programını içermektedir.

## İçerik
- `library.c`: Uygulamanın kaynak kodu.
- `library.exe`: Uygulamanın derlenmiş çalıştırılabilir hali.

## Nasıl Çalıştırılır?
1. Bir C derleyicisine (GCC, Clang veya MSVC) sahip olduğunuzdan emin olun.
2. Kaynak kodu derlemek için:
   ```bash
   gcc library.c -o library.exe
Uygulamayı çalıştırın:

Bash
./library.exe
