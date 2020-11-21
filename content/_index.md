+++
title = "React Native Quick Intro"
outputs = ["Reveal"]
+++

# A Quick Intro to React Native
# 🚀📱

Ben Murden

🐤@benmurden

---

## Who am I? 👨‍💻
- Developer at Sc0ville
- Also make Musicisum.com
- Living in Kyoto for 6 years
- From the UK

---

## React Native
React, but the markup is different

```jsx
return (
  <View>
    <Text>Hello Osaka</Text>
    <TouchableOpacity
      onPress={() => Alert.alert('Tapped!')}>
      Tap here!
    </TouchableOpacity>
  </View>
)
```

---

## Get started

### Expo.io
- 👍 Great way to start making something
- 👍 Simple to set up and see right on your device
- 👍 Can test on iOS without a Mac

--

- 👎 Only Javascript supported - no native modules

---

## Get started

### React Native CLI
- 👍 Flexible and well-supported
- 👍 Use native modules (Async storage, Keystore, etc.)

--

- 👎 Lots of setup

---

## Caveats

- Styles are different
- tailwind-rn can help here (https://github.com/vadimdemedes/tailwind-rn)
- Fast-moving project
- Docs are sometimes behind

---

## Should I Use It?

✔
- Coming from web dev
- Need to support both iOS and Android
- Views that consume an API

❌
- Already native dev
- Targeting only one platform
- Need complex native features

---

# Questions

---

## Reveal.js
## Hugo
## Github Pages