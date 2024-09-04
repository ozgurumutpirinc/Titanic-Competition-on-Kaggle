Kaggle platformunda competitions kısmında düzenlenen Titanic veri seti üzerine yapılmış veri görselleştirme ve makine öğrenmesi modeli içeren programdır.

Veri görselleştirme aşamasında seaborn kütüphanesi ve verileri kriterlere göre gruplandırıp daha anlamlı grafikler çıkarma adına 'groupby' kullanılmıştır.

Veri setlerinde null veriler olduğu için bu veriler nümerikse medyan, kategorikse mod değerleriyle doldurulmuştur

Veri görselleştirmesi yapıldıktan sonra makine öğrenmesin kısmında kullanılmak üzere kategorik veriler 'Label Encoding' ile nümerik veriye dönüştürülmüştür. Model performansını etkilemeyecek bilet numarası ve yolcu ismi gibi veriler, veri setinden kaldırılmıştır.

Veri incelendikten sonra durumun bir sınıflandırma problemi olduğu anlaşılıp, gerekli modeller denenmiş ve en iyi performans gösteren ile yola devam edilmiştir.
