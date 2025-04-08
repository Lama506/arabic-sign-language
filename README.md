#  تحويل التعليق الصوتي الرياضي إلى فيديو بلغة الإشارة العربية

مشروع ذكاء اصطناعي يهدف إلى دعم الأشخاص ذوي الإعاقة السمعية، من خلال تحويل التعليق الصوتي الرياضي إلى نص، ثم إلى فيديو بلغة الإشارة العربية باستخدام صور تمثل الأحرف.

##  فكرة المشروع
يقوم النظام بـ:
1. استخراج النص من فيديو يحتوي على **تعليق صوتي رياضي** باستخدام نموذج Whisper.
2. تنظيف النص وتطبيعه لتوحيد الحروف.
3. استخراج **الكلمات المفتاحية الرياضية** باستخدام نموذج Gemini من Google.
4. تحويل الكلمات إلى تسلسل صور يمثل **لغة الإشارة العربية**.
5. دمج الصور في فيديو يمثل المعنى.

##  الأدوات والتقنيات
- [Whisper](https://github.com/openai/whisper) من OpenAI: لتحويل الصوت إلى نص.
- [Google Generative AI (Gemini)](https://ai.google.dev/): لاستخراج الكلمات المفتاحية المهمة.
- [OpenCV](https://opencv.org/): لإنشاء الفيديو النهائي.
- [Pillow (PIL)](https://pillow.readthedocs.io/): لمعالجة الصور.
- Python + Google Colab.

