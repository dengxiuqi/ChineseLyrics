# ChineseLyrics 中文歌词数据库
##### 10W+首歌词数据, 给做NLP和数据分析领域的朋友们提供参考  
基于此数据库做了两个歌词生成器  
tensorflow版本: https://github.com/dengxiuqi/Lyricist-tensorflow  
pytorch版本: https://github.com/dengxiuqi/Lyricist-torch  

#### 项目简介
通过网络收集整理的中文歌词数据库, 包含:  
* 绝大多数华语歌手在2019年之前的歌曲  
* `4019`位歌手, 其中作品数20首以上的`1086`人, 100首以上`233`人  
* `102197`首歌曲, 平均每人`25.4`首歌

#### 格式简介
* 10W+首歌被分别记录在5个json文件中
* 歌词数据已按歌手进行聚类, 并根据作品数量降序排列  
`name`: 歌名  
`singer`: 歌手名  
`lyric`: 歌词  

#### 词频统计
* `data/words.json`: 将所有歌词的词频排序  
* `data/first_words.json`: 将用作句子开头的词语按词频排序
* `data/rhymes.json`: 根据统计得到的拼音押韵表

仅供学习交流使用!