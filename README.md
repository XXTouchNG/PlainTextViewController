# PlainTextViewController

A simple plain text viewer in Objective-C.

## Usage

```objective-c
PlainTextViewController *c = [[PlainTextViewController alloc] initWithPath:aPlainTextFilePath];
c.allowTrash = NO;
[aNavigationController pushViewController:c animated:YES];
```
