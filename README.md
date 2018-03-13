
# FreeIPAgentPool.py

之前使用的购买付费代理IP成本比较高，干脆写一个获取免费IP的库。
Python+urllib2实时动态获取免费代理IP池工具包

# 依赖库

- cprint 打印库 https://github.com/Pingze-github/cprint
- 多线程标准库 threading

# 使用方法

```
import FreeIPAgentPool as ipool  

ipool_obj = ipool.IpSpiders()
free_list = ipool_obj.get_ip() # 返回当前可用的免费IP list
# print free_list

```

# 效果截图

[![9fLZCR.md.png](https://s1.ax1x.com/2018/03/13/9fLZCR.md.png)](https://imgchr.com/i/9fLZCR)
