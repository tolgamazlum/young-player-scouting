# 🧠 Young Player Scouting – Europe's Top 5 Leagues (2024/25)

## 📌 Proje Özeti

Bu projede, Avrupa'nın 5 büyük liginde forma giyen 23 yaş altı oyuncuların performansları veriyle analiz edilerek **en verimli genç oyuncular** tespit edilmeye çalışıldı.

### ⚽ Amaç:
Sadece Python kullanarak, sahada izlenmeden de oyuncu potansiyeli hakkında fikir edinilebileceğini göstermek.  
Projede dripling, gol, asist gibi çeşitli metrikler kullanılarak **özgün bir verimlilik skoru** hesaplandı.

---

## 🛠 Kullanılan Araçlar & Kütüphaneler

- Python 3
- Pandas
- Matplotlib
- (Opsiyonel: NumPy)

---

## 📁 Veri Seti

- 📦 Kaynak: [Kaggle Dataset – Football Players Stats 2024/25](https://www.kaggle.com/datasets/hubertsidorowicz/football-players-stats-2024-2025)
- İçerik: Avrupa'nın 5 büyük liginde forma giyen futbolcuların maç başı ortalama istatistikleri (dripling, asist, şut, top kaybı vb.)

---

## 🔍 Analiz Adımları

1. Veri yükleme ve ilk inceleme
2. Yalnızca 23 yaş altı oyuncuların filtrelenmesi
3. Bazı oyuncuların elenmesi (kaleci, pozisyonsuz oyuncular vs.)
4. Özgün metrikler oluşturma:
   - **Progressive carries**
   - **Carrier efficiency**
5. En etkili genç oyuncuların sıralanması
6. 📊 Görselleştirme ile öne çıkan isimlerin sunulması

---

## 📊 Örnek Çıktı

![scouting-result](results/efficiency_scores.png)

---

## 🚀 Nasıl Çalıştırılır?

1. `requirements.txt` içeriğini yükleyin:
   ```bash
   pip install -r requirements.txt
   ```

2. Notebook'u çalıştırın:
   ```bash
   jupyter notebook notebook/scouting_analysis.ipynb
   ```

3. Gerekli veri dosyasını Kaggle’dan indirip `data/` klasörüne koyun.

---

## 👤 Yazar

**TOLGA MAZLUM**  
İstatistik öğrencisi | Python, R, SQL | Spor analitiği tutkunu  
📎 [LinkedIn](https://www.linkedin.com/in/tolgamazlum/) | 🔗 [Kaggle Notebook](https://www.kaggle.com/code/tolgamazlum/young-player-scouting-europe-s-top-5-leagues)

---

## 🤔 Neden Bu Proje?

> Scouting sadece gözlemle mi olur?  
> Verilerle de potansiyel görülebilir mi?  
Bu soruların cevabını yalnızca Python ile aradım.  
Sonuçlar, verinin sahayı ne kadar doğru okuyabildiğini bir kez daha gösterdi.

---

## 🏷 Etiketler

`#Python` `#Pandas` `#FootballAnalytics` `#DataScience` `#Scouting` `#SportsTech`
