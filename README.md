# Fixer

[![Travis](https://travis-ci.org/hakanensari/fixer.svg)](https://travis-ci.org/hakanensari/fixer)

Fixer is a Ruby wrapper to the [XML feeds of Euro foreign exchange reference rates](http://www.ecb.int/stats/exchange/eurofxref/html/index.en.html) provided by the European Central Bank. The reference rates are updated around 16:00 CET on working days.

```ruby
feed = Fixer::Feed.new
feed.each do |currency|
  # puts currency
end
```
