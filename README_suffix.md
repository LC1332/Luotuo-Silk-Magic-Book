## 鲁鲁's Discussion

+ 为什么会叫魔法书： 召唤魔法的说法，来源于李鲁鲁之前混Stable Diffusion社区的时候，他们会把CLIP的生成词叫做魔法，其实特指召唤魔法。我觉得非常贴切，你就想想在最终喊出"诸葛亮拳打镇三关"之前，你需要吟唱一大串魔法的起手势，然后才会大喊出最终的目标句子，这样ChatGPT或者文心一言就会乖乖为你生成句子。

+ 魔法与炼金：这么说来，其实给模型调整超参数的同学，我们一般会被称之为炼金术士，这样AI魔法界的世界观又被进一步补全了。

+ 那么进一步说，p-tuning或者prefix-tuning，可能是最终生成了一个法器，使得巨大的魔法式可以快速启动。

+ 关于这些超级任务的提示语(prompt)，你可以这么理解： 最简单的提示语，比如"请为我总结下面的文本:"，"请为我翻译成英语"，一般来说，较小的模型我们观察到只能进行简单的提示语启动。显然，更大的模型可以容纳更多的任务。当模型学会很多任务的提示语的时候，也自然可以学会一些提示语的组合任务，比如用灼眼的夏娜的语气说林黛玉的台词，完全是可以的。

+ 但是尽管知道这些知识，我仍然认为AIPRM这些prompt的构造者非常可怕，他们执行的事情非常像人工在进行p-tuning，并且效果甚至是超越了训练的。因为你使用训练的方式来做，X->Y的文本会限制输出的空间，而人工调整的过程，有点像RLHF的p-tuning，真的很强，为这些古召唤魔法师们致敬。

+ 那这么说来，我要做的就是把这些上古召唤魔法师的法典记录下来。

+ 当我无意之中，把这些召唤魔法翻译成中文，再输入到文心，发现居然能用的时候(第一个SOE的例子)，我是非常惊喜的。这种惊喜就好像你穿越到异世界发现原来异世界的魔法只不过是吟唱你已经掌握的一门二外（我也不知道我上一句句子在说啥）。所以我决定写下这个repo来记录这个现象。

+ 从某些方面来说，文心是个很不错的模型，我暂时没有在其他模型上观察到这样的现象。我暂时还没有将骆驼项目推进到超多任务prompt的训练中。但是希望有这么一天，我的模型也会响应我的超大规模召唤魔法！

+ 从某些方面来说，这些超长prompt已经在逼近GPT和文心的能力边界（当然从别的角度还有别的边界）是个很有意思的现象。

+ 当我前面提到人工爬取的时候，我拜托了我的老婆，在这里对她表示巨大的感谢，特别是她在运维整个项目的时候也给予了很大的支持。另外这里文心的账号使用了老婆的邀请码，老婆也在为她们公司调研使用文心的可能性，我注意到文心页面对我的截图是留有显著的水印的，希望百度的大佬们不要反查图像给我账号封了，不然也未免太小器了。

TODO: add an English translation here.

## Sponsorship(赞助) for Proj Luotuo

如果你有兴趣赞助骆驼项目，请点击[主项目](https://github.com/LC1332/Luotuo-Chinese-LLM)或者查看[赞助表单](https://github.com/LC1332/Luotuo-Chinese-LLM/blob/main/data/Sponsorship_and_balance.md)

If you are interested in sponsoring the [Luotuo Project](https://github.com/LC1332/Luotuo-Chinese-LLM), please click on the [major project](https://github.com/LC1332/Luotuo-Chinese-LLM) or view the [sponsorship form](https://github.com/LC1332/Luotuo-Chinese-LLM/blob/main/data/Sponsorship_and_balance.md).

## Citation

Please cite the repo if you use the data or code in this repo.

```
@misc{alpaca,
  author={Ziang Leng, Qiyuan Chen and Cheng Li},
  title = {Luotuo: An Instruction-following Chinese Language model, LoRA tuning on LLaMA},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/LC1332/Luotuo-Chinese-LLM}},
}
```
