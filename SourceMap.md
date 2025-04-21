# 🧠 Python技能树（进阶全景版 · Markdown版本）

## 1. Python基础
- [语法结构与缩进规范](./files/0101.md)  
- [数据类型：int / float / bool / str](./files/0102.md)  
- [输入输出与格式化输出](./files/0103.md)  
- [条件判断（if / elif / else）](./files/0104.md)  
- [循环控制（for / while / break / continue）](./files/0105.md)  
- [基础函数（定义、返回值、参数传递）](./files/0106.md)  
- [命名空间与作用域（LEGB规则）](./files/0107.md)  
- [编码与字符集（UTF-8 / BOM）](./files/0108.md)  

## 2. 数据结构进阶
- [列表 / 元组（操作技巧、切片）](./files/0201.md)  
- [字典（遍历、字典推导式、默认值处理）](./files/0202.md)  
- [集合（去重、交并差）](./files/0203.md)  
- [内置数据结构效率比较](./files/0204.md)  
- [collections模块（deque、defaultdict、Counter）](./files/0205.md)  

## 3. 函数式编程
- [匿名函数 lambda](./files/0301.md)  
- [map / filter / reduce 使用技巧](./files/0302.md)  
- [函数作为一等对象](./files/0303.md)  
- [装饰器（闭包、functools.wraps）](./files/0304.md)  
- [偏函数 partial](./files/0305.md)  

## 4. 面向对象编程（OOP）
- [类与实例](./files/0401.md)  
- [构造函数与魔术方法（`__init__`, `__str__`, `__repr__`）](./files/0402.md)  
- [继承与多态](./files/0403.md)  
- [类属性、实例属性、静态方法、类方法](./files/0404.md)  
- [私有属性与封装约定](./files/0405.md)  
- [Mixin设计模式](./files/0406.md)  
- [依赖注入与解耦技巧](./files/0407.md)  

## 5. 模块与包
- [import 与 from 的区别](./files/0501.md)  
- [相对导入与绝对导入](./files/0502.md)  
- [Python模块路径与 `PYTHONPATH`](./files/0503.md)  
- [`__main__` 的作用](./files/0504.md)  
- [`__init__.py` 文件的意义](./files/0505.md)  

## 6. 异常与调试
- [try-except-finally语法](./files/0601.md)  
- [捕捉多个异常、嵌套异常](./files/0602.md)  
- [自定义异常类](./files/0603.md)  
- [logging模块（日志级别、文件输出）](./files/0604.md)  
- [pdb调试、断点调试、traceback模块](./files/0605.md)  

## 7. 高级语法技巧
- [生成器（yield, send）](./files/0701.md)  
- [迭代器协议与 for 循环底层原理](./files/0702.md)  
- [上下文管理器（with, contextlib）](./files/0703.md)  
- [装饰器链式组合](./files/0704.md)  
- [类型注解（typing模块）](./files/0705.md)  
- [数据类（dataclasses）](./files/0706.md)  

## 8. 并发与异步
- [threading 与 GIL限制](./files/0801.md)  
- [multiprocessing 与进程间通信（Queue / Pipe）](./files/0802.md)  
- [异步IO（asyncio, await, async）](./files/0803.md)  
- [并发库（concurrent.futures）](./files/0804.md)  
- [队列与生产者消费者模式](./files/0805.md)  

## 9. 文件与IO操作
- [文件打开与关闭（open）](./files/0901.md)  
- [读写模式与二进制模式](./files/0902.md)  
- [文本编码问题](./files/0903.md)  
- [JSON / YAML / CSV 读写](./files/0904.md)  
- [pathlib / os / shutil 文件系统操作](./files/0905.md)  

## 10. 网络与爬虫
- [requests（基础用法、高级Session）](./files/1001.md)  
- [urllib 与 HTTP协议](./files/1002.md)  
- [爬虫框架：Scrapy](./files/1003.md)  
- [Selenium 自动化](./files/1004.md)  
- [代理池与反爬机制破解技巧](./files/1005.md)  
- [并发爬虫（协程 / 多线程）](./files/1006.md)  

## 11. 数据科学方向
- [Numpy 数组、广播、矩阵运算](./files/1101.md)  
- [Pandas 表格处理、分组聚合](./files/1102.md)  
- [数据可视化：Matplotlib / Seaborn](./files/1103.md)  
- [Jupyter Notebook 使用技巧](./files/1104.md)  
- [数据清洗（缺失值、重复值）](./files/1105.md)  

## 12. Web开发方向
- [Flask：路由、中间件、模板](./files/1201.md)  
- [Django：ORM、Admin后台、REST接口](./files/1202.md)  
- [FastAPI：异步、高性能接口开发](./files/1203.md)  
- [Session、Cookie、JWT认证机制](./files/1204.md)  
- [模板语言（Jinja2）](./files/1205.md)  

## 13. 自动化与脚本
- [批量文件处理脚本](./files/1301.md)  
- [办公自动化（Excel、PPT、邮件）](./files/1302.md)  
- [定时任务（schedule, APScheduler）](./files/1303.md)  
- [图像处理（Pillow）](./files/1304.md)  
- [PDF操作、OCR识别（PyPDF2 / Tesseract）](./files/1305.md)  

## 14. 测试与工程化
- [单元测试（unittest / pytest）](./files/1401.md)  
- [断言与测试覆盖率](./files/1402.md)  
- [mock模拟请求](./files/1403.md)  
- [CI/CD 自动测试集成](./files/1404.md)  
- [异常捕获日志与报警机制](./files/1405.md)  

## 15. 部署与环境管理
- [venv / virtualenv / pipenv](./files/1501.md)  
- [requirements.txt / poetry.lock](./files/1502.md)  
- [打包发布（setup.py / pyproject.toml）](./files/1503.md)  
- [Docker构建镜像](./files/1504.md)  
- [Gunicorn + Nginx 部署Flask应用](./files/1505.md)  

## 16. AI与机器学习
- [scikit-learn（模型训练与评估）](./files/1601.md)  
- [XGBoost / LightGBM](./files/1602.md)  
- [TensorFlow / Keras](./files/1603.md)  
- [PyTorch 与张量机制](./files/1604.md)  
- [OpenCV 图像处理](./files/1605.md)  
- [Transformers / NLP预训练模型](./files/1606.md)

