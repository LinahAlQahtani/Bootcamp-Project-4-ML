# السيارات المستخدمة في السعودية 🚗 🇸🇦

## المقدمة والأهداف 💬

تم العمل في هذا المشروع على مجموعة بيانات للسيارات المستعملة في السعودية.
يهدف هذا المشروع إلى استخدام خوارزميات التعلم الآلي
(machine learning algorithms) 
لغرض التنبؤ. 
استخدمنا خوارزميات الانحدار(regression algorithms), للتنبؤ بسعر السيارات المستخدمة في السعودية. 



## نظرة عامة عن البيانات و مصدرها 📍

 [Kaggle](https://www.kaggle.com/datasets/turkibintalib/saudi-arabia-used-cars-dataset) مصدر البيانات
 
تحتوي مجموعة البيانات على 8248 سجلاً للسيارات المستعملة تم جمعها من موقع syarah.com. 
يمثل كل صف سيارة مستعملة مع المعلومات الأخرى المتعلقة بكل سيارة هي اسم العلامة التجارية، الموديل، سنة الصنع، الأصل، لون السيارة، الخيارات، سعة المحرك، نوع الوقود، نوع ناقل الحركة، المسافة المقطوعة التي قطعتها السيارة، سعر المنطقة، وقابل للتفاوض


## أعضاء الفريق 👥
1. عبدالرحمن البقمي: EDA , Visualization , ML
2. محمد الحربي: ML , Dashboard
3. لينه القحطاني: ML , Markdown

| الأسم               | المهام | 
                                                                                                                                |-----------------------|----------|
|  عبدالرحمن البقمي  | EDA , Visualization , ML   |
| محمد الحربي|  ML , Dashboard    | 
| لينه القحطاني | ML , Markdown   |


## تجهيز البيانات وتنظيفها 🧹
  ثم تجهيز البيانات و تنظيفها:,Pandas تم رفع و استعراض مجموعة البيانات باستخدام مكتبة

- Shape: استخدام df.shape لفهم عدد الصفوف والأعمدة.
- Info: معلومات عن الأعمدة و نوع البيانات وعدد القيم غير الفارغة باستخدام df.info().
- Describe: إحصائيات موجزة للأعمدة الرقمية في مجموعة البيانات. باستخدام df.describe()
- تم حذف الاعمدة غير المهمه بفكرة المشروع.
- Missing Values: قمنا بفحص وجود قيم مفقودة في مجموعة البيانات باستخدام الدالة isnull() وجمع القيم الخالية.
- fillna: تم التعامل مع القيم الخاليه باستخدام fillna()




## الخوارزميات المختارة 📋
1. LinearRegression
2. ExtraTreesRegressor
3. GradientBoostingRegressor


## نتائج نماذج ML 📋

يلخص الجدول أدناه النتائج النهائية لنماذج التعلم الآلي التي تم تقييمها في هذا المشروع:

| ML Model                 | R-squared| 
|-----------------------|----------|
| LinearRegression  | 0.67   |
| GradientBoostingRegressor| 0.84    | 
| ExtraTreesRegressor | 0.83   | 

## الاستنتاج والنتائج النهائية 📋
قام مشروعنا بتحليل قاعدة بيانات للسيارات المستعملة في السعودية وتم استخدام خوارزميات التعلم الآلي (machine learning algorithms) لغرض التنبؤ بسعر السيارات المستخدمة في السعودية.
وتم استخدام نماذج الانحدار التالية: LinearRegression , GradientBoostingRegressor , ExtraTreesRegressor.
كانت GradientBoostingRegressor هي الأعلى من ناحية الأداء بمقدار 0.84 
 
