# Introduction  
Here is a short summary of things our team will do.

To begin, we need to start issues, create a project board and set up readme.md.

When the readme.md is ready, we need to show our team to the Internet.

After that, we need to write C code and get a status badge.

During the whole process, we need to keep checking our tasks and pull requests.

Finally, we will promote our repo.
    
# Code    

```c
{% include_relative code.c %}
```

# Contributors  

```c
{% for stu in site.stu %}
  <h2>
    <a href="{{ stu.image }}">
      @{{ stu.user }}({{ stu.name }})
    </a>
  </h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}
```
