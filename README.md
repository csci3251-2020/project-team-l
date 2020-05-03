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

![](https://github.com/csci3251-2020/project-team-l/workflows/C%2FC++%20CI/badge.svg)

# Contributors  

{% for stu in site.stu %}
    <blockquote> 
    <p>&gt;&gt;!({{stu.image}})
        @{{ stu.user }}({{ stu.name }})<br />
        <blockquote>
            &gt;&gt;{{ stu.content | markdownify }}</p>
{% endfor %} 
