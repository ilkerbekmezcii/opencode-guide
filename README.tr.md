🌍 [English](README.md) | [Türkçe](README.tr.md)

# 🔓 OpenCode — Topluluk Rehberi

> Açık kaynaklı OpenCode kodlama ajanı için pratik ve bağımsız bir rehber.

<div align="center">

![Rehber Lisansı](https://img.shields.io/badge/rehber%20lisansı-MIT-green)
![OpenCode](https://img.shields.io/badge/OpenCode-v2-black)
![Platform](https://img.shields.io/badge/platform-Terminal-blue)

**Terminal, masaüstü veya web iş akışınızda açık kaynaklı bir kodlama ajanı kullanın.**

</div>

---

## OpenCode Nedir?

**OpenCode**, açık kaynaklı bir yapay zeka kodlama ajanıdır. Terminal arayüzü, masaüstü uygulaması ve web uygulaması olarak kullanılabilir; birden fazla model sağlayıcısına bağlanabilir.

Bu depo **bağımsız bir topluluk rehberidir**. OpenCode'un resmi deposu değildir ve proje geliştiricileri tarafından desteklendiği veya onaylandığı anlamına gelmez.

## Kurulum

### Kurulum betiği

```bash
curl -fsSL https://opencode.ai/v2/install | bash
```

### npm

```bash
npm install -g @opencode/cli
```

### Homebrew

```bash
brew install anomalyco/tap/opencode-v2
```

Resmi OpenCode indirme sayfasında bağımsız binary dosyaları da bulunmaktadır. Güncel resmi dokümantasyona göre v2 CLI için Windows paket yöneticileri desteklenmemektedir.

OpenCode'u başlatın:

```bash
opencode
```

## Model Sağlayıcısı Bağlama

OpenCode içinde:

```text
/connect
```

komutunu kullanın ve bağlamak istediğiniz sağlayıcıyı seçin.

## Hızlı Başlangıç

Terminali proje klasörünüzde açın:

```bash
opencode
```

Örnek istekler:

```text
Bu repoyu açıkla ve en önemli dosyaları belirt.
Dış API'yi değiştirmeden başarısız testleri düzelt.
Bu fonksiyonu davranışını değiştirmeden yeniden düzenle.
Mevcut diff'i olası regresyonlar açısından incele.
```

## Kullanışlı Çalışma Şekilleri

### Bir projeyi anlamak

```text
Mimariyi özetle ve isteklerin uygulamaya nereden girdiğini göster.
```

### Özellik geliştirmek

```text
Bu endpoint'e sayfalama ekle ve testleri güncelle.
```

### Kod incelemek

```text
Mevcut değişiklikleri hata, güvensiz varsayım ve eksik testler açısından incele.
```

### Web eşleştirme

OpenCode şu komutla yerel bir web arayüzü açabilir:

```bash
opencode pair
```

Komutun gösterdiği yerel adres ve giriş bilgilerini kullanın.

## Özelleştirme

OpenCode; yapılandırma, eklentiler, MCP sunucuları, özel komutlar, temalar ve tuş atamalarını destekler. Bu özellikler hızlı değişebildiği için güncel yapılandırma biçimi için resmi dokümantasyonu kullanın.

## Güvenli Kullanım İpuçları

- Geniş değişiklikleri kabul etmeden önce shell komutlarını ve dosya düzenlemelerini inceleyin.
- API anahtarlarını ve gizli bilgileri sürüm kontrolü dışında tutun.
- Değişiklikleri inceleyebilmek ve geri alabilmek için Git kullanın.
- Ajan tarafından yapılan değişikliklerden sonra proje testlerini çalıştırın.
- Daha güçlü izolasyon gerektiğinde container veya sanal makine kullanın.

## Resmi Kaynaklar

- Resmi web sitesi: https://opencode.ai
- Resmi dokümantasyon: https://opencode.ai/v2/docs
- Resmi depo: https://github.com/anomalyco/opencode

## Lisans

Bu **rehberin içeriği** [MIT Lisansı](LICENSE) ile sunulmaktadır.

OpenCode kendi proje geliştiricileri tarafından sürdürülür ve kendi lisans şartları altında dağıtılır. Güncel proje koşulları için resmi depoya bakın.

---

Bu rehberi faydalı buluyorsanız repoya yıldız vermeniz diğer geliştiricilerin de keşfetmesine yardımcı olur.
