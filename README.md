# dllmdx
Exploring multivariable calculus math on LLMs.

## here is an idea
LLM is a function that takes a vector as an input and outputs a vector. It is a vector function. Now, for a large anough ammount of tokens it is approx a smooth vector function meaning we can calculate all sorts of math and derivatives on it.

Imagine that: an LLM that generates tokens essentially draws a line in a latent space that twists and turns is different directions. It would be interesting to see how fast and in what directions is it going to turn given a change in input vectors (dLLM/dx). What is there are some consistent patterns? Like, if an LLM sees a grammar error is twitches somehow, or if we change subject it turns gerenation in the fature direction of that subject.

What is more interesting, what if we look at those lines generated at the different depths of LLM (different encoding spaces, different layers) and turning/twitching patterns refer to sertain "decisions" that LLM makes in its sub-latent spaces and those decision hyperposed/or applied sequentially result in sertain outputs.

What if there is a layer that "notices" an adversarial intervention that we can observe? (see (Eliciting Latent Knowledge)[https://www.lesswrong.com/posts/qHCDysDnvhteW7kRd/arc-s-first-technical-report-eliciting-latent-knowledge?ref=forourposterity.com])
