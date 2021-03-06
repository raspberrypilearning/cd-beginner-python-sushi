## पूछते रहिये

आप उपयोगकर्ताओं से एक नंबर लेने के लिए कह सकते हैं, जांच लें कि क्या वह सही है और यदि नहीं है, तो उन्हें बताएं कि वो सही नहीं है। क्या होगा यदि आप अपने प्रोग्राम को तब तक चलने देना चाहते हैं जब तक आपको सही जवाब नहीं मिल जाता?

जब तक आपको सही तरह का जवाब नहीं मिल जाता, तब तक आपको अपना सवाल बार-बार पूछते रहने का तरीका चाहिए। कंप्यूटर प्रोग्रामिंग में इसे करने का तरीका **लूप (Loop)** कहा जाता है। आप `while` नामक लूप का उपयोग करने जा रहे हैं।

एक `while` लूप थोड़ा सा `if` स्टेटमेंट जैसा होता है: उस स्टेटमेंट के अंदर कोड तभी चलता है जब ब्रैकेट में दी गयी शर्त सच होती है। अंतर बस यह है कि एक `while` लूप चलता ही रहता है, जब तक कि ब्रैकेट में दी गयी शर्त झूठी न हो जाये। आपको यह ध्यान रखना होगा कि आपके पास हमेशा `while` लूप से बाहर आने का तरीका हो, अन्यथा यह हमेशा के लिए Run होता रहेगा! यह इस तरह दिखता है:

```python
while(my_number < 100):
    my_number = input("Hello "+name+" please pick a number that's bigger than 100")
    my_number = int(my_number)
```

--- task ---

अब अपने प्रोग्राम में `while` लूप जोड़े, जिससे की वह उपयोगकर्ताओं को एक संख्या के लिए पूछते रहे जब तक कि वे 100 से ज्यादा की संख्या नहीं देते।

```python
name = input("What is your name?")
my_number = 0

# तब तक लूप करे जब तक  "my_number" 100 से काम न हो 
while(my_number < 100):
    #  उपयोगकर्ता से संख्या पूछे 
    my_number = input("Hello "+name+" please pick a number that's bigger than 100")
    # उपयोगकर्ता द्वारा दिए गए उत्तर को स्ट्रिंग् से इन्टिजर में बदलें 
    my_number = int(my_number)
    print("Your number is "+str(my_number))
    # जांचे की संख्या 100 से बड़ी है क्या 
    if(my_number > 100):
        print("That's a big number!").
    elif(my_number > 90):
        print("Almost there! Try again!")
    else:
        print("That number is too small! Please try again!")
    # अगर my_number 100 से छोटा है, तो फिर से लूप करें
```

--- /task ---

--- collapse ---
---
title: वह अतिरिक्त टेक्स्ट क्या है - क्या वह कोड का हिस्सा है?
---

टेक्स्ट की लाइनें जो `#` चिन्ह से शुरू होती हैं वह **कमैंट्स (Comments)** हैं।

अधिकांश प्रोग्रामिंग भाषाओं में, आप अपने कोड में कमैंट्स लिख सकते हैं। यह ये बताने के लिए होते हैं कि कोड का क्या काम है, इन्हे कंप्यूटर अनदेखा कर देता है। आप उन्हें अपने लिए रिमाइंडर (reminder) के रूप में, या अन्य प्रोग्रामर के लिए लिख सकते हैं जो आपके कोड का उपयोग करना चाहते हैं। Python में, कमेंट्स `#` से शुरू होते हैं व पंक्ति के अंत में खत्म होते हैं।

--- /collapse ---
