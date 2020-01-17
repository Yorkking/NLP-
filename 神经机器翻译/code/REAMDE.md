# NLP神经机器翻译模型

文件目录如下：

> ./
>
> > code/
> >
> > > main.py：主函数，用于训练模型，以及在测试集上进行预测，并计算BLEU结果。
> > >
> > > module.py：构建的神经网络模型文件，有三个模型：EncoderRNN, DecoderRNN, AttentionRNN.
> > >
> > > pre_process_data.py: 预处理数据的代码：主要是对中文进行分词，并且生成源语言句子和目标语言句子的两个词典。
> > >
> > > prepare_data.py：准备训练数据的代码，把要训练的句子进行词序列化。
> >
> > data/
> >
> > > 各类产生的文件



运行代码环境依赖：

>python3.6+
>
>pytorch+cuda环境
>
>依赖包：jieba, numpy, ntlk, matplotlib

运行：在code目录下，终端下，有以下几种输入方式

```bash
python main.py 

```