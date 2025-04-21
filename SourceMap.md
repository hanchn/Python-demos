# 🧠 Python技能树（进阶全景版 · Markdown版本）

## 1. Python基础
- [语法结构与缩进规范](./Files/0101.md)  
- [数据类型：int / float / bool / str](./Files/0102.md)  
- [输入输出与格式化输出](./Files/0103.md)  
- [条件判断（if / elif / else）](./Files/0104.md)  
- [循环控制（for / while / break / continue）](./Files/0105.md)  
- [基础函数（定义、返回值、参数传递）](./Files/0106.md)  
- [命名空间与作用域（LEGB规则）](./Files/0107.md)  
- [编码与字符集（UTF-8 / BOM）](./Files/0108.md)  

## 2. 数据结构进阶
- [列表 / 元组（操作技巧、切片）](./Files/0201.md)  
- [字典（遍历、字典推导式、默认值处理）](./Files/0202.md)  
- [集合（去重、交并差）](./Files/0203.md)  
- [内置数据结构效率比较](./Files/0204.md)  
- [collections模块（deque、defaultdict、Counter）](./Files/0205.md)  

## 3. 函数式编程
- [匿名函数 lambda](./Files/0301.md)  
- [map / filter / reduce 使用技巧](./Files/0302.md)  
- [函数作为一等对象](./Files/0303.md)  
- [装饰器（闭包、functools.wraps）](./Files/0304.md)  
- [偏函数 partial](./Files/0305.md)  

## 4. 面向对象编程（OOP）
- [类与实例](./Files/0401.md)  
- [构造函数与魔术方法（`__init__`, `__str__`, `__repr__`）](./Files/0402.md)  
- [继承与多态](./Files/0403.md)  
- [类属性、实例属性、静态方法、类方法](./Files/0404.md)  
- [私有属性与封装约定](./Files/0405.md)  
- [Mixin设计模式](./Files/0406.md)  
- [依赖注入与解耦技巧](./Files/0407.md)  

## 5. 模块与包
- [import 与 from 的区别](./Files/0501.md)  
- [相对导入与绝对导入](./Files/0502.md)  
- [Python模块路径与 `PYTHONPATH`](./Files/0503.md)  
- [`__main__` 的作用](./Files/0504.md)  
- [`__init__.py` 文件的意义](./Files/0505.md)  

## 6. 异常与调试
- [try-except-finally语法](./Files/0601.md)  
- [捕捉多个异常、嵌套异常](./Files/0602.md)  
- [自定义异常类](./Files/0603.md)  
- [logging模块（日志级别、文件输出）](./Files/0604.md)  
- [pdb调试、断点调试、traceback模块](./Files/0605.md)  

## 7. 高级语法技巧
- [生成器（yield, send）](./Files/0701.md)  
- [迭代器协议与 for 循环底层原理](./Files/0702.md)  
- [上下文管理器（with, contextlib）](./Files/0703.md)  
- [装饰器链式组合](./Files/0704.md)  
- [类型注解（typing模块）](./Files/0705.md)  
- [数据类（dataclasses）](./Files/0706.md)  

## 8. 并发与异步
- [threading 与 GIL限制](./Files/0801.md)  
- [multiprocessing 与进程间通信（Queue / Pipe）](./Files/0802.md)  
- [异步IO（asyncio, await, async）](./Files/0803.md)  
- [并发库（concurrent.futures）](./Files/0804.md)  
- [队列与生产者消费者模式](./Files/0805.md)  

## 9. 文件与IO操作
- [文件打开与关闭（open）](./Files/0901.md)  
- [读写模式与二进制模式](./Files/0902.md)  
- [文本编码问题](./Files/0903.md)  
- [JSON / YAML / CSV 读写](./Files/0904.md)  
- [pathlib / os / shutil 文件系统操作](./Files/0905.md)  

## 10. 网络与爬虫
- [requests（基础用法、高级Session）](./Files/1001.md)  
- [urllib 与 HTTP协议](./Files/1002.md)  
- [爬虫框架：Scrapy](./Files/1003.md)  
- [Selenium 自动化](./Files/1004.md)  
- [代理池与反爬机制破解技巧](./Files/1005.md)  
- [并发爬虫（协程 / 多线程）](./Files/1006.md)  

## 11. 数据科学方向
- [Numpy 数组、广播、矩阵运算](./Files/1101.md)  
- [Pandas 表格处理、分组聚合](./Files/1102.md)  
- [数据可视化：Matplotlib / Seaborn](./Files/1103.md)  
- [Jupyter Notebook 使用技巧](./Files/1104.md)  
- [数据清洗（缺失值、重复值）](./Files/1105.md)  

## 12. Web开发方向
- [Flask：路由、中间件、模板](./Files/1201.md)  
- [Django：ORM、Admin后台、REST接口](./Files/1202.md)  
- [FastAPI：异步、高性能接口开发](./Files/1203.md)  
- [Session、Cookie、JWT认证机制](./Files/1204.md)  
- [模板语言（Jinja2）](./Files/1205.md)  

## 13. 自动化与脚本
- [批量文件处理脚本](./Files/1301.md)  
- [办公自动化（Excel、PPT、邮件）](./Files/1302.md)  
- [定时任务（schedule, APScheduler）](./Files/1303.md)  
- [图像处理（Pillow）](./Files/1304.md)  
- [PDF操作、OCR识别（PyPDF2 / Tesseract）](./Files/1305.md)  

## 14. 测试与工程化
- [单元测试（unittest / pytest）](./Files/1401.md)  
- [断言与测试覆盖率](./Files/1402.md)  
- [mock模拟请求](./Files/1403.md)  
- [CI/CD 自动测试集成](./Files/1404.md)  
- [异常捕获日志与报警机制](./Files/1405.md)  

## 15. 部署与环境管理
- [venv / virtualenv / pipenv](./Files/1501.md)  
- [requirements.txt / poetry.lock](./Files/1502.md)  
- [打包发布（setup.py / pyproject.toml）](./Files/1503.md)  
- [Docker构建镜像](./Files/1504.md)  
- [Gunicorn + Nginx 部署Flask应用](./Files/1505.md)  

## 16. AI与机器学习
- [scikit-learn（模型训练与评估）](./Files/1601.md)  
- [XGBoost / LightGBM](./Files/1602.md)  
- [TensorFlow / Keras](./Files/1603.md)  
- [PyTorch 与张量机制](./Files/1604.md)  
- [OpenCV 图像处理](./Files/1605.md)  
- [Transformers / NLP预训练模型](./Files/1606.md)

