# Location_based-AttentionWrapper
The code is the impletement of Location-based Attention.

When using Location-based Attention, just replace "attention_wrapper.py" for the file with the same name in tensorflow.


The second version <attention_wrapper.py(for tf version later than 1.8)> is for the later tf versions since “_like_rnncell” is instead by “assert_like_rnncell” in “tensorflow.python.ops.rnn_cell_impl”. The difference of these two version is shown in line 1209.
