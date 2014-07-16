# JSONP

## What is JSONP?

As you know, AJAX is not allowed for CORS since 'the Same-Origin Policy'.

So, people came up with the a trick of using(abusing) src tag to query CORS,

By using *GET* method in script tag to make cross domain requests.

The response from the server will be in JSON format, and will be executed as JS.

PS: Rumor also says HTML5 will be allowing CORS via AJAX.

I hope this example will help you to understand what JSONP is and how it works
in a intuitive way.

## Example

Run `python -m SimpleHTTPServer`, and open
[http://localhost:8000/jsonp.html](http://localhost:8000/jsonp.html)
to see what's going on.

## Reference:

[简单描述JSON跟JSONP的区别以及实战](http://www.qixing318.com/article/simply-describe-the-difference-between-json-with-json-as-well-as-the-actual-combat.html)

[JSONP跨域的原理解析](http://www.nowamagic.net/librarys/veda/detail/224)
