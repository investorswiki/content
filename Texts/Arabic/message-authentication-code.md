---
keywords: Personal Finance,Banking
title: رمز مصادقة الرسالة (MAC)
description: رمز مصادقة الرسالة (MAC) ، أو العلامة ، هو رمز أمان يتم كتابته بواسطة مستخدم الكمبيوتر للوصول إلى الحسابات أو البوابات.
---

# رمز مصادقة الرسالة (MAC)
## ما هو رمز مصادقة الرسالة؟

رمز مصادقة الرسالة (MAC) ، أو ** العلامة ، ** هو رمز أمان يكتبه مستخدم الكمبيوتر للوصول إلى الحسابات أو البوابات. هذا الرمز مرفق بالرسالة أو الطلب المرسل من قبل المستخدم. يجب أن يتعرف نظام الاستقبال على رموز مصادقة الرسائل (MAC) المرفقة بالرسالة من أجل منح وصول المستخدم.

## فهم رمز مصادقة الرسائل (MAC)

تُستخدم أكواد مصادقة الرسائل (MAC) بشكل شائع في [عمليات تحويل الأموال الإلكترونية](/electronic-funds-transfer-act) (EFTs) للحفاظ على تكامل المعلومات. يؤكدون أن الرسالة حقيقية ؛ بمعنى آخر ، أنه يأتي حقًا ، بعبارة أخرى ، من المرسل المعلن ، ولم يطرأ عليه أي تغييرات في الطريق. يمكن للمدقق الذي يمتلك المفتاح أيضًا استخدامه لتحديد التغييرات التي تطرأ على محتوى الرسالة المعنية.

عادةً ما تكون رموز مصادقة الرسائل مطلوبة للوصول إلى أي نوع من الحسابات المالية. يمكن للبنوك وشركات الوساطة وشركات الائتمان وأي شركة إيداع أو استثمار أو تأمين أخرى توفر الوصول عبر الإنترنت استخدام هذه الرموز. إنها مكون حيوي للتشفير المالي.

## الخوارزميات المستخدمة لإنشاء أنظمة MAC

تشتمل ثلاث خوارزميات عادةً على MAC: خوارزمية توليد المفتاح وخوارزمية التوقيع وخوارزمية التحقق. تختار خوارزمية توليد المفاتيح مفتاحًا عشوائيًا. ترسل خوارزمية التوقيع علامة عند إعطاء المفتاح والرسالة. تُستخدم خوارزمية التحقق للتحقق من صحة الرسالة عند إعطاء المفتاح والعلامة ؛ ستعيد رسالة ** مقبولة ** إذا كانت الرسالة والعلامة أصليتين ولم يتم تعديلهما ، ولكن بخلاف ذلك ، ستعيد رسالة ** مرفوضة. **

على سبيل المثال ، يرسل المرسل رسالة ، مثل تحويل الأموال الإلكتروني ، من خلال خوارزمية MAC ، والتي تقوم بإنشاء مفتاح وإرفاق علامة بيانات MAC بالرسالة. يحصل المستلم على الرسالة ، ويعيد تشغيلها من خلال خوارزمية MAC بنفس المفتاح ، ويحصل على علامة بيانات ثانية. سيقومون بعد ذلك بمقارنة علامة بيانات MAC هذه بالعلامة الأولى المرفقة بالرسالة عند إرسالها. إذا كان الرمز هو نفسه في كلا الطرفين ، يمكن للمستلم أن يفترض بأمان أن سلامة بيانات الرسالة سليمة. إذا لم يكن الأمر كذلك ، فهذا يعني أنه تم تغيير الرسالة أو العبث بها أو تزويرها.

ومع ذلك ، يجب أن تحتوي الرسالة نفسها على بعض البيانات التي تضمن إرسال هذه الرسالة مرة واحدة فقط. على سبيل المثال ، يمكن استخدام MAC لمرة واحدة أو طابع زمني أو رقم تسلسلي لضمان إرسال الرسالة مرة واحدة فقط. خلاف ذلك ، قد يكون النظام عرضة لهجوم إعادة ، حيث يعترض المهاجم الرسالة بعد فك تشفيرها ويعيد إرسالها في وقت لاحق ، مما يؤدي إلى تكرار النتائج الأصلية والتسلل إلى النظام.

## رموز سلامة الرسالة (MICs)

في بعض الأحيان ، سيتم استخدام مصطلح رمز تكامل الرسالة (MIC) بدلاً من MAC. يتم ذلك غالبًا في صناعة الاتصالات ، حيث تعني MAC تقليديًا عنوان التحكم في الوصول إلى الوسائط (عنوان MAC). ومع ذلك ، يمكن أيضًا استخدام MIC للإشارة إلى ** ملخص الرسالة ، ** الذي لا يستخدم المفاتيح السرية بنفس طريقة MAC ، ولا يمكنه تقديم نفس مستوى الأمان دون مزيد من التشفير.

