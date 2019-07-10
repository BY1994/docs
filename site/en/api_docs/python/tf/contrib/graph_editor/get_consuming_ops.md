page_type: reference
<style>{% include "site-assets/css/style.css" %}</style>

<!-- DO NOT EDIT! Automatically generated file. -->

# tf.contrib.graph_editor.get_consuming_ops

``` python
tf.contrib.graph_editor.get_consuming_ops(ts)
```



Defined in [`tensorflow/contrib/graph_editor/util.py`](https://github.com/tensorflow/tensorflow/blob/r1.13/tensorflow/contrib/graph_editor/util.py).

Return all the consuming ops of the tensors in ts.

#### Args:

* <b>`ts`</b>: a list of <a href="../../../tf/Tensor"><code>tf.Tensor</code></a>

#### Returns:

A list of all the consuming <a href="../../../tf/Operation"><code>tf.Operation</code></a> of the tensors in `ts`.

#### Raises:

* <b>`TypeError`</b>: if ts cannot be converted to a list of <a href="../../../tf/Tensor"><code>tf.Tensor</code></a>.