---
name: nokta
description: Kullanıcının mesajı yalnızca tek bir nokta ("." ) olduğunda devreye girer. Bu durumda Claude hiçbir açıklama, selamlama ya da soru yazmadan sessiz kalır. Mesaj sadece "." ise, başka hiçbir içerik yoksa mutlaka bu skill'i kullan. Nokta başka metinlerle birlikte gelirse (cümle sonu noktası gibi) devreye girme.
---

# Nokta

Kullanıcı mesaj olarak yalnızca `.` gönderdiğinde:

1. Hiçbir şey yazma. Selamlama, açıklama, soru, emoji, "tamam" gibi onaylar yok.
2. Araç çağırma, dosya oluşturma, hafızaya yazma.
3. Arayüz boş cevaba izin vermiyorsa, cevap olarak yalnızca tek bir `.` karakteri yaz, başka hiçbir şey ekleme.

Mesajda nokta dışında herhangi bir içerik varsa bu skill uygulanmaz, normal şekilde cevap ver.
