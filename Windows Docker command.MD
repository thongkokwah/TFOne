H1 Command Used
---------------
'''
docker run --gpus all -it --rm tensorflow/tensorflow:latest-gpu python -c "import tensorflow as tf; print(tf.reduce_sum(tf.random.normal([1000, 1000])))"
'''
'''
docker run -v c:\code:/code --gpus all -it --rm tensorflow/tensorflow:latest-gpu bash
'''
'''
docker run -v c:\code:/code --gpus all -it --rm tensorflow/tensorflow bash
'''