# PostgreSQL-study-case-and-exercises

# FLO CASE STUDY 
 -- Veri seti 
Flo’dan son alışverişlerini 2020 - 2021 yıllarında OmniChannel (hem online hem offline alışveriş yapan)
olarak yapan müşterilerin geçmiş alışveriş davranışlarından elde edilen bilgilerden oluşmaktadır.

--> 13 Değişken 19.945 Gözlem 2.7MB
--> master_id Eşsiz müşteri numarası
--> order_channel Alışveriş yapılan platforma ait hangi kanalın kullanıldığı (Android, ios, Desktop, Mobile)
--> last_order_channel En son alışverişin yapıldığı kanal
--> first_order_date Müşterinin yaptığı ilk alışveriş tarihi
--> last_order_date Müşterinin yaptığı son alışveriş tarihi
--> last_order_date_online Müşterinin online platformda yaptığı son alışveriş tarihi
--> last_order_date_offline Müşterinin offline platformda yaptığı son alışveriş tarihi
--> order_num_total_ever_online Müşterinin online platformda yaptığı toplam alışveriş sayısı
--> order_num_total_ever_offline Müşterinin offline'da yaptığı toplam alışveriş sayısı
--> customer_value_total_ever_offline Müşterinin offline alışverişlerinde ödediği toplam ücret
--> customer_value_total_ever_online Müşterinin online alışverişlerinde ödediği toplam ücret
--> interested_in_categories_12 Müşterinin son 12 ayda alışveriş yaptığı kategorilerin listesi
--> store_type 3 farklı companyi ifade eder. A company'sinden alışveriş yapan kişi B'dende yaptı ise A,B şeklinde yazılmıştır.


SORULAR
1. Customers isimli bir veritabanı ve verilen veri setindeki değişkenleri içerecek FLO isimli bir tablo oluşturunuz.
2. Kaç farklı müşterinin alışveriş yaptığını gösterecek sorguyu yazınız.
3. Toplam yapılan alışveriş sayısı ve ciroyu getirecek sorguyu yazınız.
4. Alışveriş başına ortalama ciroyu getirecek sorguyu yazınız.
5. En son alışveriş yapılan kanal (last_order_channel) üzerinden yapılan alışverişlerin toplam ciro ve alışveriş sayılarını
getirecek sorguyu yazınız.
6. Store type kırılımında elde edilen toplam ciroyu getiren sorguyu yazınız.
7. Yıl kırılımında alışveriş sayılarını getirecek sorguyu yazınız (Yıl olarak müşterinin ilk alışveriş tarihi (first_order_date) yılını
baz alınız)
8. En son alışveriş yapılan kanal kırılımında alışveriş başına ortalama ciroyu hesaplayacak sorguyu yazınız.
9. Son 12 ayda en çok ilgi gören kategoriyi getiren sorguyu yazınız.
10. En çok tercih edilen store_type bilgisini getiren sorguyu yazınız.
11. En son alışveriş yapılan kanal (last_order_channel) bazında, en çok ilgi gören kategoriyi ve bu kategoriden ne kadarlık
alışveriş yapıldığını getiren sorguyu yazınız.
12. En çok alışveriş yapan kişinin ID’ sini getiren sorguyu yazınız.
13. En çok alışveriş yapan kişinin alışveriş başına ortalama cirosunu ve alışveriş yapma gün ortalamasını (alışveriş sıklığını)
getiren sorguyu yazınız.
14. En çok alışveriş yapan (ciro bazında) ilk 100 kişinin alışveriş yapma gün ortalamasını (alışveriş sıklığını) getiren sorguyu
yazınız.
15. En son alışveriş yapılan kanal (last_order_channel) kırılımında en çok alışveriş yapan müşteriyi getiren sorguyu yazınız.
16. En son alışveriş yapan kişinin ID’ sini getiren sorguyu yazınız. (Max son tarihte birden fazla alışveriş yapan ID bulunmakta.
Bunları da getiriniz.)
