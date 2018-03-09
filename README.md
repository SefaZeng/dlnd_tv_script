# dlnd_tv_script
电视剧剧本生成

tensorflow版本为1.4
在Build RNN Cell and Initialize和Build_Neural Network模块中出现问题，主要是函数tf.contrib.rnn.MultiRNNCell和tf.nn.dynamic_rnn。
出现过提示变量类型不对，维度不对等问题。查阅github上部分代码，因为基本相同没能解决问题。
猜测是tensorflow的版本更新带来的问题。
