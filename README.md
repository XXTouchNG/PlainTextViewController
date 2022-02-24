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

## Screenshots

<p float="left">
  <img src="/IMG_0022.PNG" width="32%">
  <img src="/IMG_0023.PNG" width="32%">
</p>
