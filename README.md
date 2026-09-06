Transformer Made Simple (draft)
===============================

 * The scaled dot-product attention mechanism of the
   [Transformer architecture](https://doi.org/10.48550/arXiv.1706.03762)
   is mathematically equivalent to an ordinary
   [MLP](https://en.wikipedia.org/wiki/Multilayer_perceptron) with a
   [softmax](https://en.wikipedia.org/wiki/Softmax_function)
   activation that is evaluated on the products of input matrices.

 * The [ReLUFormer architecture](https://doi.org/10.48550/arXiv.2302.06461)
   replaces softmax with ReLU and achieves similar or even better performance
   than the vanilla Transformer.

 * Preliminary experiments: WIP

[See the full write-up and the notebook with the code here](https://attilammagyar.github.io/transformer-made-simple/).
