#GXToastDemo

## How To Use
- Copy GXToast.h and GXToast.m to your project,
- Import GXToast.h to file if you want to use it
- code like this:
 ```objc
[GXToast showText:@"默认显示"];
[GXToast showText:@"上面显示" position:GXToastPositionTop duration:2.0f];
[GXToast showText:@"上面显示+100偏移" position:GXToastPositionTop offset:100 duration:2.0f];
[GXToast showText:@"下面显示+200偏移" position:GXToastPositionBottom offset:200 duration:2.0f];
[GXToast showText:@"下面显示" position:GXToastPositionBottom duration:2.0f];
 ```
