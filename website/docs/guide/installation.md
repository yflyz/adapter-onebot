---
侧栏_位置：1
描述：安装

options:
  menu:
重量：10
类别：指南
---

# 安装

##安装 NoneBot

```猛敲
nb适配器安装nonebot-适配器-onebot
```

或者使用 pip

```猛敲
安装nonebot-适配器-onebot
```

## 加载适配器

###OneBot V11

```python title=bot.py {2,7}
进口nonebot
从nonebot.adapters.onebot.v11导入适配器

nonebot.init()

driver = nonebot.get_driver()
driver.register_adapter(Adapter)
```

###OneBot V12

```python title=bot.py {2,7}
import nonebot
from nonebot.adapters.onebot.v12 import Adapter

nonebot.init()

driver = nonebot.get_driver()
driver.register_adapter(Adapter)
```
