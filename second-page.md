---
description: Here is its description.
---

# Second page

And here is some more content.

> This is a nice quote

{% hint style="info" %}
This is a hint!
{% endhint %}

{% api-method method="get" host="https://api.example.com" path="/urlpath/:param" %}
{% api-method-summary %}
api-method-example
{% endapi-method-summary %}

{% api-method-description %}
Method description
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="Parameter" type="string" required=false %}
Description of parameter.
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
200 response.
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

Here is some spacer text because this is getting funky!

{% tabs %}
{% tab title="First Tab" %}
Here is first tab content.
{% endtab %}

{% tab title="Second Tab" %}
Here is second tab content.
{% endtab %}
{% endtabs %}

More spacer text.

$$
a = \int_0^\infty x dx.
$$

Wow, LaTeX!

{% page-ref page="second-page.md" %}

