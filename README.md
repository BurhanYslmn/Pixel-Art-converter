# Pixel Art & Block Converter

[Uygulamayı Aç](https://burhanyslmn.github.io/Pixel-Art-converter/) · [GitHub](https://github.com/BurhanYslmn/Pixel-Art-converter)

Pixel Worlds blokları ve arka planlarıyla fotoğraflardan mozaik oluşturma ve düzenleme aracı. Mobil ve masaüstü tarayıcılarda çalışır.

| Seçenek | Ne işe yarar? |
|---|---|
| **Option 1** | Fotoğrafı klasik pixel art'a dönüştür. Kare ve çıktı ölçülerini belirle. |
| **Option 2** | Fotoğrafı hazır Blocks ve Backgrounds dokularıyla 80×57 dünya ızgarasına dönüştür. Izgarayı aç/kapat, PNG veya JSON indir. |
| **Option 3** | Oluşturulan dünyayı düzenle. Taşı, Silgi, Damlalık, Klonla ve Geri Al kullan; PNG/JSON kaydet. |
| **Option 4** | JSON dosyasını yükle, görseli incele; bir kareye tıklayarak blok adlarını, kullanılan blokların adetlerini gör. |

**Varsayılan World Designer çıktısı:** 80 × 57 blok, 2560 × 1920 piksel.

## Görsellerin yüklenmesi

`index.html` ile `Blocks/`, `Backgrounds/`, `Props/` ve `Orbs/` klasörleri **aynı ana klasörde** bulunmalıdır. HTML içinde hazır katalog tanımlıdır; ayrıca görsel yüklemeye gerek yoktur. ZIP dosyasının içindeki HTML'yi doğrudan açmak yerine **ZIP'i tamamen ayıklayın**. Sadece `index.html` dosyasını farklı bir klasöre taşırsanız görseller bulunamaz.

GitHub'a yüklerken klasörlerin **tamamını** deponun kök dizinine aktarın. Önceden bu klasörler varsa yalnızca güncellenmiş `index.html` dosyasını değiştirebilirsiniz.

---

**English:** The app offers pixel art conversion, Pixel Worlds Blocks/Backgrounds mosaic generation, editable World Designer mode, and a JSON project inspector with block names and counts. Extract the whole ZIP before opening `index.html`; keep all asset folders beside it.
