# GROIW Amazon Plugin

This is a amazon plugin for GROWI. It creates a link to amazon with image.

## Install

Install a plugin in admin panel.

## Usage

```
$amazon(asin=4873119235)
```

That is changed to the link https://www.amazon.co.jp/dp/4873119235.
If the asin is ISBN10 or ISBN13, ie. that is a book, the link is a book picture from hanmoto.com .

## Options

You can specify a title for the link.
```
$amazon(asin=4873119235,title=ハンズオンNode-js)
```

You can also specify a link to amazon.com. Thils plugin will decode the book title or item name from the url to use as title of it.
```
$amazon(url=https://www.amazon.co.jp/%E3%83%8F%E3%83%B3%E3%82%BA%E3%82%AA%E3%83%B3Node-js-%E4%BB%8A%E6%9D%91-%E8%AC%99%E5%A3%AB/dp/4873119235/)
```


## License

MIT

