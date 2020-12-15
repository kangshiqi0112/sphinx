=======================
welcome
=======================

通过使用标点符号为节标题(ref)加下划线(上划线可选)来创建节标题, 至少与文本一样长:
sphinx 使用restructuredText作为他的标记语言

- **输出格式：** 超文本标记语言
- **输出格式：** 超文本标记语言
- **一个*：** \ *表示斜体*
- **两个‘**’：** 用于强调（粗体）
- **代码两个反引号：**\ ``include dddddd``


* this is
* a list

  * with a nested list
  * and some subitems

* and here the parent list continues
* 嵌套列表，但注意它们必须通过空行与父列表项分开:

This is a normal text paragraph. The next paragraph is a code sample::

   It is not processed in any way, except
   that the indentation is removed.

   It can span multiple lines.

This is a normal text paragraph again.

=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======

This is a paragraph that contains `a link`_.

.. _a link: https://domain.invalid/






.. image:: 1.png

对于脚注(ref)，使用 \[#name]_ \标记脚注位置，并在 “Footnotes ” 标题后添加脚注主体在文档底部，像这样:

Lorem ipsum [#f1]_ dolor sit amet ... [#f2]_

.. rubric:: Footnotes

.. [#f1] Text of the first footnote.
.. [#f2] Text of the second footnote.

支持标准reST引用(ref)，其附加功能是 “global” ，即所有引用都可以从所有文件引用。像这样使用它们:

Lorem ipsum [Ref]_ dolor sit amet.

.. [Ref] Book or article reference, URL or whatever.

.. This is a comment.
   This whole indented block
   is a comment.

   Still in the comment.