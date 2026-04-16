# Math for AI — Week 2

- **Matrix multiplication**: every neural network forward pass is W @ x + b,
  repeated across layers. NumPy is ~1000x faster than pure Python loops.

- **Naive Bayes**: Bayes' theorem applied per-word, with log probabilities
  to avoid underflow. Works surprisingly well with tiny training data.

- **Central Limit Theorem**: no matter how skewed or weird your source
  distribution is, sample means always become normal as n grows.
  This is why normal distributions appear everywhere in AI.
