Column Store
============

Row
---

row store

+-----+-----+-----+-----+
| 1   | 2   | 3   | 4   |
+=====+=====+=====+=====+
+-----+-----+-----+-----+

Column
------

::

    1         2       3        4
    +----+  +----+  +----+   +-----+
    |    |  |    |  |    |   |     |
    +----+  +----+  +----|   +-----+
    |    |  |    |  |    |   |     |
    |    |  |    |  |    |   |     |
    |    |  |    |  |    |   |     |
    |    |  |    |  |    |   |     |
    |    |  |    |  |    |   |     |
    |    |  |    |  |    |   |     |
    |    |  |    |  |    |   |     |
    +----+  +----+  +----+   +-----+

利用 CPU 缓存
-------------

vid value index
