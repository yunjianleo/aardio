---
title:  "扩展库"
---


#### 如何使用

```aardio
//安装扩展库
_IMPORTURL["库名称"] = "库链接"
import 库名称; //导入刚安装的扩展库
```

#### 库列表

<dl>{% for object in site.data.lib %}
    <li><a href="samples/{{ object.last.keywords }}">{{ object | first }}</a>
        : {{ object.last.description }}
    </li>{% endfor %}
</dl>
