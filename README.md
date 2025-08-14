# FGSM ile Yapay Zekayı Kandırmak: Adversarial Saldırı Uygulaması

Bu proje, yapay zeka sistemlerinin zayıf noktalarını keşfetmek ve savunma stratejileri geliştirmek amacıyla geliştirilmiştir. Derin öğrenme modellerinin ne kadar güçlü görünse de küçük manipülasyonlarla nasıl yanıltılabileceğini göstermek temel hedeftir.

## Proje Hakkında

Bu çalışmada, **MNIST** veri seti kullanılarak bir **CNN (Convolutional Neural Network)** modeli eğitilmiş ve ardından bu modele **FGSM (Fast Gradient Sign Method)** adlı adversarial saldırı uygulanmıştır.

### Uygulanan Adımlar:

1. **Model Eğitimi:**  
   - MNIST veri seti üzerinde bir CNN modeli eğitildi.  
   - Model, yüksek doğruluk oranı (%97+) elde edecek şekilde optimize edildi.

2. **FGSM Saldırısı:**  
   - Eğitilen model üzerinde FGSM yöntemiyle adversarial örnekler (bozulmuş görüntüler) oluşturuldu.  
   - Modelin bu örneklerde nasıl hata yaptığı gözlemlendi.  
   - Orijinal ve bozulmuş görüntüler karşılaştırmalı olarak analiz edildi.

3. **Adversarial Training (İsteğe Bağlı):**  
   - Model, hem orijinal hem de bozulmuş verilerle yeniden eğitilerek saldırılara karşı daha dayanıklı hale getirildi.

## Daha Fazlası İçin


🔗 **Makale:**  
👉 [https://medium.com/@deniz0](https://medium.com/@deniz0)






---
