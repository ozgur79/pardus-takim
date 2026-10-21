# Pardus Takım Sunumu — Claude

> Bu dosyayı **Claude Code** okur. Codex'in okuduğu eşi: `AGENTS.md`. İnsanlar için giriş: `README.md`.

---

## ORTAK GÖVDE — `AGENTS.md` ile birebir aynı olmak zorunda

**Sync kuralı:** Bu bölüm `CLAUDE.md` ile `AGENTS.md`'de karakter karakter aynıdır. Birini
değiştiren, aynı commit'te diğerini de değiştirir; yalnız en alttaki "ARACA ÖZGÜ" bölümü farklıdır.

Bu klasörün bir üstünde takımın çalışma reposu varsa (`../CLAUDE.md`, Codex için `../AGENTS.md`)
önce onu oku; yoksa bu satırı yok say.

### Bu repo ne
TEKNOFEST 2027 Pardus Hata Yakalama ve Öneri Yarışması'na hazırlanan takımın toplantı ve tanıtım
sunumu. Tek dosya: `index.html`. Sahneler `#1`, `#2` ... adresleriyle açılır, anlatıcı notları
`N` ile görünür. GitHub Pages ile yayınlanır (`main` dalı, kök dizin):
https://ozgur79.github.io/pardus-takim/

### Sert sınırlar
1. **Bu repo herkese açık.** İçindeki her şey internette okunur: anlatıcı notları, HTML
   yorumları, commit mesajları, bu dosya. Bulgu, "bakılacak yer", yüklenilecek uygulamanın adı,
   e-posta, kullanıcı adı ve takımın çalışma reposunun adresi buraya girmez. Neden: yarışmada
   önceden paylaşılan bulgu "önceden bildirilmiş" sayılır; yayımlanan kişisel bilgi geri alınamaz.
2. **Dış kaynak yok:** font, CDN, analitik, dışarıdan görsel kullanılmaz. Her şey `index.html`
   içinde, çizimler satır içi SVG. Neden: sayfa ziyaretçinin verisini üçüncü tarafa göndermez,
   çevrimdışı da açılır.
3. **Resmî sayfa izlenimi verilmez.** TEKNOFEST, TÜBİTAK ya da Pardus logosu kullanılmaz; alt
   şeritteki "resmî sayfası değildir" notu kalır.
4. **Her rakamın ve alıntının kaynağı** sahnenin HTML yorumunda ya da anlatıcı notunda yazılı
   kalır; kaynağı olmayan bilgi eklenmez, tarihli bilgi "... itibarıyla" diye yazılır.
5. **Yayın dışa dönüktür:** push etmeden önce değişikliği Özgür'e göster, onayını al. Force push
   yok.

### Bakım
- 2027 şartnamesi çıkınca sahne 04 (kurallar) ve 10 (takvim) güncellenir, kaynak notlarıyla
  birlikte.
- Takım adı seçilince üst şeritteki ad güncellenir (sahne 11'in notu).
- Sayfa telefonda da açılır: 760 px altında tek sütun. Değişiklikten sonra dar ekranda da bak.

---

## ARACA ÖZGÜ — Claude (bu bölüm `AGENTS.md`'dekinden farklıdır, bilinçli)

- Bu klasör kendi git deposudur; üstteki çalışma reposu onu `.gitignore` ile dışarıda tutar.
  git komutlarını bu klasörde çalıştır, bu dosyaları üst repoya commit'leme.
- Claude Code üst klasörün `CLAUDE.md`'sini de yükler. Oradaki bulgu akışı ve komutlar
  (`/bulgu`, `/durum` ...) bu repo için geçerli değildir; gizlilik kuralları geçerlidir.
