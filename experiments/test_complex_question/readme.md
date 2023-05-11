# Summary of the Experiment.

Becaues I don't have API access to GPT4, my experiment is based on GPT3.5

In the experiment, I did the following tests with results

### Test 1 
- Called SparkSQL Agent with a complex question.
- GPT3.5 provided a query which triggered Spark AnalysisException (missing_group_by). 
- details in gpt35turbo_not_able_to_use_group_by.ipynb

### Test 2
- Called GPT3.5 directly to confirm if it's an agent conv issue or GPT3.5 issue.
- GPT3.5 couldn't provide a correct answer after providing a feedback.
- details in gpt35turbo_manual_test.ipynb

### Test 3
- Called GPT4 to optimize GPT3.5 ansewr.
- Result worked.
- details in ask_gpt4_to_optimize_for_gpt3.5_answer.ipynb

### Test 4
- Called GPT to answer this question.
- GPT4 provided a correct answer. I further requested an optimization. It also provided an answer.
- gpt4_manual_test.ipynb

## Test 5
- TODO: I would like to change agent to GPT-4 and repeat this test, but I don't have GPT-4 API access...

## Next Step
- TODO: I want to find a question which can't be answered with 1 single SQL.
