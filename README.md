WebDirScan
本项目所有内容,仅供学习和研究使用,请勿使用项目的技术手段用于非法用途,任何人造成的任何负面影响,与本人无关.
目录扫描工具
这个项目是一个URL扫描工具，它从字典文件中获取URL路径列表，并检查它们是否有效。该工具使用并行处理来提高扫描效率，并将有效的URL记录到文件中。

功能
从提供的字典文件中扫描URL。
使用并行处理加快URL扫描速度。
将有效的URL记录到文件中。
安装
克隆仓库：


复制代码
git clone https://github.com/yourusername/catalog-scanning-tool.git
cd catalog-scanning-tool
安装依赖项：
确保你已经安装了Python。你可以使用以下命令安装所需的包：


复制代码
pip install requests tqdm
使用方法
准备你的字典文件：

创建一个文本文件，包含要扫描的URL路径，每行一个。
运行扫描工具：


复制代码
python Catalog\ scanning\ tool.py
脚本会提示你输入字典文件的路径和要扫描的基础URL。
输出结果：

脚本会生成一个名为url_go.txt的文件，里面包含有效的URL。
示例
创建字典文件：


复制代码
echo "/path1" >> dict.txt
echo "/path2" >> dict.txt
echo "/path3" >> dict.txt
运行工具：


复制代码
python Catalog\ scanning\ tool.py
当提示时，输入字典文件的路径和基础URL：

复制代码
请输入字典文件路径（含文件名）：dict.txt
请输入需要扫描的URL（含协议）：http://example.com
查看输出结果：

打开url_go.txt文件查看有效的URL列表。

作者
Yuu_z
