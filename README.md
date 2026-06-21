Simply paste the code into kaggle, add your HF key through the "secrets" feature or pasting it in place of "your_hf_token_here".
Generation should take between 15 seconds and 4 minutes depending on task length

This is a rough draft based on ~30 hours of testing.
It seems to work on models between 1.5B and 9B with 64-128 token outputs just fine, anything else hasn't been tested in any moderately formal way.
Scaling of performance seems linear up to 6 candidates, I may do more aggressive scaling tests in the future.
I offer this for free with no expectation of credit, not just because I believe in Open Source, but because I'm not sure if this has been done before.

Future versions may include an aggregator and disagreement based filtering (something Open Router already offers) to enhance selection.
The method of uncertainty measurement and candidate selection may change in the future, as I've found seemingly better designs already.
