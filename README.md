# Representation Engineering Papers

A curated list of papers and repositories implementing representation engineering techniques for large language models.

## Methods

### Linear Contrastive Steering Vector Methods
Papers that use linear methods with fixed intervention strength:

- [LM-Truthfulness](https://github.com/lingo-mit/lm-truthfulness) - Analyzing truthfulness in language models using representation engineering
- [Contrastive Activation Addition (CAA)](https://github.com/nrimsky/CAA) - Steering model behavior through contrastive activation differences
- [Activation Addition (ActAdd)](https://github.com/TeunvdWeij/extending-activation-addition) - Simple activation steering using single contrastive pairs
- [Affine Steering](https://github.com/shauli-ravfogel/affine-steering) - Affine transformations for steering model representations
- [Activation Steering](https://github.com/cma1114/activation_steering) - General activation steering techniques
- [Parsimonious Concept Engineering (PaCE)](https://github.com/peterljq/Parsimonious-Concept-Engineering) - Efficient concept engineering through sparse coding

### Dynamic Strength Methods
Papers that adjust intervention strength during inference:

- [SADI](https://github.com/weixuan-wang123/SADI) - Semantic-Adaptive Dynamic Intervention
- [Activation Scaling](https://github.com/niklasstoehr/activationScaling) - Dynamic scaling of activation patterns
- [RE-Control](https://github.com/Lingkai-Kong/RE-Control) - Control theory based representation editing
- [Dynamic Activation Composition](https://github.com/DanielSc4/Dynamic-Activation-Composition) - Composing multiple activation patterns dynamically

### Multiple Model Methods
Papers that leverage multiple models for representation engineering:

- [ConTrans](https://github.com/willowdong/ConTrans) - Concept transfer between models
- [KL-Then-Steer](https://github.com/AsaCooperStickland/kl-then-steer) - KL divergence based steering
- [InferAligner](https://github.com/Jihuai-wpy/InferAligner) - Alignment through inference time interventions

### Sparse Autoencoder Methods
Papers using sparse autoencoders for representation identification:

- [SAE-TS](https://github.com/slavachalnev/SAE-TS) - SAE-targeted steering
- [SV Interpretability](https://github.com/HarryMayne/SV_interpretability) - Interpretability through sparse vectors

### Fine-tuning Alternatives
Papers providing alternatives to traditional fine-tuning:

- [PyREFT](https://github.com/stanfordnlp/pyreft) - Python Representation Fine-Tuning
- [PyVENE](https://github.com/stanfordnlp/pyvene) - Python interventions framework

### Other Approaches
Novel and hybrid approaches:

- [Conceptor Steering](https://github.com/jorispos/conceptorsteering) - Steering using conceptor matrices
- [Steering Vectors](https://github.com/nishantsubramani/steering_vectors) - General steering vector implementations
- [REPE Alignment](https://github.com/dorin133/REPE_alignment_helpfulness_tradeoff) - Alignment-helpfulness tradeoff analysis
- [SCAV](https://github.com/SproutNan/AI-Safety_SCAV) - Safety concept activation vectors
- [Adversarial RE](https://github.com/Zhang-Yihao/Adversarial-Representation-Engineering) - Adversarial approaches to representation engineering
- [REEF](https://github.com/AI45Lab/REEF) - Representation engineering framework
- [Honest LLaMA](https://github.com/likenneth/honest_llama) - Improving model honesty through representations
- [Probing LLaMA](https://github.com/Jometeorie/probing_llama) - Probing techniques for LLaMA models
- [Function Vectors](https://github.com/ericwtodd/function_vectors) - Vector-based function manipulation

## Contributing

Feel free to submit pull requests to add new papers and repositories related to representation engineering.

## License

This repository list is provided for research purposes.
