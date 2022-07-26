---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: बॉक्स-जेनकिंस मॉडल
description: बॉक्स-जेनकिंस मॉडल एक गणितीय मॉडल है जिसे एक निर्दिष्ट समय श्रृंखला से डेटा की भविष्यवाणी करने के लिए डिज़ाइन किया गया है।
---

# बॉक्स-जेनकिंस मॉडल
## बॉक्स-जेनकिंस मॉडल क्या है?

बॉक्स-जेनकिंस मॉडल एक गणितीय मॉडल है जिसे एक निर्दिष्ट [समय श्रृंखला से इनपुट के आधार पर डेटा श्रेणियों का पूर्वानुमान लगाने के लिए डिज़ाइन किया गया है](/timeseries) । बॉक्स-जेनकिन्स मॉडल पूर्वानुमान उद्देश्यों के लिए कई अलग-अलग प्रकार के समय श्रृंखला डेटा का विश्लेषण कर सकता है।

इसकी कार्यप्रणाली परिणामों को निर्धारित करने के लिए डेटा बिंदुओं के बीच अंतर का उपयोग करती है। कार्यप्रणाली मॉडल को पूर्वानुमान उत्पन्न करने के लिए ऑटोरेग्रेशन, मूविंग एवरेज और मौसमी अंतर का उपयोग करके रुझानों की पहचान करने की अनुमति देती है।

[ऑटोरेग्रेसिव इंटीग्रेटेड मूविंग एवरेज (ARIMA) मॉडल](/autoregressive-integrated-moving-average-arima) बॉक्स-जेनकिंस मॉडल का एक रूप है। ARIMA और Box-Jenkins शब्द कभी-कभी एक दूसरे के लिए उपयोग किए जाते हैं।

## बॉक्स-जेनकिंस मॉडल को समझना

बॉक्स-जेनकिंस मॉडल का उपयोग विभिन्न प्रकार के अनुमानित डेटा बिंदुओं या डेटा श्रेणियों के [पूर्वानुमान के लिए किया जाता](/forecasting) है, जिसमें व्यावसायिक डेटा और भविष्य की सुरक्षा कीमतें शामिल हैं।

बॉक्स-जेनकिंस मॉडल दो गणितज्ञों द्वारा बनाया गया था: जॉर्ज बॉक्स और ग्विलीम जेनकिंस। दो गणितज्ञों ने 1970 के प्रकाशन में "टाइम सीरीज़ एनालिसिस: फोरकास्टिंग एंड कंट्रोल" नामक प्रकाशन में इस मॉडल को शामिल करने वाली अवधारणाओं पर चर्चा की।

बॉक्स-जेनकिंस मॉडल के मापदंडों का अनुमान बहुत जटिल हो सकता है। इसलिए, अन्य समय-श्रृंखला प्रतिगमन मॉडल के समान, सर्वोत्तम परिणाम आमतौर पर प्रोग्राम योग्य सॉफ़्टवेयर के उपयोग के माध्यम से प्राप्त किए जाएंगे। बॉक्स-जेनकिंस मॉडल भी आम तौर पर 18 महीने या उससे कम के अल्पकालिक पूर्वानुमान के लिए सबसे उपयुक्त है।

##बॉक्स-जेनकिंस पद्धति

बॉक्स-जेनकिंस मॉडल कई में से एक हो सकता है, समय श्रृंखला विश्लेषण मॉडल प्रोग्राम किए गए पूर्वानुमान सॉफ़्टवेयर का उपयोग करते समय एक फोरकास्टर का सामना करेगा। कई मामलों में, सॉफ़्टवेयर को पूर्वानुमानित किए जाने वाले [समय श्रृंखला](/timeseries) डेटा के आधार पर स्वचालित रूप से सर्वोत्तम फिटिंग पूर्वानुमान पद्धति का उपयोग करने के लिए प्रोग्राम किया जाएगा। बॉक्स-जेनकिंस को डेटा सेट के लिए एक शीर्ष विकल्प माना जाता है जो ज्यादातर स्थिर होते हैं और कम [अस्थिरता वाले होते हैं](/volatility) ।

बॉक्स-जेनकिंस मॉडल तीन सिद्धांतों का उपयोग करके डेटा का पूर्वानुमान लगाता है: ऑटोरेग्रेशन, डिफरेंसिंग और मूविंग एवरेज। इन तीन सिद्धांतों को क्रमशः p, d और q के रूप में जाना जाता है। बॉक्स-जेनकिंस विश्लेषण में प्रत्येक सिद्धांत का उपयोग किया जाता है; साथ में, उन्हें सामूहिक रूप से ARIMA (p, d, q) के रूप में दिखाया जाता है।

ऑटोरेग्रेशन (पी) प्रक्रिया इसकी स्थिरता के स्तर के लिए डेटा का परीक्षण करती है। यदि उपयोग किया जा रहा डेटा स्थिर है, तो यह पूर्वानुमान प्रक्रिया को सरल बना सकता है। यदि उपयोग किया जा रहा डेटा गैर-स्थिर है तो इसे अंतर करने की आवश्यकता होगी (डी)। डेटा को इसके मूविंग एवरेज फिट (जो विश्लेषण प्रक्रिया के भाग q में किया जाता है) के लिए भी परीक्षण किया जाता है। कुल मिलाकर, डेटा का प्रारंभिक विश्लेषण पैरामीटर (पी, डी, और क्यू) का निर्धारण करके पूर्वानुमान के लिए तैयार करता है, जिसे बाद में पूर्वानुमान विकसित करने के लिए लागू किया जाता है।

