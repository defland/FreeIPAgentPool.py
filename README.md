
# FreeIPAgentPool.py

之前使用的购买付费代理IP成本比较高，干脆写一个获取免费IP的库。原理就是写多个爬虫，执行脚本时候，爬取免费ip地址，验证后返回可以使用的list。
Python+urllib2实时动态获取免费代理IP池工具包

# 爬取的免费ip地址来源

- http://www.kuaidaili.com/free/inha/1
- http://www.xicidaili.com/nn/1
- http://www.xdaili.cn/ipagent/freeip/getFreeIps?page=1&rows=10
- http://www.nianshao.me


# 依赖库

- 打印库 cprint https://github.com/Pingze-github/cprint
- 多线程 threading
- 正则 re

# 使用方法

```
import FreeIPAgentPool as ipool  

ipool_obj = ipool.IpSpiders()
free_list = ipool_obj.get_ip() # 返回当前可用的免费IP list
# print free_list

```

# 效果截图

[![9fLZCR.md.png](https://s1.ax1x.com/2018/03/13/9fLZCR.md.png)](https://imgchr.com/i/9fLZCR)
