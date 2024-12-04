  - `step1_train()`：加载预训练模型并开始训练。
  
   - `step2_Constraint_train()`：在约束条件下进行训练，例如可能涉及到正则化或其他约束条件。
   
   - `step3_pruning()`：使用自定义的`do_pruning`函数对模型进行剪枝，以减少模型的复杂度。
   
   - `step4_finetune()`：微调剪枝后的模型。
   
   - `step5_distillation()`：使用知识蒸馏技术，将一个训练好的大模型（教师模型）的知识传递给一个较小的模型（学生模型）。
