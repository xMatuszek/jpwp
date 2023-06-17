# Polecenia do zadań
**Ważne jest, aby zadania były wykonywane po kolei, zgodnie z ustaloną kolejnością.**

Baza MNIST jest tak zwanym "hello world" dla ML. Jest to zbiór ręcznie pisanych cyfr wykorzystywany do treningu różnych systemów ML. Jest to problem wieloklasowego klasyfikatora - rozpoznawanie cyfr 0, 1, ..., 9.

Baza składa się z 60k obrazów treningowych (skala szarości 28x28 pikseli) i 10k obrazów testowych.

## Przygotowanie do zadań
```
import tensorflow as tf 

# import MNIST dataset
(x_train, y_train), (x_valid, y_valid) = tf.keras.datasets.mnist.load_data()
x_train = x_train.reshape(60000, 784).astype('float32') / 255       # 784 = 28*28
x_valid = x_valid.reshape(10000, 784).astype('float32') / 255

print('x_train size: ' + str(x_train.shape))
```

