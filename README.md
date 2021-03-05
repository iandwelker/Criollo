

[![Criollo](https://criollo.io/res/doc/images/criollo-github.png)](https://criollo.io/)

This is just a fork of [Criollo](https://github.com/thecatalinstan/Criollo) with a few modifications:
1. It has support for HTML5 `multiple` input tags
1. It doesn't filter out plus signs from URL requests
1. It fixes an issue with URL Query parsing by encoding the URL to prevent special, unencoded characters, from messing things up
1. It fixes an issue with HTTP `Host` header parsing by checking for both `host` and `Host`.
