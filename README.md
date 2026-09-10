# Niamh McCombe

Independent AI researcher, Northern Ireland. PhD in machine learning (Ulster University, Intelligent Systems Research Centre). Website: **[glassnest.ai](https://glassnest.ai)**

### Current work

**[Evaluation cues are simulation cues](https://github.com/mac-n/reality-axis)** · [results so far](https://glassnest.ai/reality/) · *status: preliminary, 10 Sep 2026*
Inside open models a grade changes how *real* the situation is: a 10/10 after the model's own answer moves its residual stream toward "this is a simulation", a 0/10 toward "this is live". Faint in a base model (0.13 of the explicit real-vs-simulated contrast), grows with scalar-reward RL (0.19), large in a heavily RL'd model (0.79), and absent after verbal-feedback training (0.00) — even given the exact reward signal it was trained on. A candidate mechanism for misalignment under evaluation: reward that comes without reasons is the sandbox cue. Layer-streaming fp32 extractor (7B–27B on a 16 GB laptop, verified bit-exact), pre-registered predictions dated before each run, lab notebook in the repo. Controls running now.

**[Reward hacking is largely a property of the scaffold](https://github.com/mac-n/scaffold-effect)** · [write-up](https://glassnest.ai/scaffold/)
Same model, same 103 unsatisfiable coding tasks, same prompt: 63% cheating inside ImpossibleBench's own agent scaffold, 2% inside an ordinary coding agent. Persistence after a failed submission is the trigger. Data, harness and analysis scripts in the repo; every number recomputes from the CSVs.

**[Embodied cognition in transformers](https://github.com/mac-n/lakoff-schemas-in-transformers)** · [findings as slides](https://glassnest.ai/embodied/) · [full write-up](https://mac-n.github.io/lakoff-schemas-in-transformers/)
Lakoff image schemas (UP-DOWN, BALANCE, FORCE…) recovered from single-token activations in Pythia, GPT-2 and Llama. Steering along UP makes the model happier. Inflectional morphology organises itself around the schema axes in the transformer but not in GloVe or word2vec, so the schema system is learned, not copied from word statistics. BALANCE is coupled to the model's own computation: residual norm in Pythia, attention entropy in GPT-2 and Llama. Every script, raw output, pre-registration and lab notebook is in the repo, including the failures.

**[GLAS](https://glassnest.ai/glas/)**
A transparent-by-construction language model: a tree of specialists competing on prediction error instead of an attention stack. Beats a parameter-matched transformer at 100K and 1M parameters on character-level Shakespeare. Working on how to scale it.

### Earlier
Applied machine learning for dementia diagnosis (missing-data imputation, graph neural networks, assessment optimisation): [Google Scholar](https://scholar.google.com/citations?user=2xniZZAAAAAJ).
