## एक से अधिक स्ट्रिंग (string) की जांच करें

क्या होगा यदि आप जांचना चाहते हैं कि उपयोगकर्ता की संख्या पर्याप्त रूप से बड़ी है या नहीं, और फिर उन्हें बताएं अगर नहीं है तो?

आप `and` और `or` का उपयोग करके ब्रैकेट में लिखी जाने वाली शर्तों को जोड़ सकते हैं । तो आप इस तरह कोड लिख सकते हैं:

```python
if(my_number >= 20 and my_number < 30):
    print("That number is in the twenties!")
```

या, उदाहरण के लिए:

```python
if(food == "Cake" or food == "Chocolate" or food == "Pie"):
    print("Sounds tasty!")
```

--- task ---

जांचें कि उपयोगकर्ता की संख्या 100 से अधिक है या नहीं। फिर, या तो उपयोगकर्ता को सही नंबर देने के लिए बधाई दें जो कि काफी बड़ा है, या उन्हें बताएं कि उन्होंने नंबर को सही नहीं चुना यानी की बड़ा नहीं चुना है।

इसे इस्तेमाल करके देखें:

```python
name = input("What is your name?")
my_number = input("Hello "+name+" please pick a number that's bigger than 100")
my_number = int(my_number)
print("Your number is "+str(my_number))

if(my_number > 100):
    print("That's a big number!")
else:
    print("That number is too small!")
```

--- /task ---

`else` स्टेटमेंट के अंदर का कोड तब चलता है जब `if` स्टेटमंट के ब्रैकेट के अंदर की शर्त जब सच _नहीं_ होती।

### और शर्तें

क्या होगा यदि आप उपयोगकर्ता को संख्या के आसपास होने पर बताना चाहते हैं, उदाहरण के लिए यदि उन्होंने `90` से अधिक नंबर लिया है?

तब आप एक `elif` का उपयोग कर सकते हैं! यह शब्द else और if को साथ जोड़ने से बनता है। `elif` स्टेटमेंट के अंदर का कोड केवल तभी चलता है जब `if` स्टेटमेंट के अंदर की शर्त सच _नहीं हो_ **और ** `elif` स्टेटमेंट के ब्रैकेट की शर्त सच _हो_।

यहाँ पे है वो कोड जो आपको प्रोग्राम में जोड़ेंगे तो वह उपयोगी को यह बता सके की वो उस संख्या के आसपास हैं:

```python
elif(my_number > 90):
    print("Almost there!"
```

--- task ---

अब उन पँक्तियों को अपने बाकी प्रोग्राम में जोड़ें। ध्यान दें कि `elif` स्टेटमेंट को `if` और `else` स्टेटमेंट के बीच में आना होता है।

```python
name = input("What is your name?")
my_number = input("Hello "+name+" please pick a number that's bigger than 100")
my_number = int(my_number)
print("Your number is "+str(my_number))

if(my_number > 100):
    print("That's a big number!")
elif(my_number > 90):
    print("Almost there!")
else:
    print("That number is too small!")
```

--- /task ---
