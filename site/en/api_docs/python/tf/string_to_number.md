

page_type: reference
<style> table img { max-width: 100%; } </style>


<!-- DO NOT EDIT! Automatically generated file. -->

# tf.string_to_number

``` python
tf.string_to_number(
    string_tensor,
    out_type=tf.float32,
    name=None
)
```



Defined in generated file: `tensorflow/python/ops/gen_parsing_ops.py`.

See the guides: [Strings > Conversion](../../../api_guides/python/string_ops#Conversion), [Tensor Transformations > Casting](../../../api_guides/python/array_ops#Casting)

Converts each string in the input Tensor to the specified numeric type.

(Note that int32 overflow results in an error while float overflow
results in a rounded value.)

#### Args:

* <b>`string_tensor`</b>: A `Tensor` of type `string`.
* <b>`out_type`</b>: An optional <a href="../tf/DType"><code>tf.DType</code></a> from: `tf.float32, tf.float64, tf.int32, tf.int64`. Defaults to <a href="../tf/float32"><code>tf.float32</code></a>.
    The numeric type to interpret each string in `string_tensor` as.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor` of type `out_type`.