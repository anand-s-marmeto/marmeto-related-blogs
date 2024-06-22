Add the below code to main-article.liquid:-

To render the snippet:
{% when 'related-blogs' %}
  {% render 'related-blogs' , block: block , article : article}

To block settings:
{
  "type": "related-blogs",
  "name":"Related blogs",
  "settings":[
    {
      "type": "text",
      "id": "heading",
      "label":"Heading",
      "info": "The heading for the related articles",
      "default":"Related posts"
    }
  ]
}

Note: Change css properties based on your requirement.