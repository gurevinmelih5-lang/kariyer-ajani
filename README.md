# Kariyer Ajanı

Her sabah web'i ve LinkedIn'i tarayıp proje yarışmalarını, hackathonları, staj ilanlarını ve diğer kariyer fırsatlarını toplayan, raporu Gmail'e gönderen bir Claude Code bulut rutini.

Rutin Anthropic'in bulutunda çalışır; bilgisayar kapalıyken de her gün **08:45'te (Europe/Istanbul)** başlar ve rapor 09:00 civarında gelir.

## Dosyalar

- `prompt.md`: Ajanın her çalışmada aldığı talimat (profil, kaynaklar, filtreler, e-posta formatı).
- `routine.json`: Rutin ayarları (zamanlama, model, bağlayıcılar, bildirimler). Talimat metni `prompt.md` içinde.

## Kaynaklar

- **Web:** WebSearch ve Exa ile Teknofest, TÜBİTAK, Coderspace, Devpost, Youthall, Kariyer.net, Anbean, Toptalent, Erasmus+ vb.
- **LinkedIn:** Exa üzerinden herkese açık gönderiler ve fırsat paylaşan şirket sayfaları; Gmail'e gelen LinkedIn iş alarmı mailleri.
- **Tekrar kontrolü:** Son 10 günün raporları Gmail'den okunur, aynı fırsat tekrar yazılmaz.

## Yönetim

- Rutin sayfası: https://claude.ai/code/routines/trig_01FGE6E95VgHjdEvZvUz948p
- Buradaki dosyalar rutinin bir kopyasıdır. Talimatı değiştirince rutini de güncellemek gerekir (Claude Code'da `RemoteTrigger update` ya da rutin sayfasından).
