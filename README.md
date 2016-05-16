Replacement of `sizeWithFont:` and `sizeWithFont:constrainedToSize:` in iOS7 or above.  
Based on `boundingRectWithSize:options:attributes:context:`.


```
@interface NSString (SizeWithFontIniOS7)

- (CGSize)sizeWithFontIniOS7:(UIFont *)font;
- (CGSize)sizeWithFontIniOS7:(UIFont *)font constrainedToSize:(CGSize)size;

@end
```