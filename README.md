# 📊 FINANCIAL PERFORMANCE CLASSIFICATION

## 🧠 Proje Özeti | Project Overview

**TR:**  
Bu proje, şirketlere ait finansal veriler üzerinden makine öğrenimi modelleri kullanarak **finansal performans sınıflandırması** yapmayı amaçlamaktadır.  

**EN:**  
This project aims to classify **financial performance** of companies using machine learning models based on their financial indicators.

---

## 📁 Dosya Yapısı | File Structure

- `financial_data.csv` → Veri seti / Dataset (12.000 satır / rows, 55 özellik / features)  
- `data_creation.ipynb` → Veri oluşturma süreci / Data creation  
- `extracting_information.ipynb` → Veri analizi ve görselleştirme / Data analysis & visualization  
- `model_evaluation.ipynb` → Özellik mühendisliği ve model değerlendirme / Feature engineering & evaluation

---

## 📊 Veri Analizi | Data Analysis

**TR:**  
- Eksik değer kontrolü  
- Değişken dağılımları  
- Korelasyon analizi  
- Görselleştirme  

**EN:**  
- Missing value check  
- Feature distributions  
- Correlation matrix  
- Visualization  

---

## 🔧 Modelleme ve Değerlendirme | Modeling & Evaluation

**TR:**  
- Eğitim/Test ayrımı (Company_ID ile)  
- Finansal metriklerin dağılım grafikleri  
- Korelasyon matrisi  
- Yeni özellikler:  
  - EBITDA Margin  
  - ROA, ROE  
  - CashFlow/Debt, DSCR  
  - FCF, Inventory Turnover  
  - DSO, P/B Ratio  
- Sayısal değişkenlerin ölçeklenmesi  
- `train_set_processed.csv`, `test_set_processed.csv`

**EN:**  
- Train/Test split using Company_ID  
- Histograms of financial variables  
- Correlation heatmap  
- New engineered features:  
  - EBITDA Margin  
  - ROA, ROE  
  - CashFlow/Debt, DSCR  
  - FCF, Inventory Turnover  
  - DSO, P/B Ratio  
- Standard scaling  
- Final datasets: `train_set_processed.csv`, `test_set_processed.csv`

---

## ⚙️ Kullanılan Teknolojiler | Technologies Used

- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-Learn  
- Jupyter Notebook  

---

## 🚀 Nasıl Çalıştırılır? | How to Run

```bash
pip install -r requirements.txt
jupyter notebook
