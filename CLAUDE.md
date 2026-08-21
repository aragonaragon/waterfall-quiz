# اختبار الشلال — Waterfall Quiz

اختبار شخصية عربي (RTL) مستوحى من Dragon Quest III يحدد «أي مهنة JRPG تناسبك».

**اقرأ [HANDOFF.md](HANDOFF.md) أولاً** — فيه كل التفاصيل: صيغة الأسئلة، بنية المهن، مواصفات الرسومات، النشر، والأخطاء اللي تم حلها سابقاً (لا تكررها).

الأساسيات:
- كل الموقع في `index.html` واحد (HTML+CSS+JS). لا build، لا مكتبات.
- التشغيل محلياً: سيرفر `waterfall-quiz` في `.claude/launch.json` (بورت 8123). لا تفتح بـfile://.
- الأسئلة في `QUESTION_BANK` (30 سؤالاً، الجولة تسحب 10) والمهن في `CLASSES`. مفاتيح المهن: warrior, fighter, mage, priest, thief, merchant, jester (+hero نتيجة نادرة محسوبة، لا تُستخدم في الأسئلة).
- النشر: `netlify deploy --prod --dir .` (فريق nathoool92 → ikhtibar-al-shallal.netlify.app) و`git push` (GitHub Pages احتياطي).
- التواصل مع المستخدم بالعربية.
