# First Blog
* General info
* Screenshots
* Technologies
* Features
* Code sample
* Status

## General info
My first atend to make blog.
## Screenshots
  ![Image of the game](https://github.com/SboTeaman/My-first-blog/blob/master/blog.png)
## Technologies
Language: 
* Python
* Django

## Features
Player can:
* add new post
* eddit post

## Code sample
```
<body>
    <header class="page-header">
        <div class="container">
            <a href="{% url 'post_new' %}" class="top-menu">
                {% include './icons/file-earmark-plus.svg' %}
            </a>
            <h1><a href="/">Some blog</a></h1>
        </div>
    </header>
    <main class="content container">
        <div class="row">
            <div class="col">
                {% block content %}
                {% endblock %}
            </div>
        </div>
    </main>
</body>
 ``` 
## Status
Project is: *in progress*.
