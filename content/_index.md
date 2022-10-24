+++
title = "juice"
sort_by = "weight"
+++

# How to make an API request

URL: `api.pdfy.ml/render`
<pre><code>{
	"url": "https://www.google.com",
	"landscape": true,                  // optional, default: false
	"format": "A3",                     // optional, default: A4
	"headers": {                        // optional, default: {}
		"subdomain.domain.com": {
			"Authorization": "Bearer testtoken"
		}
	}
}
</code></pre>

Postman collection [https://documenter.getpostman.com/view/7143179/2s84LF4Gf4](https://documenter.getpostman.com/view/7143179/2s84LF4Gf4)
