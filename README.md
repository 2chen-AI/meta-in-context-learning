# Meta-in-context learning in large language models. Preprint available [here](https://arxiv.org/pdf/2305.12907.pdf).

**Abstract:** Large language models have shown tremendous performance in a variety of tasks.  In-context learning  -- the ability to improve at a task after being provided with a number of demonstrations -- is seen as one of the main contributors to their success. In the present paper, we demonstrate that the in-context learning abilities of large language models can be recursively improved via in-context learning itself. We coin this phenomenon \emph{meta-in-context learning}. Looking at two idealized domains, a one-dimensional regression task and a two-armed bandit task, we show that meta-in-context learning adaptively reshapes a large language model's priors over expected tasks. Furthermore, we find that meta-in-context learning modifies the in-context learning strategies of such models. Finally, we broaden the scope of our investigation to encompass two diverse benchmarks: one focusing on real-world regression problems and the other encompassing multiple NLP tasks. In both cases, we observe competitive performance comparable to that of traditional learning algorithms. Taken together, our work improves our understanding of in-context learning and paves the way toward adapting large language models to the environment they are applied purely through meta-in-context learning rather than traditional finetuning.

**Usage:** The Four folders represent the four experiments in the paper. Each folder contains a README.md file with instructions. One thing to note is that each folder has an llm() function which is imported from a utils.py script. This function has to be adapted to the user's own evaluating llm function (for now they are set to a random agent). 