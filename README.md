# Polinomal Regresyon ile Hisse Fiyat Tahmini

Bu proje, Amazon'un hisse fiyatlarını polinomal regresyon modeli kullanarak tahmin eder. Tarihsel hisse fiyatlarını çeker, kapanış fiyatlarına dayalı bir regresyon modeli eğitir ve gelecekteki fiyatları tahmin eder.

[**Read this document in English**](./README.md)

## Özellikler

- **Veri Çekme**: `yfinance` kullanarak Amazon'un tarihsel hisse fiyatı verilerini çeker.
- **Polinomal Regresyon Modeli**: Gelecekteki fiyatları tahmin etmek için kapanış fiyatlarına dayalı bir regresyon modeli eğitir.
- **Veri Görselleştirme**: Tarihsel hisse verilerini ve tahmin sonuçlarını kolay yorumlanabilir şekilde grafiklerle sunar.

## Gereksinimler

- Python 3.8 veya üzeri
- Gerekli Python paketleri:
    - `yfinance`
    - `pandas`
    - `numpy`
    - `matplotlib`
    - `scikit-learn`

## Kurulum

1. Bu projeyi yerel makinenize klonlayın:
    ```bash
    git clone https://github.com/Furkan-Demircan/amazon-stock-prediction.git
    cd amazon-stock-prediction
    ```

2. Gerekli Python paketlerini yükleyin:
    ```bash
    pip install -r requirements.txt
    ```

3. Jupyter Notebook'u başlatın:
    ```bash
    jupyter notebook
    ```

4. `Stock-Predict-Plynomal-Regression.ipynb` dosyasını açın ve hücreleri adım adım çalıştırın.

## Kullanım

1. Notebook, `yfinance` kütüphanesini kullanarak Amazon'un tarihsel hisse fiyatlarını çeker.
2. Kapanış fiyatlarına dayalı bir polinomal regresyon modeli eğitilir.
3. Tarihsel fiyatlar ve tahminler görselleştirilir.
4. Eğitilen modele dayalı olarak gelecekteki tarihler için tahminler görüntülenir.

## Katkıda Bulunma

Katkılar memnuniyetle karşılanır! Lütfen katkıda bulunmadan önce bir konu açarak değişikliklerinizi tartışın.

1. Fork'layın (Çatal oluşturun).
2. Kendi dalınızı oluşturun (`git checkout -b ozellik/yeni-ozellik`).
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik ekle'`).
4. Dalınıza push yapın (`git push origin ozellik/yeni-ozellik`).
5. Bir pull isteği (PR) açın.

## Lisans

Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için [LICENSE](./LICENSE) dosyasına bakabilirsiniz.

## İletişim

Bu proje hakkında sorularınız veya önerileriniz için bizimle iletişime geçebilirsiniz:

- **E-posta**: goooglenudle@gmail.com
- **GitHub**: [Furkan-Demircan](https://github.com/Furkan-Demircan)

---

İyi kodlamalar!!!
