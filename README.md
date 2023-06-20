# Tensor-Flow-Basic-operations
TensorFlow is an open-source machine learning framework developed by Google. It provides a comprehensive ecosystem of tools, libraries, and resources for building and deploying machine learning models. In TensorFlow, the fundamental building block is the tensor, which is an n-dimensional array of numerical values.
Tensors: Tensors are the primary data structure in TensorFlow. They represent multi-dimensional arrays of numerical values. Tensors can have different ranks (number of dimensions) such as scalar (rank-0), vector (rank-1), matrix (rank-2), or higher-order tensors. TensorFlow operations are performed on tensors.

In TensorFlow, the concept of rank refers to the number of dimensions of a tensor. It indicates how many indices are required to access or refer to a specific element within the tensor. Here are the common ranks used in TensorFlow:

Rank-0: Rank-0 tensors are scalar values, representing a single element. They don't have any dimensions. For example, a rank-0 tensor can be a single number like 5 or 3.14.

Rank-1: Rank-1 tensors are vectors, representing a one-dimensional array of values. They have a single dimension. For example, [1, 2, 3] or [0.1, 0.2, 0.3] are rank-1 tensors.

Rank-2: Rank-2 tensors are matrices, representing a two-dimensional array of values. They have two dimensions, usually denoted as rows and columns. For example, [[1, 2], [3, 4]] or [[0.1, 0.2], [0.3, 0.4]] are rank-2 tensors.

Rank-3: Rank-3 tensors have three dimensions. They can be thought of as a collection of matrices stacked along a third dimension. For example, [[[1, 2], [3, 4]], [[5, 6], [7, 8]]] is a rank-3 tensor with two matrices.

Higher Ranks: TensorFlow supports tensors with higher ranks as well. These tensors have more than three dimensions. They can represent multi-dimensional arrays or volumes of data. For example, an RGB image can be represented as a rank-3 tensor with shape (height, width, channels).

In general, the rank of a tensor determines the number of indices needed to access a specific element within the tensor. Higher-rank tensors enable the representation of more complex data structures and are commonly used in machine learning applications.






