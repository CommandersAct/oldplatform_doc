---
description: Get platform users.
---

# Get Users

{% swagger baseUrl="https://api.commander1.com" path="/v2/{siteId}/users" method="get" summary="Users" %}
{% swagger-description %}
Two usages :

\


GET 

**/users/**

 : Returns a list of user properties (depending on the parameters requested) linked to the users of a site.

\


GET 

**/users/123**

 : Return properties of one user (id 

**123**

) on one site.

\




\


Click below to download complete API documentation
{% endswagger-description %}

{% swagger-parameter in="query" name="id" type="integer" %}
The user id
{% endswagger-parameter %}

{% swagger-parameter in="query" name="include" type="string" %}
`permissions`

 or 

`roles`

 or both separated by a comma
{% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
```
{% endswagger-response %}
{% endswagger %}

{% file src="../.gitbook/assets/global-platform-api (1).html" %}
Download complete API documentation
{% endfile %}

