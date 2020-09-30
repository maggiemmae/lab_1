# lab_1
1. Обучение модели из примера

а.batch_size = 256

        tf.keras.models.Sequential([
        tf.keras.layers.Input(shape=(224,224,3)),
        tf.keras.layers.Conv2D(filters=8, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Conv2D(filters=8, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Flatten(),
        tf.keras.layers.Dense(NUM_CLASSES, activation=tf.keras.activations.softmax)
        
![Image alt](https://github.com/maggiemmae/lab_1/blob/master/epoch_categorical_accuracy%201.svg)
![Image alt](https://github.com/maggiemmae/lab_1/blob/master/epoch_loss%201.svg)
  
b.batch_size = 16

        tf.keras.models.Sequential([
        tf.keras.layers.Input(shape=(224,224,3)),
        tf.keras.layers.Conv2D(filters=8, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Conv2D(filters=8, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Flatten(),
        tf.keras.layers.Dense(NUM_CLASSES, activation=tf.keras.activations.softmax)

![Image alt](https://github.com/maggiemmae/lab_1/blob/master/epoch_categorical_accuracy%202.svg)
![Image alt](https://github.com/maggiemmae/lab_1/blob/master/epoch_loss%202.svg)

2.Добавление сверточного слоя

        tf.keras.models.Sequential([
        tf.keras.layers.Input(shape=(224,224,3)),
        tf.keras.layers.Conv2D(filters=8, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Conv2D(filters=8, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Conv2D(filters=8, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Flatten(),
        tf.keras.layers.Dense(NUM_CLASSES, activation=tf.keras.activations.softmax)

![Image alt](https://github.com/maggiemmae/lab_1/blob/master/epoch_categorical_accuracy%204.svg)
![Image alt](https://github.com/maggiemmae/lab_1/blob/master/epoch_loss%204.svg)

3.Изменение количества сверток в сверточных слоях

        tf.keras.models.Sequential([
        tf.keras.layers.Input(shape=(224,224,3)),
        tf.keras.layers.Conv2D(filters=16, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Conv2D(filters=16, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Conv2D(filters=16, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Flatten(),
        tf.keras.layers.Dense(NUM_CLASSES, activation=tf.keras.activations.softmax)
 
![Image alt](https://github.com/maggiemmae/lab_1/blob/master/epoch_categorical_accuracy%205.svg)
![Image alt](https://github.com/maggiemmae/lab_1/blob/master/epoch_loss%205.svg)
       

4.Добавление сверточного слоя
        
        tf.keras.models.Sequential([
        tf.keras.layers.Input(shape=(224,224,3)),
        tf.keras.layers.Conv2D(filters=16, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Conv2D(filters=16, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Conv2D(filters=16, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Conv2D(filters=16, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Flatten(),
        tf.keras.layers.Dense(NUM_CLASSES, activation=tf.keras.activations.softmax)
        
![Image alt](https://github.com/maggiemmae/lab_1/blob/master/epoch_categorical_accuracy%206.svg)
![Image alt](https://github.com/maggiemmae/lab_1/blob/master/epoch_loss%206.svg)

5.Изменение количества сверток в сверточных слоях

       tf.keras.models.Sequential([
        tf.keras.layers.Input(shape=(224,224,3)),
        tf.keras.layers.Conv2D(filters=32, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Conv2D(filters=32, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Conv2D(filters=32, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Conv2D(filters=32, kernel_size=3),
        tf.keras.layers.MaxPool2D(),
        tf.keras.layers.Flatten(),
        tf.keras.layers.Dense(NUM_CLASSES, activation=tf.keras.activations.softmax)
 
 ![Image alt](https://github.com/maggiemmae/lab_1/blob/master/epoch_categorical_accuracy%207.svg)
![Image alt](https://github.com/maggiemmae/lab_1/blob/master/epoch_loss%207.svg)
        
