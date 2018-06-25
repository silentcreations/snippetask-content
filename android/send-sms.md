---
name: Send SMS
language: android
read_more:
- http://guides.rubyonrails.org/routing.html#segment-constraints
---
You can use the following code:

```java
Intent intent = new Intent(Intent.ACTION_VIEW, Uri.parse("sms:" + phoneNumber));     
intent.putExtra("sms_body", message); 
startActivity(intent);
```

Make sure you set `phoneNumber` to the phone number that you want to send the message to.
