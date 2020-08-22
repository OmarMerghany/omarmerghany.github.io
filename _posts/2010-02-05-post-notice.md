<!-- ---
title: "Post: Notice"
categories:
  - Blog
tags:
  - Post Formats
  - notice
---

A.

n `{: .notice}` ce `.notice` te `<p></p>` e. 

**Changes in Service:** W [privacy policy](#) h.
{: .notice}

**Primary Notice:** L [Praesent libero](#). S.
{: .notice--primary}

**Info Notice:** L [consectetur adipiscing elit](#). I.
{: .notice--info}

**Warning Notice:** L [Integer nec odio](#). .
{: .notice--warning}

**Danger Notice:** L [consectetur adipiscing](#) e.
{: .notice--danger}

**Success Notice:** L [nibh elementum](#) .
{: .notice--success}

W `markdownify` i.

```html
{% raw %}{% capture notice-2 %}
#### New Site Features

* You can now have cover images on blog pages
* Drafts will now auto-save while writing
{% endcapture %}{% endraw %}

<div class="notice">{% raw %}{{ notice-2 | markdownify }}{% endraw %}</div>

```

{% capture notice-2 %}
#### N

* Y
* D
{% endcapture %}

<div class="notice">
  {{ notice-2 | markdownify }}
</div>

O.

```html
<div class="notice">
  <h4>Message</h4>
  <p>A basic message.</p>
</div>
```

<div class="notice">
  <h4>M</h4>
  <p>A b</p>
</div> -->