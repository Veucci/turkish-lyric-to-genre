---
license: cc-by-nc-4.0
datasets:
- Veucci/turkish-lyric-to-genre
language:
- tr
library_name: transformers
tags:
- music
widget:
  - text: Çaldığın o kalbi yerine koy lütfen Eğer hislerinden pek emin değilsen
      Aradığın aşksa en güzelinden O zaman başka Açarım kapıları hazırım dünden
      Çaldığın o kalbi yerine koy lütfen Eğer hislerinden pek emin değilsen
      Aradığın aşksa en güzelinden O zaman başka Açarım kapıları hazırım dünden
    example_title: (Pop) O Sen Olsan Bari - Aleyna Tilki
  - text: Nefes alamam, boğazıma kadar dolu Yük dolu, kül dolu iç yarası Bu kez
      yaramaz, ilaçlar ama Sonun ölüm dostum o yüzden iç yarasın Nefes alamam,
      boğazıma kadar dolu Yük dolu, kül dolu iç yarası Bu kez yaramaz, ilaçlar
      ama Sonun ölüm dostum o yüzden iç yarasın Karanlık ev, bu sokak, bütün
      gezegen Ateş yak, ateş yak eskimiş seneler Zaman ilaç dediler ne gelir
      elimden? Işıksızım bir şık seçtim inanıp derinden Umrumda mı sandın dünya
      oynasın yerinden Kıyamet kopsun severim erinmem Ölümden değil korkum
      gittiğimde yenilmen O gün cevap bulursun öpmek yarayı geçirmez Buraya
      kadar, kanayamam artık Yapıştı yakama, buraya kadar Kaçamam asla yine
      yakalar Son nefesini ver, buraya kadar
    example_title: (Hip-Hop) Nefes Alamam - Aspova
  - text: Bedava yaşıyoruz, dostlar bedava Hava bedava, bulut bedava Dere tepe
      bedava, yağmur çamur bedava Bedava yaşıyoruz, dostlar bedava Hava bedava,
      bulut bedava Dere tepe bedava, yağmur çamur bedava Otomobillerin dışı,
      sinemaların kapısı Otomobillerin dışı, sinemaların kapısı Camekanlar,
      onlar bedava Camekanlar, onlar bedava Peynir ekmek değil ama acı su bedava
      Kelle fiyatına hürriyet, esirlik bedava Peynir ekmek değil ama acı su
      bedava Kelle fiyatına hürriyet, esirlik bedava Bedava yaşıyoruz, dostlar
      bedava
    example_title: (Rock) Bedava Yaşıyoruz - Cem Karaca
  - text: Nikâhına beni çağır, sevgilim İstersen şahidin olurum senin Bu adam kim?
      diye soran olursa Eski bir tanıdık dersin, sevgilim Nikâhına beni çağır
      sevgilim İstersen şahidin olurum senin Bu adam kim diye soran olursa Eski
      bir tanıdık dersin, sevgilim Hayaller kurardık biz yıllar önce Hiç yoktu
      hesapta ayrılık bizce Bilirsin ne kadar görmek isterdim Beyazlar içinde
      seni öylece Hayaller kurardık biz yıllar önce Hiç yoktu hesapta ayrılık
      bizce Bilirsin ne kadar görmek isterdim Beyazlar içinde seni öylece
      Garibin biriysem sevemez miyim? Aşkla karın doymaz diyen ben miyim? Şimdi
      çok zenginsin, ben ayrı garip Sana bir buket gül veremez miyim?
    example_title: (Arabesk) Nikah Masası - Ümit Besen
---

# Lyrics Genre Classification Model

## Description

The model was trained using the BERT language model on a song lyrics dataset to predict the genre of a given song based on its lyrics. This repository houses the machine learning model, which is capable of making predictions in four distinct genres: Pop, Rock, Hip-Hop and Arabesk.
For training and test codes check out [Github page](https://github.com/Veucci/turkish-lyric-to-genre).

## Dataset

The model was trained on a diverse and labeled dataset of song lyrics, which contained 3172 rows. The dataset was carefully curated to include songs from a wide range of artists and genres, ensuring a comprehensive representation of Pop, Rock, Hip-Hop and Arabesk music.
[DATASET](https://huggingface.co/datasets/Veucci/turkish-lyric-to-genre)

## License

This dataset is released under the Creative Commons Attribution-NonCommercial license. This means that you are not allowed to use the dataset for commercial purposes. For detailed information about the license, please refer to the [LICENSE](./LICENSE) file.

## Contact

If you have any questions, suggestions, or concerns regarding this dataset, please feel free to reach out to email at [efe.ozkan732@gmail.com](mailto:efe.ozkan732@gmail.com).
I hope this model helps in your genre classification tasks and inspires further exploration of song lyrics analysis!

