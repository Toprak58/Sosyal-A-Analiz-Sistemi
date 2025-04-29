# 👥 Sosyal Ağ Analizi (C Projesi)

Bu proje, C dili ile yazılmış bir **sosyal ağ analiz sistemidir**. Kullanıcılar ve arkadaşlık ilişkileri üzerinden toplulukları, etkileyici kullanıcıları ve arkadaş ağlarını analiz etmeye olanak tanır.

## 📌 Özellikler

- Kullanıcı ve arkadaşlık ilişkileri ekleme
- Derinlik öncelikli arama (DFS) ile belirli mesafedeki arkadaşları listeleme
- Ortak arkadaşları bulma
- Topluluk (bağlı bileşen) tespiti
- Etki alanı (bir kullanıcının etkilediği kişi sayısı) hesaplama
- Red-Black Tree (Kırmızı-Siyah Ağaç) ile kullanıcı arama

## 🛠 Kurulum ve Derleme

### Gereksinimler

- C derleyicisi (GCC, MinGW, Clang, vs.)
- (Opsiyonel) Dev-C++, Code::Blocks veya VSCode gibi bir C IDE’si

### Derleme

Linux/macOS:
```bash
gcc -o sosyal_ag main.c
./sosyal_ag
