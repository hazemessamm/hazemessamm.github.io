---
layout: post
title: "My Open Source Contributions"
categories: misc
---

1. My first contribution was adding an example to [keras.io](https://keras.io/examples/vision/siamese_network/), despite not knowing how to contribute or what to add to a library. I found an issue in the Keras repo suggesting examples to add to keras.io, so I picked one and worked on it. I wanted to add more than just examples, I wanted to implement a feature.
2. My second contribution was adding an audio utility function to [Keras](https://github.com/keras-team/tf-keras/blob/master/tf_keras/utils/audio_dataset.py), this contribution was really exciting because it was my first time to add a feature. I was hesitant at first because I kept thinking about what if my implementation sucks and I did not want to be in a situation where my implementation is not good enough to be accepted, but I submitted it anyway and I found that my thoughts were completely wrong and I learned a lot from this contribution and gained more confidence.
3. Ported `CategoryEncoding` from Keras to [Keras Core](https://github.com/keras-team/keras-core/blob/main/keras_core/layers/preprocessing/category_encoding.py) and updated test cases
4. Fixed bug in `Concatenate` in [Keras Core](https://github.com/keras-team/keras-core/blob/main/keras_core/layers/merging/concatenate.py)
5. Added ALiBi positional encoding in [MLX](https://github.com/ml-explore/mlx/blob/main/python/mlx/nn/layers/positional_encoding.py#L176)
6. Added Scaling configuration in RoPE in [MLX](https://github.com/ml-explore/mlx/blob/main/python/mlx/nn/layers/positional_encoding.py#L42)
7. Added GLU activation function in [MLX](https://github.com/ml-explore/mlx/blob/main/python/mlx/nn/layers/activations.py#L166)

What I learned:

* How to make your first contribution:
    1. If you do not have ideas in your mind to add to a specific library you want to contribute to, filter the issues by labels like `contributions-welcome` or something similar. This will help you find open issues that welcome contributions.
    2. If you don't find any relevant labels in the issues, check the repository for a file called `CONTRIBUTING.md`. This file might contain links to files that list missing features you can work on.
    3. You can also look for pinned issues, which may also contain missing features.
    4. Keep an eye on latest tools/ideas that could be part of the tool you want to contribute to. (I found a PR in MLX that integerates GGUF into MLX.)
* Follow the guidelines, naming conventions, and add unit tests to your implementation. The code review process will reveal any areas for improvement, so don't worry about perfection right now. You'll learn a lot from the feedback you receive.
* You'll gain deeper insights into the tool you're contributing to, including its design and limitations. These insights can help you generate new ideas for further contributions or enhance your usage of the tool in your work.
* Code review process will teach you a lot: you will talk to nice folks who are experts in your field, you will learn from them how to do code review properly, cool tricks, what to care about in implementation and so on.
* Sharing your contributions might help you to get to know folks and work with them on interesting projects.
