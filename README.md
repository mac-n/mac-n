# Niamh McCombe

Independent AI researcher, Northern Ireland. PhD in machine learning (Ulster University, Intelligent Systems Research Centre). Website: **[glassnest.ai](https://glassnest.ai)**

### Current work

**[Reward hacking is largely a property of the scaffold](https://github.com/mac-n/scaffold-effect)** · [write-up](https://glassnest.ai/scaffold/)
Same model, same 103 unsatisfiable coding tasks, same prompt: 63% cheating inside ImpossibleBench's own agent scaffold, 2% inside an ordinary coding agent. Persistence after a failed submission is the trigger. Data, harness and analysis scripts in the repo; every number recomputes from the CSVs.

**[Embodied cognition in transformers](https://github.com/mac-n/lakoff-schemas-in-transformers)** · [findings as slides](https://glassnest.ai/embodied/) · [full write-up](https://mac-n.github.io/lakoff-schemas-in-transformers/)
Lakoff image schemas (UP-DOWN, BALANCE, FORCE…) recovered from single-token activations in Pythia, GPT-2 and Llama. Steering along UP makes the model happier. Inflectional morphology organises itself around the schema axes in the transformer but not in GloVe or word2vec, so the schema system is learned, not copied from word statistics. BALANCE is coupled to the model's own computation: residual norm in Pythia, attention entropy in GPT-2 and Llama. Every script, raw output, pre-registration and lab notebook is in the repo, including the failures.

**[GLAS](https://glassnest.ai/glas/)**
A transparent-by-construction language model: a tree of specialists competing on prediction error instead of an attention stack. Beats a parameter-matched transformer at 100K and 1M parameters on character-level Shakespeare. Working on how to scale it.

### Earlier
Applied machine learning for dementia diagnosis (missing-data imputation, graph neural networks, assessment optimisation): [Google Scholar](https://scholar.google.com/citations?user=2xniZZAAAAAJ).
