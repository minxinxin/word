Chinese Word Segmentation Component


分词使用方法：


    List<Word> words = WordSeg.seg("杨尚川是APDPlat应用级产品开发平台的作者");
    System.out.println(words);
    
    输出：
    [杨尚川, 是, APDPlat, 应用, 级, 产品开发, 平台, 的, 作者]



分词算法文章：

    
   [1、中文分词算法 之 基于词典的正向最大匹配算法](http://yangshangchuan.iteye.com/blog/2031813)
    
   [2、中文分词算法 之 基于词典的逆向最大匹配算法](http://yangshangchuan.iteye.com/blog/2033843)
    
   [3、中文分词算法 之 词典机制性能优化与测试](http://yangshangchuan.iteye.com/blog/2035007)