---
name: Send SMS
language: android
read_more:
- https://developer.android.com/guide/components/intents-common#SendMessage
---
You can use the following code:

```java
Intent intent = new Intent(Intent.ACTION_VIEW, Uri.parse("sms:" + phoneNumber));     
intent.putExtra("sms_body", message); 
startActivity(intent);
```

Make sure you set `phoneNumber` to the phone number that you want to send the message to.
`message` paramater is optional.
