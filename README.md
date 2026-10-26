# kod_asistanim
## projenin amacı:kullanıcılara günlük işlerinde  hesaplama yardımcı olacak bir dijital sistem tasarlamak
## projenin hedefleri:bir asistanın ilerleyen zamanlarda hangi özellikleri kazanacağını
giris kontrolu
BAŞLA

GirişPaneliAç()
BilgileriAl(k_adı, şifre)

EĞER VeritabanındaDoğrula(k_adı, şifre) İSE

EVET: AnaSayfayaYönlendir() -> HoşgeldinMesajıGöster()

HAYIR: HataMesajıGöster() -> GirişEkranınaDön()
BİTİR
