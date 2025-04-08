# 🧠 Arabic Sign Language Video Generator

مشروع يستخدم تقنيات الذكاء الاصطناعي لتحويل الصوت العربي إلى نص، ثم إلى فيديو بلغة الإشارة العربية.

## 🔧 فكرة المشروع
يقوم النظام بـ:
1. استخراج النص من فيديو صوتي باستخدام نموذج Whisper.
2. تنظيف وتطبيع النص.
3. استخدام نموذج Gemini من Google لاستخراج الكلمات المفتاحية.
4. تحويل الكلمات إلى صور أحرف من لغة الإشارة العربية.
5. دمج الصور في فيديو يمثل الكلمات بلغة الإشارة.

## 🛠️ الأدوات المستخدمة
- [Whisper](https://github.com/openai/whisper) من OpenAI للتعرف على الصوت.
- [Google Generative AI (Gemini)](https://ai.google.dev/) لاستخراج الكلمات المفتاحية.
- [OpenCV](https://opencv.org/) لإنشاء الفيديو.
- [Python PIL](https://pillow.readthedocs.io/) لمعالجة الصور.
- Google Colab لتشغيل المشروع.
