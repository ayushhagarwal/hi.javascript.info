importance: 4

---

# बड़े अक्षर का उपयोग const के लिये?

निम्नलिखित कोड की जाँच करें:

```js
const birthday = '18.04.1982';

const age = someCode(birthday);
```

यहां हमारे पास एक निरंतर `birthday` तिथि है और `age` की गणना `birthday` से कुछ कोड की सहायता से की जाती है (यह संक्षिप्तता के लिए प्रदान नहीं की जाती है, और क्योंकि विवरण से यहां कोई फर्क नहीं पड़ता)।

क्या `birthday` के लिए बड़ा अक्षर का उपयोग करना सही होगा? `age` के लिए? या दोनों के लिए भी?

```js
const BIRTHDAY = '18.04.1982'; // बड़ा अक्षर बनाएं?

const AGE = someCode(BIRTHDAY); // बड़ा अक्षर बनाएं?
```

