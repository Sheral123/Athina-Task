# AthinaAI-Task

Dataset Construction:
Thought Process:
Understanding Data Needs:
To construct a dataset for training and evaluating our question-answering chatbot, we needed pairs of questions and their corresponding answers.
The dataset should cover various topics and questions relevant to the domain of the chatbot.
Data Collection:
Collected question-answer pairs from multiple sources:
Existing Q&A datasets available online (e.g., insurance FAQs, product manuals, etc.).
Customer support logs or chat transcripts.
Company documentation, policies, or FAQs.
Dataset Preprocessing:
Cleaned the collected data by removing duplicates, irrelevant entries, and noise.
Ensured the dataset covers a diverse range of questions and answers to provide a comprehensive evaluation.
Formatting Data:
Organized the data into a structured format, typically a DataFrame with columns for "Query" and "Response".
Dataset Split:
Split the dataset into training, validation, and test sets to train the model, tune hyperparameters, and evaluate performance.
Evaluation Metric Selection:
Thought Process:
Understanding Evaluation Needs:
We needed metrics that reflect different aspects of the chatbot's performance, including correctness, fluency, and relevance of responses.
Considered Metrics:
Exact Match (EM) Score:

Measures the percentage of questions for which the model gives exactly correct answers.
BLEU Score (Bilingual Evaluation Understudy Score):

Evaluates the similarity between the generated answer and the reference answer based on n-gram overlap.
ROUGE Score (Recall-Oriented Understudy for Gisting Evaluation):

Measures the overlap of n-grams and word sequences between the generated answer and the reference answer.
METEOR Score (Metric for Evaluation of Translation with Explicit Ordering):

Measures the adequacy and fluency of the generated answer compared to the reference answer.
Accuracy:

Measures the proportion of correctly answered questions out of the total.
Coverage:

Measures the proportion of questions for which the model provides any answer.
Human Evaluation:

Subjective evaluation by human annotators to assess the overall quality, fluency, and correctness of the responses.
Conclusion:
By selecting a combination of these evaluation metrics, we aim to comprehensively evaluate the question-answering chatbot's performance in terms of correctness, fluency, relevance, and comprehensiveness of the responses. These metrics will help in understanding the strengths and weaknesses of the model and guide further improvements.
