# **تحليل التكدس المروري في طرق الحج باستخدام الذكاء الاصطناعي**  

## 📌 نظرة عامة  
يهدف هذا المشروع إلى **تحليل التكدس المروري وتحديد النقاط الخطرة** على الطرق المؤدية إلى **عرفة** باستخدام **الخرائط التفاعلية (Folium)** وتقنيات **الذكاء الاصطناعي**. يتيح هذا النظام تصور المناطق الحرجة التي قد تؤثر على سلامة الحجاج والمعتمرين، مما يساعد في اتخاذ قرارات أفضل لإدارة الحشود وتحسين تدفق الحركة.  

## 🚀 التقنيات المستخدمة  
- **Python** – لغة البرمجة الأساسية للمشروع  
- **Folium** – لإنشاء الخرائط التفاعلية  
- **Pandas & NumPy** – لمعالجة وتحليل البيانات  
- **Scikit-learn (Random Forest Classifier)** – لاكتشاف الحالات الخطرة والتكدس المروري  
- **TensorFlow/Keras (Deep Learning)** – لتحليل أنماط البيانات وتحسين دقة التنبؤ  
- **Synthetic Data Generation** – لإنشاء بيانات تحاكي الواقع بسبب نقص البيانات الحقيقية  

## 📊 كيفية عمل المشروع  
1. **جمع البيانات**: نظرًا لعدم توفر بيانات حقيقية كافية، تم إنشاء **بيانات اصطناعية** تحاكي التكدس المروري والحالات الخطرة.  
2. **تحليل البيانات**: تم استخدام **تحليل البيانات الاستكشافي (EDA)** لفهم الأنماط والعوامل المؤثرة في الازدحام.  
3. **تدريب النماذج**:  
   - تم استخدام **Random Forest Classifier** لاكتشاف الأنماط في البيانات والتنبؤ بالمواقع الخطرة.  
   - تم تدريب **نموذج تعلم عميق (Deep Learning)** باستخدام **شبكات عصبية متعددة الطبقات (MLP)** لزيادة دقة التنبؤ بالحالات الخطرة.  
4. **عرض النتائج**: تم استخدام **Folium** لإنشاء **خريطة تفاعلية** تعرض **المناطق الخطرة كنقاط حمراء** لمساعدة الجهات المعنية في تحسين إدارة الحشود.  

