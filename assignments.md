---
layout: page
title: Ödevler
permalink: /assignments
---

### 💡 Ödev 1 — Dinamik Programlama (DP) Konu Sunumları

Ödev **iki kişilik gruplar** hâlinde hazırlanacaktır. 36 öğrenci, toplam **18 grup** oluşturacaktır. Her grup aşağıdaki 18 konudan **birini** seçecek; her konu yalnızca bir grup tarafından alınacaktır.

Her grup seçtiği problem için:

1. Problemin tanımını, girdilerini, beklenen çıktısını ve amacını açıklayacak.
2. DP durumunun neyi temsil ettiğini, başlangıç koşullarını ve geçiş bağıntısını (recurrence relation) örnek üzerinden açıklayacak.
3. Çalışan kodunu **Java veya Python** ile yazacak; kodu, çalıştırma adımlarını ve örnek girdileri/çıktıları PDF raporuna ekleyecek.
4. Derste gösterildiği gibi **bir GIF animasyonu ve DP tablosu** hazırlayacak. GIF, küçük bir örnekte problemin nasıl çözüldüğünü adım adım gösterecek; tablo, aynı örnekte durumların hangi sırayla ve nasıl hesaplandığını açıklayacak. GIF, tablo ve kodun sonucu birbiriyle tutarlı olacak.
5. Zaman ve bellek karmaşıklığını, kullanılan değişkenlerin anlamını belirterek analiz edecek.
6. Çözümünü sınıfta sunacak ve PDF raporunda açıklayacak.

#### 🎓 Konu Listesi

1. Fibonacci Number
2. Factorial (Memoization)
3. Unbounded Knapsack
4. Coin Change — Hedef Tutarı Oluşturan Farklı Kombinasyonların Sayısı
5. Subset Sum
6. Partition Equal Subset Sum
7. Longest Common Subsequence (LCS)
8. Longest Common Substring
9. Edit Distance (Levenshtein)
10. Matrix Chain Multiplication
11. Longest Palindromic Subsequence
12. Minimum Palindrome Partitioning
13. Rod Cutting Problem
14. House Robber Problem
15. Climbing Stairs
16. Unique Paths (Robot Grid)
17. Longest Increasing Subsequence (LIS)
18. Optimal Binary Search Tree (OBST)

#### Coin Change konusunun kapsamı

Derste çözülen **minimum para sayısı** problemi, bir tutarı oluşturmak için en az kaç madeni para gerektiğini sorar. Bu ödevdeki **kombinasyon sayısı** problemi ise aynı tutarın kaç farklı para kombinasyonuyla oluşturulabileceğini sorar.

Örneğin para birimleri `[1, 3, 4]`, hedef tutar `6` olduğunda minimum para sayısı `2` olur (`3 + 3`). Kombinasyon sayısı ise `4` olur: `1+1+1+1+1+1`, `3+1+1+1`, `3+3` ve `4+1+1`.

Bu konuda her para biriminden **sınırsız sayıda** kullanılabilir ve **sıra önemli değildir**: `4+1+1` ile `1+4+1` aynı kombinasyondur. Çözüm, minimum para sayısını değil, bu kurallara göre **tüm farklı kombinasyonların sayısını** hesaplamalıdır. GIF ve DP tablosu da bu sayımın nasıl yapıldığını göstermelidir.

#### 📦 Teslim biçimi

Her grup teslimini **dersin Telegram grubundan** tek bir paylaşım olarak yapacaktır. Paylaşımda aşağıdakiler yer almalıdır:

- **Öğrenci bilgileri:** Grubun iki öğrencisinin adı, soyadı ve öğrenci numarası; seçilen ödev konusu.
- **GIF dosyası:** Derste gösterildiği gibi adım adım çözüm animasyonu.
- **PDF açıklama dosyası:** Problem tanımı, DP mantığı ve bağıntısı, örnek DP tablosu, Java veya Python kodu, çalıştırma adımları, örnek girdiler/çıktılar, zaman ve bellek analizi.

GIF ve PDF, Telegram paylaşımına dosya olarak eklenmelidir. İki öğrencinin adı, soyadı ve öğrenci numarası PDF raporunun ilk sayfasında da yer almalıdır.

#### GitHub üzerinden isteğe bağlı PR

İsteyen gruplar çalışmalarını **şimdiden Pull Request (PR)** açarak da paylaşabilir. Bu ödevde PR açmak **isteğe bağlıdır**; tüm gruplar GIF ve PDF dosyalarını **10 Kasım 2026 saat 23.59'a kadar (Bişkek saati) Telegram grubuna** göndermelidir. PR açılması, Telegram tesliminin yerine geçmez ve değerlendirme yüzdelerini değiştirmez.

PR açmak isteyen gruplar:

1. [Ders reposunu](https://github.com/kadirseker00/AlgApp-BIL377) fork eder.
2. Kod, GIF, PDF ve kısa bir README dosyasını yalnızca kendi `teslimler/odev1/grupXX/` klasörüne ekler (`XX`: grup numarası).
3. Ders reposunun `main` dalına, `Ödev 1 | Grup XX | Konu adı` başlığıyla grup başına tek PR açar. Diğer grupların dosyalarını ve ders materyallerini değiştirmez.

GitHub herkese açık olduğundan, PR açıklamasında ve repoya eklenen dosyalarda öğrenci numaraları yer almamalıdır. Öğrenci numaraları Telegram paylaşımında ve Telegram'a gönderilen PDF'de bulunmalıdır; GitHub'a eklenecek PDF'nin numaraları çıkarılmış bir kopyası kullanılmalıdır.

> 🔹 **Değerlendirme:**
>
> - DP mantığının doğru açıklanması (30%)
> - Kodun doğruluğu (30%)
> - Görselleştirme / tablo (20%): Derste gösterildiği gibi bir GIF animasyonu **ve** DP tablosu.
> - Rapor dili ve düzen (20%)

---

🗓️ **Son teslim:** 10 Kasım 2026, saat **23.59** (Bişkek saati).
