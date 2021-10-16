# skipgram
word2vec模型代码复现

1.读取训练文本，创建字典vocab
2.初始化网络参数（syno,syn1）
3.根据训练模式，初始化Huffman树(hir)或用于negative采样的unigram表
4.调用多线程运行train_process,使用_init_process初始化线程
5.保存训练好的模型参数到syno
