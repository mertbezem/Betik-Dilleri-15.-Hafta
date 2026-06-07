import random
mahkumlar=[]
serbest_kalanlar=[]
infaz_edilen=""
for i in range(6):
    sec=input("okunan mahkum ismini yaz")
    mahkumlar.append(sec)
    print("secilen mahkum {} sahneye çıkartıldı.".format(sec))
print("ss subayı silahı cıkarıp rus ruleti icin hazır hale getirdi")
silah_patladi=0
sayac=1
r=random.randint(1,6)
while silah_patladi==False:
    # r=random.randint(1,6) eğer burada olursa her mahkum icin rus ruleti
    if r==sayac:
        print("booom .............. {}.mahkum öldü. diğerleri kurtuldu")
        silah_patladi=True
        print("olen= {}".format(mahkumlar[sayac-1]))
        
    else:
        print("Tık   {}. mahkum kurtuldu {}. sıradakine geçildi")
        print("kurtulan isim = {}".format(mahkumlar[sayac-1]))
        serbest_kalanlar.append(mahkumlar[sayac-1])
        sayac = sayac + 1
        #kurtulanlara 1. sahsin ismini ekle
