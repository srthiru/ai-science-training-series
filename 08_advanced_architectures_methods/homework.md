How could you use AI for a problem that interests you?
I would like to work on fine-tuning Large language models to perform some downstream natural language processing tasks.


What is the task?
One such task is commonsense reasoning.


What kind of data would you use?
I recently came across a recently released benchmark that is well suited for this type of task - https://arxiv.org/pdf/2210.01241.pdf. 


What kind of method or model might be appropriate?
One potential model is to use a reinforcement learning method to train a language model that was pre-trained in a supervised fashion.
The above benchmark also provides a reinforcement learning environment for language tasks that can be used to train this type of models.


What kind of metric would you use to measure success?
Since the reasoning task boils down to text generation, one common metric used is BLEU scores.
