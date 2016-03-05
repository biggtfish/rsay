This is a remake and fusion of code and ideas from rtranslate by Dingding Ye, rbabel by Sharon Rosner and google-translate-api by Dookie.

**Dookie** implemented a good  JSON parser for the googleapis translation service and put it in a ruby script. **Dingding Ye** and **Sharon Rosner** created gems that parse html result from google web interface,  causing google to block your script. RSay gem works without this limitation.

**same syntax of rtranslate:**

```
require "rsay"
result = Translate.t("Hello my Friend", Language::ENGLISH, Language::ITALIAN)

$rsay -f en -t it 'Hello my Friend!'
```