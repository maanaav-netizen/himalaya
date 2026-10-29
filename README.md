# हिमाल चिनौँ

फोनमा install गर्न मिल्ने offline-first web app (PWA)। Wikimedia Commons बाट peak का real photos र license/attribution ल्याउँछ; देखिएका card का फोटो बिस्तारै load हुन्छन्, र “सबै फोटो अफलाइन राख्नुहोस्” बटनले उपलब्ध photo library cache गर्छ। Machhapuchhre को कार्डमा छुट्टै पहिचान गरिएको Commons फोटो छ। पहिलोपटक त्यो फोटो खोल्न वा अफलाइन cache गर्न internet चाहिन्छ। हिमालको फोटो खिचेपछि GPS र फोनको compass बाट सम्भावित peak देखाउँछ। तपाईंले खिचेको photo device बाट बाहिर पठाइँदैन।

Catalog का कुनै peak card मा **“फोटो बदल्नुहोस्”** छानेर आफ्नो photo राख्न सकिन्छ। त्यो फोटो browser को IndexedDB मा सोही device मा सुरक्षित हुन्छ र पछि कार्डमा देखिन्छ। पहिचान नतिजामा upload गरेको photo ठूलो preview मा देखिन्छ; GPS/compass सुझावबाट peak छानेर त्यसको वास्तविक चुचुरोमा tap गर्दा नाम/उचाइको arrow बस्छ।

## चलाउने

फो र Android Chrome वा iPhone Safari बाट खोल्नुहोस्। **फोनमा Install** बटन वा browser menu प्रयोग गर्नुहोस्। iPhone मा Safari को Share → **Add to Home Screen** छान्नुहोस्। पहिलोपटक internet हुँदा app एकपटक खोल्नुहोस्; त्यसपछि app shell र catalog अफलाइन चल्छन्। फोटोहरू अफलाइन चाहिँदा **सबै फोटो अफलाइन राख्नुहोस्** थिच्नुहोस्। आफ्नै device मा बदलिएका फोटोहरू पनि त्यही device मा सुरक्षित हुन्छन्। Camera/GPS/compass अनुमति चाहिन्छ; GPS र compass मा internet नहुँदा पनि device को location/sensor उपलब्ध हुनुपर्छ। यो browser बाट install हुने PWA हो; यस workspace मा native APK बनाइएको छैन।

## Data र सीमा

Offline catalog मा Himalayan Database को June 2026 Peak List बाट ६,००० m वा माथिका 464 Himalayan Database entries छन्; Machhapuchhre (6,993 m) थपेर app मा जम्मा 465 peak देखिन्छन्। Peak IDs, elevation र Himal-region यही सूचीसँग मिलाइएका छन्। यसलाई नेपालका सबै topographic summits को पूर्ण गणना मान्नु हुँदैन; peak को परिभाषा र source अनुसार सूची फरक पर्न सक्छ, र सबै शिखरका लागि verified name/elevation/coordinate dataset उपलब्ध छैन।

यो computer-vision model होइन। GPS र कम्पासले coordinate भएका peak का सम्भावित नाम/दिशा छान्छ; त्यसपछि सही शिखरको टुप्पोमा tap गर्दा arrow त्यही स्थानमा बस्छ। फोटोका pixels बाट app ले आफैं हिमाल छुट्याउँदैन। HDB सूचीका धेरै entries सँग coordinates छैनन्। कमजोर GPS/compass वा लामो दूरीले सम्भावित peak सूची गलत बनाउन सक्छ। Wikimedia Commons का फोटो र लाइसेन्सको attribution app मा देखाइन्छ।

मुख्य data स्रोत: [Himalayan Database Peak List, June 2026](https://www.himalayandatabase.net/downloads/HD%20Peak%20List.pdf)। आधिकारिक पर्यटन संख्या/8,000 m+ सन्दर्भ: [नेपाल पर्यटन विभाग](https://tourismdepartment.gov.np/pages/mountains1/) र [नेपाल पर्यटन बोर्ड](https://ntb.gov.np/en/eight-thousanders)।

