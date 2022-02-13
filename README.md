# PlainTextViewController

A simple plain text viewer in Objective-C.

## Usage

```objective-c
PlainTextViewController *ctrl = [[PlainTextViewController alloc] initWithPath:[[NSBundle mainBundle] pathForResource:@"passwd" ofType:@""]];
ctrl.pullToReload = YES;
ctrl.allowSearch = YES;
UINavigationController *navCtrl = [[UINavigationController alloc] initWithRootViewController:ctrl];
[self presentViewController:navCtrl animated:YES completion:nil];
```
