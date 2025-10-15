BAŞLA

1. "Kartınızı takınız." mesajını göster
2. Kullanıcının kart takmasını bekle

3. "PIN kodunuzu giriniz." mesajını göster
4. Kullanıcıdan PIN kodunu al

5. PIN doğru mu?
    EĞER EVET ise
        DEVAM ET
    DEĞİLSE
        PIN deneme hakkını 1 azalt
        3 deneme hakkı bitti mi?
            EĞER EVET ise
                "Kart bloke edildi." mesajı göster
                Kartı yut
                DUR
            DEĞİLSE
                4. adıma geri dön

6. "Lütfen işlem seçiniz." menüsünü göster: [Para Çekme, Bakiye Sorgulama, İptal]
7. Kullanıcının seçimini al

8. Seçim == "Para Çekme" ise
    9. "Çekmek istediğiniz tutarı giriniz:" mesajını göster
    10. Tutarı al

    11. Tutar geçerli mi? (0'dan büyük ve belirli bir kat mı?)
        DEĞİLSE
            "Geçersiz tutar." mesajını göster
            9. adıma geri dön

    12. Kullanıcının bakiyesi yeterli mi?
        DEĞİLSE
            "Yetersiz bakiye." mesajını göster
            6. adıma geri dön

    13. ATM'de yeterli nakit var mı?
        DEĞİLSE
            "ATM'de yeterli nakit yok." mesajını göster
            6. adıma geri dön

    14. Tutarı kullanıcıya ver
    15. İşlemi bankaya bildir ve bakiyeyi güncelle

    16. "İşleminiz başarıyla tamamlandı." mesajını göster

17. Kartı iade et
18. "Kartınızı almayı unutmayınız." mesajını göster

DUR
