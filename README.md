# leecode_training


1.两数之和(Python)
1.1 捕捉list.index()方法的异常
    target_index = source_list.index(target_num) if target_num in source_list else -1 #
1.2 获取list中指定元素的索引
    source_list.index(target_num)
    enumerate(source_list) # this method could let type of source_list from list to tuple which like [(0,sub_num0),(1,subword1)]
    
838. 推多米诺
在设计同一时刻并行执行的事件时，使用广度优先搜索树。用一个队列来模拟事件执行的过程。
