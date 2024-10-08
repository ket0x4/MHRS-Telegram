# MHRS Randevu Bulucu

Hem ihtiyaca binaen hem de deneysel amaçlı yazılmış bir python projesidir. @enescaakir'ın C# olarak yazdığı [MHRS Otomatik Randevu](https://github.com/enescaakir/MHRS-OtomatikRandevu) projesinden esinlenilmiştir.

30 saniye arayla girilen kriterlere göre randevu arayacaktır. Randevu bulunduğunda bildirim verecektir. 

## Gereksinimler

- Python 3+
- Telegram bot tokeni (isteğe bağlı)
- Telegram chat id (isteğe bağlı)

## Kurulum
### Telegram bidirimleri (isteğe bağlı)
`.env` adında boş bir dosya oluşturup şunları ekleyin:
```shell
BOT_TOKEN = "Telegram bot tokeni"
CHAT_ID = "telegram chat id"
```
[Token almak için Tıkla](https://core.telegram.org/bots)

### Windows:
```powershell
python3 -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python3 mhrs.py
```

### Linux:
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python3 mhrs.py
```

![image](https://github.com/omergorur/mhrs-randevu-bulucu/assets/102440553/d6f0e6f4-927a-45b8-bea3-c26d01c1a0cb)
Örnek ekran görüntüsü: 14 saat sorgulamadan sonra ertesi güne bir randevu buldu.