.. _cn_api_tensor_floor_divide:

floor_divide
-------------------------------

.. py:function:: paddle.floor_divide(x, y, name=None)

逐元素整除算子，输入 ``x`` 与输入 ``y`` 逐元素整除，并将各个位置的输出元素保存到返回结果中。
输入 ``x`` 与输入 ``y`` 必须可以广播为相同形状，关于广播规则，请参考 :ref:`cn_user_guide_broadcasting`

等式为：

.. math::
        Out = X // Y

- :math:`X`：多维 Tensor。
- :math:`Y`：多维 Tensor。

参数
:::::::::
        - x（Tensor）- 多维 Tensor。数据类型为 int32 或 int64。
        - y（Tensor）- 多维 Tensor。数据类型为 int32 或 int64。
        - name（str，可选）- 操作的名称(可选，默认值为 None）。更多信息请参见 :ref:`api_guide_Name`。


返回
:::::::::
多维 Tensor，数据类型与 ``x`` 相同，维度为广播后的形状。


代码示例
:::::::::

COPY-FROM: paddle.floor_divide
