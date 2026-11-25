# مرآة الأشعة · X-Ray Mirror

صفحة ويب تفتح الكاميرا وترسم الجمجمة والدماغ وعضلات الوجه والعينين والأذن والجيوب الأنفية وفقرات العنق وعظام اليد وعضلاتها وأعصابها فوق رأسك ويدك الحقيقيين، وتتبعهما أثناء الحركة.

> نموذج تشريحي تعليمي، ليس أشعة حقيقية ولا فحصاً طبياً.

## التجربة

افتح الصفحة في Google Chrome، واضغط «ابدأ التجربة»، واسمح باستخدام الكاميرا.

- انقر على أي جزء، أو أشر إليه بإصبع السبابة نصف ثانية، ليظهر اسمه ومعلومة عنه.
- افتح فمك ليتحرك الفك السفلي.
- من لوحة التحكم: طبقات التشريح، وشكل الأشعة أو الألوان، وعدسة الأشعة، وتسجيل فيديو.
- «نماذج ثلاثية الأبعاد حقيقية»: أزرار لتحميل جمجمة ودماغ وعينين وفقرات حقيقية من BodyParts3D.

لا تُرسَل صورة الكاميرا إلى أي خادم؛ كل المعالجة تتم داخل المتصفح.

الصفحة بالعربية والإنجليزية: زر «English / العربية» في أعلى الصفحة، أو افتح الرابط مع `?lang=en`.

## English

A web page that opens your camera and draws the skull, brain, face muscles, eyes, ear, sinuses, neck vertebrae, and the hand bones, muscles and nerves over your real head and hands, following them as you move. Educational anatomical model, not a real X-ray or medical exam.

Open https://azizkhth.github.io/xray-mirror/?lang=en in Google Chrome, press Start and allow the camera. Click a part (or point at it with your index finger for half a second) to see its name and a fact. The camera image never leaves your browser.

## التقنية

- [MediaPipe Tasks Vision](https://developers.google.com/mediapipe) لتتبّع 478 نقطة في الوجه و21 نقطة في كل يد.
- [Three.js](https://threejs.org) لرسم الرأس ثلاثي الأبعاد.
- ملف HTML واحد، بلا خطوات بناء.

## حقوق البيانات

النماذج في مجلد `models/bodyparts3d`:

BodyParts3D, (c) The Database Center for Life Science licensed under CC Attribution-Share Alike 2.1 Japan
— https://dbarchive.biosciencedbc.jp/en/bodyparts3d/lic.html

إن أعدت نشر هذه الملفات أو عدّلتها فيجب ذكر المصدر بالسطر أعلاه ونشرها بالرخصة نفسها.
