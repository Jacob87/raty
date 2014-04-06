# jQuery Raty FA - A Star Rating Plugin with Font Awesome - https://github.com/Jacob87/raty-fa

## 0.1

### News

+ Fork of [https://github.com/wbotelhos/raty](jQuery Raty)

### Changes

+ Adjusted scope of entire plugin to use <i> instead of <img> and Font Awesome instead of png assets;

## known Bugs

+ On versions before 1.6 if a attribute not exists, then empty string is returned instead undefined;
+ On 1.5.2 the opt.click callback is never called, because this version always returns undefined to .call() and .apply();
+ On 1.5.2 the attribute readonly is setted with empty value as following readonly="".
