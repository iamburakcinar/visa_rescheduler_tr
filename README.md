# visa_rescheduler
US VISA (ais.usvisa-info.com) appointment re-scheduler - Turkiye adaptation

## Gereklilikler
- Mevcutta alınmış bir randevunuz olması gerekiyor.
- Google Chrome tarayıcıya sahip olmanız gerekiyor.
- Python v3 kurulu olmalı. https://www.python.org/downloads/ adresinden kurulum sağlayabilirsiniz.
- Pushover yada Sendgrid 'den alınmış entegrasyon bilgileri. ( Bilgilendirme gönderilmesini istiyorsanız)

## Kurulum
- `config.ini` dosyasındaki yapılandırma ayarlarını kendi randevu bilgileriniz ve konsolosluk bilgileriniz ile güncelleyin.
-  `pip3 install -r requirements.txt` komutunu çalıştırarak scriptin çalışması gerekli olan tüm bileşenleri kurulumunu tamamlayın.

## Çalıştırma
- Komut satırından  `python3 visa.py`  komutunu yazmanız yeterli.
- Script randevu sisteminde müsaitlik olduğunda sizin için bu aralığı seçip size bilgilendirme maili gönderecek.

## Teşekkür.
@yaojialyu bu uygulamayı yaptığın için teşekkürler.
