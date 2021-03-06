### Getting Confident

Once you've got a feel for the language, and some of the patterns here's some advice to start speeding you up in getting around the systems.


Use Reveal
----------------
[Reveal](http://revealapp.com) is a tool for inspecting the view hierarchy. Folio is _featured_ on their website as an example of how pretty it looks. You should have Reveal installed, and when our app is loaded you select the simulator type in the top left of Reveal. See this [gist](https://gist.github.com/raven/8553761) for getting started, or be lazy: quit Xcode and run:

```
mkdir -p ~/Library/Developer/Xcode/UserData/xcdebugger && curl https://gist.githubusercontent.com/raven/8553761/raw/Breakpoints_v2.xcbkptlist -o ~/Library/Developer/Xcode/UserData/xcdebugger/Breakpoints_v2.xcbkptlist
```

Use AppCode
---------------
AppCode is Xcode but with a lot of extra goodies because they don't have to say no to everything. It's a Java app and I understand when you wince but I can promise you that a lot of smart people _deal with it_. You should too.

My install settings are open source at [orta/AppCode](https://github.com/orta/AppCode). They are a mix of TextMate + Xcode. Also check out the [QuickStart Guide](http://www.jetbrains.com/objc/quickstart/).

Use Dash
---------------
Documentation is essential. Having quick access is even more useful. With Dash I partially type the class then guess the method name after pressing space. [Dash](http://kapeli.com) makes this very very fast.

If you insist on using Xcode
---------------
I understand, it's worth the switch. Anyway.

* Use Xcode Plugins. The Git & FuzzyAutoComplete ones especially. Get [Alcatraz](https://github.com/mneorr/Alcatraz/) for this.
* Make "Open Quickly" `cmd + t` in Xcode to quickly open files like TextMate
* Make "Standard Editor > Show Document Items" `cmd + shift + t` in Xcode to make it quickly jump to methods in the file like TextMate
* `Edit all in Scope` is a great way to rename things: `cmd + ctrl + e`
* If you have no idea what's wrong, and it should work clean your derived data with `cmd + alt + shift + k`
* Use the git commit sheet in Xcode, it's better than AppCode's: `cmd + alt + c`
