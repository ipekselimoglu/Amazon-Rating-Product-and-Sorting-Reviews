# MEASUREMENT PROBLEMS:

1- Rating Products:

   - Social Proof, The Wisdom Of Products !!
   
   - Ürün puanının hesaplanması, Ürünlerin sıralanması, Ürün yorumlarının sıralanması, olası ekran ve reaksiyon testleri önemli!
   
   - Time Based Weighted Average: Farklı zaman dilimlerinde gerçekleşen değerler ağırlıklandırılarak bir ortalama hesaplanır. 
     Bu yöntem, son dönemlerin verilerine daha fazla önem vererek geçmiş verilerden daha güncel verilerin daha etkili olmasını sağlar. 
     Bu sayede, ortalama hesaplanırken verilerin zaman içindeki değişimi dikkate alınmış olur.   
   
   - User Based Weighted Average: Kullanıcıların ağırlıklandırılarak bir ortalamanın hesaplanması yöntemidir. 
     Bu yöntemde, farklı kullanıcıların verdikleri değerler, kullanıcıların önemine veya belirli kriterlere göre ağırlıklandırılır. 
     Böylece, daha önemli veya güvenilir kullanıcıların verdikleri değerler ortalamada daha fazla etkili olur.      

2- Sorting Products: 

   - Sorting By Rating : ürünleri kullanıcıların verdikleri değerlere göre sıralama işlemidir ancak tek faktöre göre sıralama yanıltıcıdır.
   - Sorting By comment count or purchase count
   - Sorting By Rating + Comment count + purchase count: Daha optimizedir ancak öncesinde scale ve standardize edilmeli !
   - Bayesian avg. Rating Score: verilen puanların dağılımına bakılarak olasılıksal bir ortalama hesaplar, sadece puan dağılımına baktığı 
     için yanıltıcı olabilir. Ancak Potensiyeli Gözden kaçırmamayı sağlar, yeni ürünler de öne çıkabilir, ümit vaadedenleri ezmez.
   - Karma sıralama(wss+bar)


3- Sorting Reviews:

   - Up-Down Diff: score = up_rate - down_rate , oranı yakalayamıyor
   - Avg. rating: score = up_rate / all_rate, frekansı yakalayamıyor
   - Wilson lower bound score : güven aralığı hesaplayıp bu aralığı alt sınır kabul eder.Bu yöntem, hem olumlu değerlendirme oranını 
     hem de değerlendirme sayısını dikkate alarak, ürünlerin sıralanmasında daha dengeli bir yaklaşım sunar. 
     Bu yöntem, özellikle az sayıda değerlendirme alan ürünlerle, çok sayıda değerlendirme alan ürünleri daha adil bir şekilde karşılaştırmak için kullanılır!!
