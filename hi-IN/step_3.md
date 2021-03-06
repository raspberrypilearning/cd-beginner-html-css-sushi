## आपका पहला वेबपेज!

- बायीं ओर के पैनल, जिसे **कोड पैनल** कहा जाता है, उस में `index.html` टैब पर क्लिक करें।

- `Welcome to Ireland!` पंक्ति को ढूंढें और इसे अपने संदेश में बदल दें - सावधान रहें पंक्ति की शुरुआत में `<p>` टैग और अंत में `</p>` टैग **नहीं हटाने** हैं। आपको अपना वेबपेज दाईं ओर के पैनल में अपडेट होता दिखना चाहिए।

![HTML अनुच्छेद उदाहरण](images/egFirstHtmlCode.png)

- अब उसी लाइन पर, `<p>` और `</p>` को `<h1>` और `</h1>` में बदलें । क्या आपको दाईं ओर के परिणाम में कोई परिवर्तन दिखाई दिया?

```html
  <h1>Welcome to Ireland!</h1>
```

--- collapse ---
---
title: HTML और टैग की व्याख्या
---

**HTML** वह कोड है जो वेबपेज बनाता है।

`.html` फ़ाइल नाम ब्राउज़र को बताता है कि फ़ाइल एक वेबपेज है, इसलिए ब्राउज़र को **टैग** देखने की जानकारी मिलती है और यह भी कि क्या प्रदर्शित करना है। (एक ब्राउज़र वह प्रोग्राम है जिसका उपयोग आप वेबसाइटों को देखने के लिए करते हैं, उदाहरण के लिए क्रोम या फ़ायरफ़ॉक्स।)

HTML टैग्स जैसे `<p>` और `</p>` पृष्ठ के विभिन्न टुकड़ों को परिभाषित करें, उदाहरण के लिए अनुच्छेद, शीर्षक या शरीर। इन टुकड़ों को **elements (तत्व)** कहा जाता है । उन्हें वेबसाइट के निर्माण की ईंटों के रूप में सोचें।

### मुझे दो टैग की आवश्यकता क्यों है?

आपको एक टैग **खोलने** और एक टैग **समापन** के लिए चाहिए ताकि ब्राउज़र को बता सके की तत्व कहाँ **शुरू** होते हैं और **अंत** । तो एक अनुच्छेद के लिए, शुरू का `<p>` टैग कहता है "यहां कुछ पाठ आता है जो मैं चाहता हूं कि आप एक अनुच्छेद के रूप में प्रदर्शित करें।" समापन `</p>` टैग उस ब्राउज़र को बताता है जहां पैराग्राफ समाप्त होता है।

`<body>` और `</body>` टैग के बीच सब कुछ आपका वेबपेज है।

- ध्यान दें कि कैसे बंद होने वाले टैग के आगे **हमेशा** एक स्लैश (slash) `/` होता है।

--- /collapse ---

- अपने शीर्षक में विभिन्न आकारों को देखने के लिए **शीर्षक** टैग में संख्याओं को बदलने का प्रयास करें। वे `<h1>` से `<h6>` तक जा सकते हैं। खुलने और बंद होने के टैग दोनों को बदलना याद रखें ताकि वे मेल खाते रहें।

- उस अनुच्छेद के कोड को खोजें जो कहता है `My website is about Ireland.` और इसे बदल दें ताकि यह इस तरह दिखे:

```html
  <p>
    <em>My website</em> is about <strong>Ireland</strong>. 
    It is going to have the following pages: Attractions, Music, Food
  </p>
```

क्या आप अनुमान लगा सक्ते हैं की `<em> </em>` और `<strong> </strong>` टैग क्या काम करते हैं?

![HTML टैग्स का उदाहरण](images/egFirstTags.png)

--- challenge ---

## चुनौती: अपने खुद के कुछ और पाठ जोड़ें

- आपके द्वारा सीखे गए कुछ टैगों का उपयोग करके अपने पृष्ठ में एक नया अनुच्छेद या शीर्षक जोड़ने का प्रयास करें।

--- hints ---


--- hint ---

जब आप किसी पृष्ठ पर पाठ डालना चाहते हैं, तो आपको इसे दो टैगों के बीच में रखना होगा जो आपके ब्राउज़र को आपके पाठ को प्रदर्शित करने का तरीका बताते हैं। उदाहरण के लिए, `<p> </p>` टैग ब्राउज़र को बताते हैं कि जो कुछ भी उनके बीच है वह पाठ का एक नया पैराग्राफ है, और `<h1> </h1>` टैग यह बताते हैं कि बीच में पाठ एक शीर्षक है।

--- /hint ---

--- hint ---

अनुच्छेद के लिए कोड इस तरह दिखता है:

```html
  <p>This is one paragraph of text.</p>

  <p>This is another paragraph.
  Everything in between one set of p tags is 
  displayed together in one long line on the webpage.</p>
```

--- /hint ---

--- hint ---

शीर्षकों के लिए कोड इस तरह दिखता है:

```html
  <h1>This is a heading.</h1>
```

शीर्षकों को आम तौर पर पैराग्राफ की तुलना में बड़ा या मोटा प्रदर्शित किया जाता है।

--- /hint ---

--- /hints ---

--- /challenge ---

बधाई हो, आपने अपना पहला वेबपेज बनाया है! अगले कार्ड पर, आपको यह पता लगाना होगा कि इसे कैसे नियंत्रित किया जाए।