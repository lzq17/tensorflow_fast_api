# tensorflow_fast_api
python setup.py build install

# use_guide
```bash
python test.py
```
```python
from tf_fast_api import *
tf.random.set_seed(2021)
x = tf.random.normal((3,5))
print(x.sum())
print(x.reduce_sum())
print(tf.reduce_sum(x))
#tf.Tensor(1.4016838, shape=(), dtype=float32)
#tf.Tensor(1.4016838, shape=(), dtype=float32)
#tf.Tensor(1.4016838, shape=(), dtype=float32)
```