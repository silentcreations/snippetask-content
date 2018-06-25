---
name: Send SMS
language: ios
read_more:
- https://developer.apple.com/documentation/messageui/mfmessagecomposeviewcontroller
---
Here is a tutorial which does exactly what you are looking for: the `MFMessageComposeViewController`.

```objectivec
MFMessageComposeViewController *controller = [[[MFMessageComposeViewController alloc] init] autorelease];
if([MFMessageComposeViewController canSendText]) {
    controller.body = @"SMS message here";
    controller.recipients = [NSArray arrayWithObjects:@"1(234)567-8910", nil];
    controller.messageComposeDelegate = self;
    [self presentModalViewController:controller animated:YES];
}
```
