# MultiSenseDetection
MultiSenseDetection, chinese multi-wordsense disambiguation based on online bake knowledge base and semantic embedding similarity compute,基于百科知识库的中文词语多义项获取与特定句子词语语义消歧. 





# 项目结构




# 项目思路







# 项目效果
python wordsense_detect.py,运行中文词语语义消歧脚本.  
1, 指定需要进行词义消歧的词语word  
2, 指定需要极刑词义消歧词语所在的句子  

例子:

    enter an sent to search:苹果发布新产品了
    enter an word to identify:苹果
    sent_embedding_res:
    [('公司', 0.4309597564421702), ('物品', 0.39608141793731144), ('歌曲', 0.37937766923800026)]
    wds_embedding_res:
    [('歌曲', 0.37504538578806157), ('果树', 0.3572757418314274), ('物品', 0.3479904634206044)]
    ****************************************************************************************
    enter an sent to search:最近连降大雨,种苹果的果农损失惨重
    enter an word to identify:苹果
    sent_embedding_res:
    [('角色', 0.23535153116801097), ('果树', 0.22943442305363207), ('歌曲', 0.21173595044037458)]
    wds_embedding_res:
    [('物品', 0.24051958779817326), ('人物', 0.20978448328069915), ('果树', 0.20251385230085645)]
    ****************************************************************************************
    enter an sent to search:小米上市了
    enter an word to identify:小米
    sent_embedding_res:
    [('公司', 0.3901701093980004), ('主角', 0.365504574048325), ('母亲', 0.29381689724140836)]
    wds_embedding_res:
    [('公司', 0.4342258273055104), ('动物', 0.3777650235830843), ('精灵', 0.35332623481158437)]
    ****************************************************************************************
    enter an sent to search:小米和玉米放在一起煮粥会很好吃
    enter an word to identify:小米
    sent_embedding_res:
    [('特色小吃', 0.5558542842056945), ('草本', 0.4466804204905287), ('犬', 0.291238012852016)]
    wds_embedding_res:
    [('特色小吃', 0.3718067960513453), ('草本', 0.26636323574527104), ('犬', 0.20866931168592512)]
    ****************************************************************************************
    enter an sent to search:小辣椒开花了,很好看
    enter an word to identify:小辣椒
    sent_embedding_res:
    [('茄科', 0.4904365572878336), ('植物', 0.2402877631447203), ('品牌', 0.10335075207027959)]
    wds_embedding_res:
    [('茄科', 0.5541452367707211), ('植物', 0.2990925606278592), ('角色', 0.19372604287529646)]
    ****************************************************************************************
    enter an sent to search:小辣椒,三星,苹果都是特别畅销的手机品牌
    enter an word to identify:小辣椒
    sent_embedding_res:
    [('品牌', 0.7590410310876141), ('歌曲', 0.5101141696340716), ('女友', 0.4695221792163845)]
    wds_embedding_res:
    [('品牌', 0.5786736513059438), ('植物', 0.407433638956153), ('角色', 0.34862850174224996)]
    ****************************************************************************************

# 总结
