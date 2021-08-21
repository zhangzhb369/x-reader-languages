# x-reader-languages
Txt,Pdf,Epub,Mobi,Azw book reader for iOS/iPad/Mac OS. 苹果多平台文档阅读器.多语言翻译工程. 
There may be some problems in the translation. So we need your help with the language translation. 
Thanks.
[x-reader.com](http://www.x-reader.com/)

Here is the multi-language translation project for X-Reader.

![Screenshot1](http://www.x-reader.com/images/mac_sreenshot.png)


## :closed_book: X-Reader Features:
- Good reading experience, custom fonts, themes, brightness, dark mode.
- Support txt, epub, pdf, mobi, azw, azw3 etc.
- Import & export local books.
- 4 turning animations: curl, horizontal, smooth scroll, none.
- iPad multi tasking.
- Mac multi windows.
- Keyboard shortcuts.
- Multi languages support.
   

## :green_book: Multi-languange localization:
### A language definition is a swift class. These class name conform to Lang_[language code]_[region code].
####  Below is the English localization:
```
class Lang_en_US: LangProtocol {
    var Alert_Title: String = "Warning"
    var Notice_Title: String = "Info"
    var Start_Title: String = "Start"
    var Confirm_Title: String = "Confirm"
    var Ok_Title: String = "Ok"
    var Cancel_Title: String = "Cancel"
    var Close_Title: String = "Close"
    var Save_Title: String = "Save"
    ...
}
```
#### And its corresponding Chinese localization class:
```
class Lang_zh_CN: LangProtocol {
    var Alert_Title: String = "警告"
    var Notice_Title: String = "提示"
    var Start_Title: String = "开始"
    var Confirm_Title: String = "确认"
    var Ok_Title: String = "确定"
    var Cancel_Title: String = "取消"
    var Close_Title: String = "关闭"
    var Save_Title: String = "保存"
    ...
}
```

#### Any problem please contace me: <zhangzhb369@gmail.com>
#### Many thanks for your help.
####
####

