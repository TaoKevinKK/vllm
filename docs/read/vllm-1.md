1. llm = LLM(model="facebook/opt-125m")
    # 实例化一个LLM对象，并加载指定模型, LLMEngine对象.
    # 初始化tokenizer, detokenizer, tokenizer_group对象.
    
2. outputs = llm.generate(prompts, sampling_params)
    # 调用LLM对象的generate方法，生成推理结果
3. for output in outputs:
    # 遍历推理结果
    # 对每一条prompt，打印其推理结果

1. 关于模型推理的采样超参数的介绍：



