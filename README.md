# machine-translation
基于Seq2Seq、Global attention、Transformer的中英文翻译

## 中英文数据集：http://www.manythings.org/anki/
选择英文-中文的翻译句子对,英文按照空格分词，中文按照字粒度分词;目的只要是为了在PC上跑通模型，因此只选择1000条数据集来进行训练

## 数据实例
    I try.-让我来。
    I won!-我赢了。
    Perfect!-完美！
    
## 依赖
* Python3.6
* Tensorflow 1.9.0
    
## License
[MIT LICENSE](LICENSE)
