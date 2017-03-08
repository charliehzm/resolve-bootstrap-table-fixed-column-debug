# resolve-bootstrap-table-fixed-column-debug

1，用bootstrap-table实现表格固定表头和列
question：
此插件用于生成固定列的表格，

在一行表头的情况下固定列没有问题，

但是当表头多于一行或者固定的表头部分有合并单元格的情况下此插件有bug，

resolve：
可以通过修改bootstrap-table-fixed-columns.js来修复bug，

对固定表头的修改在initHeader原型中修改，

对固定body的修改在initBody函数原型中修改
