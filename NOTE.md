# 模型参数
页面上设置的参数，好像没有生效，打印出来的都是空
可以增加默认参数

在docker_api容器下，修改如下代码即可
```
/app/api/core/model_runtime/model_providers/openai_api_compatible/llm/llm.py
```