.. _cn_overview_paddle:

paddle.incubate.sparse
---------------------

paddle.incubate.sparse 目录包含飞桨框架支持稀疏数据存储和计算相关的 API。具体如下：

-  :ref:`稀疏数据结构相关 <about_sparse_tensor>`
-  :ref:`数学操作 API <about_sparse_math>`
-  :ref:`NN 相关 API <about_sparse_nn>`

.. _about_sparse_tensor:

稀疏数据结构相关
::::::::::::::::::::

.. csv-table::
    :header: "API 名称", "API 功能"

    " :ref:`paddle.incubate.sparse.sparse_coo_tensor <cn_api_paddle_incubate_sparse_coo_tensor>` ", "创建一个 COO 格式的 SparseTensor"
    " :ref:`paddle.incubate.sparse.sparse_csr_tensor <cn_api_paddle_incubate_sparse_csr_tensor>` ", "创建一个 CSR 格式的 SparseTensor"


.. _about_sparse_math:

数学操作相关
::::::::::::::::::::

.. csv-table::
    :header: "API 名称", "API 功能"

    " :ref:`paddle.incubate.sparse.abs` ", "绝对值函数"
    " :ref:`paddle.incubate.sparse.add` ", "Sparse Tensor 逐元素相加"
    " :ref:`paddle.incubate.sparse.asin` ", "arcsine 函数"
    " :ref:`paddle.incubate.sparse.asinh` ", "反双曲正弦函数"
    " :ref:`paddle.incubate.sparse.atan` ", "反双曲正切函数"


.. _about_sparse_nn:

NN 相关
::::::::::::::::::::

.. csv-table::
    :header: "API 名称", "API 功能"

    " :ref:`paddle.incubate.sparse.nn.Conv3D` ", "三维卷积"
    " :ref:`paddle.incubate.sparse.nn.SubmConv3D` ", "三维的 submanifold 卷积"
    " :ref:`paddle.incubate.sparse.nn.Relu` ", "激活函数"
