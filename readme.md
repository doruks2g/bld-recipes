# 📦 BLD-RECIPES

> [!CAUTION]
> **ÖNEMLİ:** Bu depo bir **HOBİ PROJESİDİR**. Profesyonel sistemlerde tek paket yöneticisi olarak kullanıma uygun değildir. Sistem güvenliği ve kararlılığı için kullanıcı sorumludur.

### ❓ Bld-Recipes Nedir?
`bld-recipes`, [bld](https://github.com/doruks2g/BLD) paket yöneticisinin paketleri indirmek, derlemek ve kurmak için ihtiyaç duyduğu tüm reçetelerin (`.bld` dosyalarının) bulunduğu merkezi depo yeridir. 

`bld` programı, `bld update` komutuyla doğrudan bu depoya bağlanır ve en güncel paket tanımlarını bilgisayarınıza senkronize eder.

### 🛠️ Katkıda Bulunun
Bu ekosistemi büyütmek için katkılarınıza ihtiyacımız var! Eğer sistemde olmayan bir yazılımın reçetesini hazırladıysanız:
1. Depoyu fork'layın.
2. Yeni `.bld` dosyanızı ekleyin.
3. Bir **Pull Request (PR)** gönderin.

Reçetelerinizi eklerken mevcut formatı takip etmeye özen gösterin.

### 📄 Reçete Formatı
```plaintext
NAME:paket_adı
VERSION:1.0.0
URL:https://kaynak-kod-adresi.tar.gz
BUILD:./configure --prefix=$PKG_DIR && make
INSTALL:make install
DEPS:varsa_bagimliliklar
