# Fake115Upload
模拟115客户端的上传功能，支持极速秒传和本地文件上传及网盘文件批量导入和导出。(谨慎使用批量导入功能，115本身并未提供此类功能，出了问题概不负责。）

# Usage:
```
$root:python Fake115Upload.py 
Options:
-l filename: 从本地上传一个文件，支持秒传和普通上传两种方式。
-i filename: 从本地文本读取（文件名|文件大小|文件HASH值|块HASH）字段值并将其导入到115中。
-o filename: 从115中导出所有文件的（文件名|文件大小|文件HASH值）字段值到本地文本。
-m filename: 从本地当前目录导出所有文件的（文件名|文件大小|文件HASH值|块HASH）字段值到本地文本。
```
