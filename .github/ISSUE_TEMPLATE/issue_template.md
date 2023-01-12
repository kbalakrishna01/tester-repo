#Bugs and Bug-Fixes of Huggies-JL Experience

Problem       | Description   |Solution  
------------- | ------------- | -------------
Replay Bug  | Mic is being enabled when replay function is revoked, this disturbs the other sound effects in the experience | MediaRecorder should be called only once and disable the revoking function of the same. 
Facebook Share - Android/ios  | Facebook do not allow text/description linked with the captured image to post in it's feed directly. | It cannot be made possible to enable the description of the image to be posted in the feed, as the facebook's policy restricts the same.
Share Function - iOS(first-tap) |Share function in ios works only once. It is an iOS safari bug. The fix has been implemented but is not yet available in an iOS build. | Implement [Tap + Hold] after the first click on share. Other workaround at this time would be to reload the page or use Replay function.[Code Snippet link to be added]