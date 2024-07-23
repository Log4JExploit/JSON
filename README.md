# JSON
A free to use JSON Library for your Java application. Free as in liberty and free as in free beer.

# Features
- Parse JSON objects and arrays
- stringify JSON objects and arrays
- use custom get methods to skip casting
  e.g. getBoolean, getLong, ..
- works with unicode

# Getting Started
```
JSONObject object = new JSONObject();
object.put("key", true);

String text = object.toJSONString();
JSONObject parsed = JSON.byText(text);
```

# Honorable Mentions

[@nemethi](https://github.com/nemethi) inspired this project  
with their project [json-pretty-printer](https://github.com/nemethi/json-pretty-printer)
