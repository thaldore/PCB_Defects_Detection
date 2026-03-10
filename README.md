# 🛠️ PCB Defect Detection — Baskılı Devre Kartı Hata Tespiti

> **Deep learning-powered defect detection for Printed Circuit Boards (PCBs) using YOLOv8n & YOLOv10n.**
>
> **YOLOv8n ve YOLOv10n modelleriyle Baskılı Devre Kartlarında (PCB) derin öğrenme tabanlı hata tespiti.**

---

## 🌐 English

### 🔍 Project Overview

This project automates quality control in PCB manufacturing by detecting **6 distinct defect types** using state-of-the-art deep learning object detection. Both **YOLOv8n** and **YOLOv10n** models were trained and benchmarked on a specialized PCB defect dataset.

### 🎯 Key Objectives

| Goal | Description |
|------|-------------|
| 🤖 Automation | Replace manual inspection with AI-driven quality control |
| 🔬 Precision | Accurately classify and localize defects in PCB images |
| ⚡ Efficiency | Compare performance across two lightweight YOLO architectures |

### 📊 Dataset

- **Source:** [Kaggle — PCB Defects Dataset](https://www.kaggle.com/datasets/akhatova/pcb-defects)
- **Defect Classes (6):**

  | # | Defect Type |
  |---|-------------|
  | 1 | Missing Hole |
  | 2 | Mouse Bite |
  | 3 | Open Circuit |
  | 4 | Short |
  | 5 | Spur |
  | 6 | Spurious Copper |

### 📦 Project Files

> Download the full project (models, notebooks, and results):
>
> 🔗 [Google Drive — PCB Defect Detection Project](https://drive.google.com/file/d/1P_JwdkPnuqlascJxQBvSUd1xIRfQIf_h/view?usp=drive_link)

### 🖼️ Example Output

*Sample defect detection result on a PCB image:*

![PCB Defect Detection Screenshot](https://drive.google.com/uc?export=view&id=18olIMgqBGFysy_Fw25QFrytysOWaL-68)

---

## 🇹🇷 Türkçe

### 🔍 Proje Özeti

Bu proje, **Baskılı Devre Kartı (PCB)** üretiminde kalite kontrolünü otomatikleştirmeyi hedeflemektedir. **6 farklı hata türü**, derin öğrenme tabanlı nesne tanıma teknikleriyle tespit edilmektedir. **YOLOv8n** ve **YOLOv10n** modelleri özel bir veri seti üzerinde eğitilmiş ve karşılaştırmalı olarak değerlendirilmiştir.

### 🎯 Temel Hedefler

| Hedef | Açıklama |
|-------|----------|
| 🤖 Otomasyon | Manuel denetimi yapay zeka destekli kalite kontrolüyle değiştirmek |
| 🔬 Hassasiyet | PCB görüntülerindeki hataları doğru şekilde sınıflandırmak ve konumlandırmak |
| ⚡ Verimlilik | İki hafif YOLO mimarisinin performansını karşılaştırmak |

### 📊 Kullanılan Veri Seti

- **Kaynak:** [Kaggle — PCB Defects Dataset](https://www.kaggle.com/datasets/akhatova/pcb-defects)
- **Hata Sınıfları (6 adet):**

  | # | Hata Türü (TR) | Defect Name (EN) |
  |---|----------------|-----------------|
  | 1 | Eksik Delik | Missing Hole |
  | 2 | Fare Isırığı | Mouse Bite |
  | 3 | Açık Devre | Open Circuit |
  | 4 | Kısa Devre | Short |
  | 5 | Çıkıntı | Spur |
  | 6 | Yanlış Bakır İz | Spurious Copper |

### 📦 Proje Dosyası

> Projeyi indirmek için (modeller, notebook'lar ve sonuçlar dahil):
>
> 🔗 [Google Drive — PCB Hata Tespiti Projesi](https://drive.google.com/file/d/1P_JwdkPnuqlascJxQBvSUd1xIRfQIf_h/view?usp=drive_link)

### 🖼️ Örnek Çıktı

*Örnek bir PCB görüntüsü üzerinde hata tespiti sonucu:*

![PCB Hata Tespiti Görseli](https://drive.google.com/uc?export=view&id=18olIMgqBGFysy_Fw25QFrytysOWaL-68)
