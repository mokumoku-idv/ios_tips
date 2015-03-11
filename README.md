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
