**purpose** 
- to have a notification alert within the status bar area

**vision**
- ![Status Bar Notifications](http://i.imgur.com/zS0qpyG.gif)

**methodology**
- all controllers must import CustomViewController (Views and TableViews)
- access the statusbar notification at anytime via 
```swift
StatusBarNotification.show(text: String)
```
```swift
StatusBarNotification.hide(text: String?)
```





