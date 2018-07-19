# test_git
test lsh
插入时，返回与该条数据相似的数据id的list
当插入数据的id小于0时，实际 不插入。相当于查询。只返回相似数据的id
假设有n个bands则分配n快cache，每个cache下面有若干bucket桶。

汉明距离的LSH原理：https://www.jianshu.com/p/e6af33fd8e27

simhash实现原理：http://www.lanceyan.com/tech/arch/simhash_hamming_distance_similarity2-html.html

LSH实现原理较详细：https://blog.csdn.net/sinat_26917383/article/details/52451028

simhash用来意图搜图：https://blog.csdn.net/sinat_26917383/article/details/70287521
