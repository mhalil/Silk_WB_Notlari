# Silk_WB_Notlari
FreeCAD Eklentisi olan Silk Workbench Notlarının paylaşıldığı repo.
![silk](https://github.com/edwardvmills/Silk/raw/master/Resources/Demo_files/Silk_Demo_02.png?raw=true)

Silk workbench, FreeCAD'de NURBS yüzeyleri oluşturan bir Harici çalışma tezgahıdır.
Silk, NURBS Düşük derece ve dikiş sürekliliğine odaklanan yüzey modelleme araçlarıdır.

![silk_demo](https://github.com/edwardvmills/Silk/raw/master/Resources/Demo_files/Silk_Demo_03_01.png?raw=true)

NURBS: formu/şekli nispeten az sayıda "kontrol noktası" tarafından kontrol edilen, pürüzsüz eğriler ve yüzeylerdir. 
Adından da anlaşılacağı gibi, "kontrol noktaları", kullanıcının eğrileri veya yüzeyleri kontrol etmek için değiştirdiği şeylerdir. 
Bir NURBS'nin "iyileştirilmesi" derecesi tarafından kontrol edilir ve bir kontrol noktasının "etki mesafesi" NURBS'nin düğüm vektörü tarafından kontrol edilir.

**Düşük Derece (Low Degree)**: Silk NURBS eğrileri ve yüzeyleri, istenilen amaca uygun minimum derecededir. Düğüm vektörleri küçük bir tutarlı kümede tutulur. Genellikle NURBS modelleme problemlerinde görünen çözüm, düğümlerin derecesini ve sayısını artırmaktır. Bu tamamen geçerli olsa da, kontrol noktalarının hesaplama zorluklarını ve organizasyon zorluklarını artırıyor. Silk, çözülen her problem için mutlak minimum matematiksel karmaşıklığa sahip araçlar sağlamayı amaçlar.

**Dikiş Sürekliliği (Seam Continuity)**: Silk'in amacı, farklı NURBS bölümlerinden karmaşık modellerin oluşturulmasına olanak tanımak, alternatif olarak mevcut yüzeylere sürekli olacak yeni yüzeyler oluşturmak veya yüzeylerin başlangıçta süreksizliklerle oluşturulduğu yerlerde yumuşak geçişler oluşturmak için araçlar sağlamaktır.

Aşağıdaki animasyon, eğri ve yüzey sürekliliğinin tam mühendislik kontrolü ile eskizler aracılığıyla ince yüzey ayarını göstermektedir. Profil kontrol çiziminde kullanılan kontrol noktası sayısının az olduğuna dikkat edin. Belirli bir karmaşıklığa kadar Silk, eskiz düzenleme ile neredeyse gerçek zamanlı olarak güncellenir.

![anim](https://github.com/edwardvmills/Silk/raw/master/Resources/Demo_files/Steering_Wheel_01_01.gif?raw=true)

Kaynak:
https://github.com/edwardvmills/Silk
