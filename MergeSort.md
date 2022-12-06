# Proje 2
-[16,21,11,8,12,22] ikiye bölünür -> [16,21,11],[8,12,22]
-[16,21,11];[8,12,22] kendi aralarında ikiye bölünür -> [16],[21,11];[8],[12,22]
-[16],[21,11];[8],[12,22] hala bölünecek varsa tekrar bölünür sonra sıralanmaya başlar.
-[16],[11,21];[8],[12,22] -> 2 li olanlar sıralandı şimdi tekrar aynı gruptakiler kendi aralarında sıralanacak 
-[11,16,21];[8,12,22] -> şimdi son grup sıralanacak ve işlemimiz bitmiş olacak.
-[8,11,12,16,21,22]

## Big O Gösterimi
'O(nlogn)'