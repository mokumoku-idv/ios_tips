# What is this
this page is to add tips of ios development which i realized.

## i want to move uiimage by my gesture

i will read below page.

http://d.hatena.ne.jp/yoheiM/20110925
##
## when application crash i want to know information further
i guess it is good way.
http://www.crossbridge.biz/nssetuncaughtexceptionhandler

## Logging
http://blog.jarinosuke.com/entry/2013/01/25/intermediate_ios_debugging

https://www.assembla.com/wiki/show/snlog

## when nsmutablearray has exc_bad_access
maybe i will fix.

http://stackoverflow.com/questions/3967104/nsmutablearray-exc-bad-access-when-i-try-read-from-it

https://github.com/shiratsu/neocafesagashi/commit/8068e7846e2d3e3ef71401c63d77a588a7165564

## ios http connect
it is probably most famous libraly about http connect,Alamofire.

http://dev.classmethod.jp/references/swift-oss-alamofire-1/

## スレッドセーフ
あるコードがスレッドセーフであるという場合、そのコードを複数のスレッドが同時並行的に実行しても問題が発生しないことを意味する。
if some-code is thead-safe,this code can move on multi.


## I tryed to distribute ipa file by fabric.
1. At first,to create ipa file by xcode anyway.
2. after creating ipa file,fabric will show some display.
3. this display said
'Achive build sucessful. Would you like to distribute 〜 to testers?'
4. please select Distribute for you
5. You can watch Text box + button.
6. you should set the email.if you want to add more,please press add.
Then,you should set mail-address each person.
7. if this is finishing,you should send mail by fabric.
8. to be sended should check e-mail
9. please follow email and fabirc.
10. 

# Push notification by Zero Push on Heroku
* https://zeropush.com/

# How to use xcodebuild
* xcodebuild is to build ios application by command line.
* http://blog.asial.co.jp/953 
* 
# command line build script
## shenzen
* http://qiita.com/k_kinukawa/items/8718aba35060cf838ffa
* it's very useful!

# Push Notification with normal way
* i will also create push notification with watch kit.
* https://sites.google.com/site/aoi68k/home/push-notificationwo-shittemiru

## Payload
* APNSで送るメッセージの正体。実体はJSONファイル
* https://developer.apple.com/library/ios/documentation/NetworkingInternet/Conceptual/RemoteNotificationsPG/Chapters/ApplePushService.html#//apple_ref/doc/uid/TP40008194-CH100-SW1

## to want to divide build which debug or release.
* http://qiita.com/ryusukefuda/items/63194d1165cdaea18ec9
* 

## difference between local notification and remote notification
* Remote can't use on simulator.
* local notification is to notice in same application.
* ローカルnotificationは同じアプリ内の通知である

## for example about localnotification
* Todo application.when todo task is approching,it notice.
* 

### good sample of local notification
* https://sites.google.com/site/propicaudio/sample-code/notification-test
* 

## To transfer development setting 
* http://makotton.com/2014/10/24/625
* 

## FMDB with ORM
* http://mbehan.com/post/105556974748/super-basic-orm-on-top-of-fmdb-and-sqlite-for-ios

## NSURLSession
* This is instead of nsurlrequest.I think it is to use easier than nsurlrequest.
* http://chicketen.blog.jp/archives/15787549.html

## PlayGround

Not to repeat to try playground.
In playground,we can't try viewcontroller.If we want to use viewcontroller,i must develop by common way.

## property of value
* I think this page is good.
* http://natsuapps.com/note/2011/11/ios5-arc-overview.html

## Auto Layout
* i think following page is good for me to understand auto-layout.
* http://engineer.typemag.jp/article/ra-ios-tips06
* http://qiita.com/teradonburi/items/94b89379aa5a0bfdc71d
* 

# EXC_BAD_INSTRUCTION
* In i use not an optioanl value<br>
If this value is setted to the 'nil',This error will be produced.

## How to use instrument
* http://blog.fenrir-inc.com/jp/2013/04/improve-mac-ios-apps-with-instruments.html
* I guess it is good for me to use leaks to debug iPhone application<br>
Product→Profile<br>
If i want to use profile I must check scheme info before running profile.

# About protocol and delegate of objective-c
* http://www.objectivec-iphone.com/introduction/protocol/protocol.html

## swift クロージャ記法
* http://qiita.com/kiyotaman/items/55966cc10ef2ed44c4fd

## iOS web フック
* http://www.yoheim.net/blog.php?q=20130105
* http://blog.ch3cooh.jp/entry/20130208/1360299071

* http://www.ibm.com/developerworks/jp/mobile/library/mo-ios-memory/

## memory leak when i use nsurlsession on iOS8
* It happened when i run it on instruments's debugger
* CFNetwork NSCachedURLResponce
* CFNetwork HTTPProtocol CopyVartState NSURLSession
* iOS8のみで、デバッガと接続してる時のみっぽい
* http://ja.stackoverflow.com/questions/4527/nsurlsession-%E3%81%AB%E3%82%88%E3%82%8B%E9%80%A3%E7%B6%9A%E3%83%80%E3%82%A6%E3%83%B3%E3%83%AD%E3%83%BC%E3%83%89%E3%81%AB%E3%81%8A%E3%81%91%E3%82%8B%E3%83%A1%E3%83%A2%E3%83%AA%E3%83%AA%E3%83%BC%E3%82%AF-ios8
* 

## view hierarchy debugger
* when you have some troubles on looks of aplication,you should use 'view hierarchy debugger'.
* http://blog.atrac613.com/2015/01/28/debug-view-hierarchy/
