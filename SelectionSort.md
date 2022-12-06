# Proje 1
[22,27,16,2,18,6] -> ilk başta ilk sırada yer alacak en küçük sayıyı arar ve *2* yi bulup ilk index'e yerleştirir.
[2,27,16,22,18,6] -> 2. index'ten başlayarak 2. en küçüğü arar ve *27* ile *6* yı yer değiştirir.
[2,6,16,22,18,27] -> 3. index'ten başlayarak sonraki en küçüğü arar *16* en küçük olduğu için değişmeden devam eder.
[2,6,16,22,18,27] -> 4. index'ten başlayarak en küçüğü arar "18" en küçüktür *22* ve *18*'i değiştirir.
[2,6,16,18,22,27] -> 5. index en küçüktür değişmeden kalır ve tamamlanır.

## Big O gösterimi
Zaman karmaşıklığı *Average case*'e denk gelir


