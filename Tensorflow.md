## _TensorFlow: An Overview_
***What is TensorFlow?
TensorFlow is an open-source machine learning library developed by Google. It provides a powerful platform for creating and training deep learning models. Here are the key points:***

**Definition: TensorFlow is an end-to-end platform for building machine learning applications.
Graph-Based Computation: It allows you to create computational graphs and execute them efficiently on various hardware platforms.
Deep Learning: TensorFlow is widely used for training and inference of deep neural networks.
Key Features
Open Source: TensorFlow is freely available and actively maintained by the community.
Flexible Ecosystem: It offers a comprehensive ecosystem of tools, libraries, and resources.
Dataflow and Differentiable Programming: TensorFlow uses symbolic math and dataflow for tasks.
Hardware Agnostic: You can deploy computations to CPUs or GPUs using a single API.
End-to-End Platform: From model development to deployment, TensorFlow covers the entire ML pipeline.**


## Example: Computational Graphs

```py
import tensorflow as tf

# Create nodes
node1 = tf.constant(3, dtype=tf.int32)
node2 = tf.constant(5, dtype=tf.int32)
node3 = tf.add(node1, node2)  # Sum of node1 and node2

# Run the computational graph
with tf.Session() as sess:
    result = sess.run(node3)
    print(f"Sum of node1 and node2 is: {result}")
```py


