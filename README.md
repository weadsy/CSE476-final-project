# CSE476-final-project
CSE 475 final project

Agent implementation is in the model_eval.ipynb file.

To use the agent simply scroll to the bottom and find the Agent Loop section.

Try different tests with this this line

test_prompts = get_tests(n=1, seed=rng, test_type=["planning"])

n=random sampled tests, test_type for the domain (can do multiple), or dont use n and use char boundaries to slice tests. Can also set n=-1 and no test_type to get a random sample of tests from each domain.