> एक बार का झटका भविष्य में बॉक्स-जेनकिंस मॉडल के बाद के मूल्यों को असीम रूप से प्रभावित करेगा। इसलिए, वित्तीय संकट की विरासत आज के ऑटोरेग्रेसिव मॉडल में रहती है।

>

## ऑटोरेग्रेसिव इंटीग्रेटेड मूविंग एवरेज (ARIMA)

बॉक्स-जेनकिंस एक प्रकार का ऑटोरेग्रेसिव इंटीग्रेटेड मूविंग एवरेज (ARIMA) मॉडल है जो अन्य बदलते चर के सापेक्ष एक आश्रित चर की ताकत का अनुमान लगाता है। मॉडल का लक्ष्य वास्तविक मूल्यों के बजाय श्रृंखला में मूल्यों के बीच अंतर की जांच करके भविष्य की प्रतिभूतियों या वित्तीय बाजार की चाल की भविष्यवाणी करना है।

एक ARIMA मॉडल को इसके प्रत्येक घटक को निम्नानुसार रेखांकित करके समझा जा सकता है:

- [ऑटोरेग्रेशन (एआर)](/autoregressive) : एक मॉडल को संदर्भित करता है जो एक बदलते चर को दिखाता है जो अपने स्वयं के अंतराल, या पूर्व, मूल्यों पर वापस आता है।

- एकीकृत (आई): समय श्रृंखला को स्थिर होने की अनुमति देने के लिए कच्चे अवलोकनों के अंतर का प्रतिनिधित्व करता है, यानी डेटा मानों को डेटा मानों और पिछले मानों के बीच अंतर से बदल दिया जाता है।

- [मूविंग एवरेज (एमए)](/movingaverage) : एक अवलोकन और एक चलती औसत मॉडल से अवशिष्ट त्रुटि के बीच निर्भरता को शामिल करता है जो लैग्ड अवलोकनों पर लागू होता है।

## स्टॉक की कीमतों का पूर्वानुमान

बॉक्स-जेनकिंस मॉडल विश्लेषण के लिए एक प्रयोग [स्टॉक](/stock) की कीमतों का पूर्वानुमान करना है। यह विश्लेषण आम तौर पर आर सॉफ्टवेयर के माध्यम से बनाया और कोडित किया जाता है। एक लॉगरिदमिक परिणाम में परिणाम विश्लेषण, जिसे भविष्य में एक निर्दिष्ट अवधि के लिए अनुमानित मूल्य उत्पन्न करने के लिए डेटा सेट पर लागू किया जा सकता है।

एआरआईएमए मॉडल इस धारणा पर आधारित हैं कि पिछले मूल्यों का वर्तमान या भविष्य के मूल्यों पर कुछ अवशिष्ट प्रभाव पड़ता है। उदाहरण के लिए, स्टॉक की कीमतों की भविष्यवाणी करने के लिए एआरआईएमए मॉडल का उपयोग करने वाला एक निवेशक यह मान लेगा कि उस स्टॉक के नए खरीदार और विक्रेता हाल के बाजार लेनदेन से प्रभावित होते हैं, जब यह तय करते हैं कि सुरक्षा के लिए कितना प्रस्ताव देना या स्वीकार करना है।

हालांकि यह धारणा कई अलग-अलग परिस्थितियों में मान्य होगी, यह हमेशा सच नहीं होता है। उदाहरण के लिए, 2008 के वित्तीय संकट से पहले के वर्षों में, अधिकांश निवेशक कई वित्तीय फर्मों द्वारा रखे गए [बंधक-समर्थित प्रतिभूतियों (एमबीएस) के बड़े पोर्टफोलियो द्वारा उत्पन्न जोखिमों से अवगत नहीं थे।](/mbs)

उस समय के दौरान, अमेरिकी वित्तीय शेयरों के प्रदर्शन की भविष्यवाणी करने के लिए एक ऑटोरेग्रेसिव मॉडल का उपयोग करने वाले निवेशक के पास उस क्षेत्र में स्थिर या बढ़ती स्टॉक कीमतों की चल रही प्रवृत्ति की भविष्यवाणी करने का अच्छा कारण होगा। हालांकि, एक बार जब यह सार्वजनिक हो गया कि कई वित्तीय संस्थान आसन्न पतन के जोखिम में थे, तो निवेशक अचानक इन शेयरों की हाल की कीमतों से कम चिंतित हो गए और उनके अंतर्निहित जोखिम जोखिम से कहीं अधिक चिंतित हो गए।

इसलिए, बाजार तेजी से वित्तीय शेयरों को बहुत निचले स्तर पर पुनर्मूल्यांकन कर रहा है, एक ऐसा कदम जिसने एक ऑटोरेग्रेसिव मॉडल को पूरी तरह से भ्रमित कर दिया होगा।

##हाइलाइट

- ऑटोरेग्रेसिव इंटीग्रेटेड मूविंग एवरेज (ARIMA) मॉडल बॉक्स-जेनकिंस मॉडल का एक रूप है।

- बॉक्स-जेनकिंस मॉडल 18 महीने या उससे कम समय के भीतर पूर्वानुमान लगाने के लिए सबसे उपयुक्त है।

- कार्यप्रणाली इस धारणा पर आधारित है कि पिछली घटनाएं भविष्य को प्रभावित करती हैं।

- बॉक्स-जेनकिंस मॉडल समय श्रृंखला डेटा पर प्रतिगमन अध्ययन का उपयोग करते हुए एक पूर्वानुमान पद्धति है।

