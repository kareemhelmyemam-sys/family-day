خريطة اليوم v9 — PWA

1) index.html يعمل على الكمبيوتر والموبايل.
2) لتثبيته كتطبيق PWA حقيقي يجب فتح المجلد من موقع HTTPS (وليس file://).
3) بعد فتحه من HTTPS:
   Android Chrome/Edge: Install app أو Add to Home screen.
   iPhone Safari: Share > Add to Home Screen.
4) بعد أول فتح ناجح من HTTPS، Service Worker يخزن ملفات الواجهة للعمل Offline.
5) تنبيهات الجدول تعمل بأفضل صورة أثناء تشغيل التطبيق. PWA وحده لا يضمن منبهًا دقيقًا إذا أغلق النظام التطبيق بالكامل؛ ذلك يحتاج لاحقًا Native app أو push/server scheduling.
