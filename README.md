

# 📝 **Free Fire Info API Documentation**

مرحبًا بك في وثائق **API معلومات Free Fire**! تتيح لك هذه الـ API استرجاع معلومات الحساب التفصيلية للاعبين في لعبة Free Fire، بما في ذلك إحصائيات المستخدم، معلومات الجناح، وغيرها من البيانات المفيدة.

## 🚀 **نقاط الوصول المتاحة**

### 1. **API معلومات الحساب**
**مسار الـ API:**  
```http
https://info-free-fire-killer-kelly-121-xwb7.onrender.com/info/id={uid}`
```
تسترجع هذه النقطة معلومات الحساب الأساسية بناءً على رقم تعريف المستخدم.

#### **مثال على الطلب:**
```http
GET https://info-free-fire-killer-kelly-121-xwb7.onrender.com/info/id=12345678
```
المعلمات المستخدمة:
ايدي لاعب فقط

---

2. API عبر الايدي  الإعجابات إرسال

مسار الـ API:
```http
https://likes-free-fire-kelly-121.onrender.com//@BL_RX/likes/id={uid}

```
تسترجع هذه النقطة إرسل الإعجابات إلى حساب المستخدم.

مثال على الطلب:

```http

GET https://likes-free-fire-kelly-121.onrender.com//@BL_RX/likes/id=2687804507

```
المعلمات المستخدمة:

ايدي لاعب فقط

---

💬 أمثلة على الاستجابة الناجحة

1. استجابة معلومات الحساب:
```json
{
  "ACCOUNT BASIC": {
    "Exp": 1949414,
    "Honor Score": 100,
    "Level": 66,
    "Likes": 3400318,
    "Name": "FB:\u3164@GMRemyX",
    "Region": "SG",
    "Signature": "FB & YT GM Remy | TikTok: gmremyx | IG GM Remy",
    "Title": 901045005,
    "UID": 12345678,
    "Update": "OB47"
  },
  "ACCOUNT OVERVIEW": {
    "Avatar ID": 902000154,
    "Banner ID": 901045005,
    "Equipped Gun ID": "leda",
    "Pet Exp": 6000,
    "Pet Level": 7,
    "Pin ID": 0
  },
  "ACCOUNT_F": {
    "BR Rank": "Heroic I (2142)",
    "CS Points": 25,
    "Created At": "2024-12-06 14:21:29",
    "Current BP Badges": 214,
    "Fire Pass": "Basic",
    "Last Login": "2017-12-06 21:19:29"
  },
  "GUILD INFO": {
    "Guild ID": 60893361,
    "Guild Level": 7,
    "Guild Name": "M\u1d1c\u1d0d\u1d0d\u028fyE\u1d20\u1d00T\u1d07\u1d00\u1d0d",
    "Leader Info": {
      "Leader BR Points": 214,
      "Leader CS Points": 55,
      "Leader Created At": "2024-12-05 02:02:44",
      "Leader Current BP Badges": 1300000071,
      "Leader Exp": 1949414,
      "Leader Last Login": "2024-12-08 02:02:44",
      "Leader Level": 66,
      "Leader Name": "FB:\u3164@GMRemyX",
      "Leader Title": "not found",
      "Leader UID": 12345678
    },
    "Live Members": 48
  }
}

```

2. استجابة ناجحة  الإعجابات:
```json
{
  "Ok": "Account will send 100 likes soon. Telegram Dev @SXmodG"
}

```


---

#😵 الأخطاء الشائعة وحلولها

###قد تُرجع الـ API استجابة خطأ في حال كانت البيانات المدخلة غير صحيحة. إليك بعض الأخطاء الشائعة وحلولها:

- ** الخطأ: 400

- **: المنطقة غير صحيحة.
- **: تأكد من أنك تستخدم رمز المنطقة الصحيح (مثل sg، me).

- ** الخطأ: 429

- **الرسالة: تم اكتشاف طلبات غير طبيعية. يرجى عدم إساءة استخدام الـ API أو قد يتم حظر عنوان الـ IP الخاص بك!
الحل: تجنب إرسال الكثير من الطلبات في فترة قصيرة. إذا استمر المشكلة، اتصل بمزود الـ API.

- ** الخطأ: 500

- **: حدث خطأ أثناء معالجة الطلب. يرجى التحقق من ID والمنطقة.
الحل: تحقق من ID المنطقة والمستخدم، وإذا استمرت المشكلة، تواصل مع مزود الـ API.


---

📚 هدف الـ API

#الهدف الأساسي من هذه الـ API المجانية هو تحسين تجربة مجتمع Free Fire. حيث أن شركة Garena لا توفر API رسمية للوصول إلى بيانات الحسابات، فإن هذه الـ API المخصصة تهدف إلى ملء هذا الفراغ وتقديم بيانات حسابات مفيدة للاعبين والمطورين.


---

**🧩 التقنيات المستخدمة**

- **>Flask: إطار عمل ويب صغير لبناء نقاط الـ API.

- **>Requests: لإرسال طلبات HTTP إلى الخوادم.



---

📅 صاحب الـ API

تم إنشاء هذه الـ API بواسطة  (كيلوا»» @SXmodG). جميع الحقوق محفوظة.

##انضم إلى مجموعتي على تليجرام  https://t.me/bot_pro_v3



#ملاحضه جلب معلومات وأرسل إعجبات يعمل فقط على لاعبين سيرفر مينا الشرق الاوسط إذا اردت صنع واحد خاص في بلدك تواصل معي على تليجرام ستكون الخدمه مجانيه بل كامل فقط ارسل لي حساب من بلدك حتى اقوم بنصع API  لك 

##تواصل >>>>>> Telegram @SXmodG 
