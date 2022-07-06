# kaggle-Titanic
Machine learning prediction for binary classification

Using Artificial Neural Network

## ANN architecture
### Layers
`tf.keras.layers.Dense(16, activation='relu', input_shape=[len(X_train[0])]),`
`tf.keras.layers.Dense(16, activation='relu'),`
`tf.keras.layers.Dense(1, activation='sigmoid')`

## Optimizer
`optimizer='adam', loss=tf.keras.losses.BinaryCrossentropy(from_logits=False), metrics=['accuracy']`

Since this is binary classifier, we using BinaryCrossentropy losses

`epochs=200`
`batch_size=100`
