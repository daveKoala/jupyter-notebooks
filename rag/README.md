## Retrieval Augmented Generation (RAG)

Retrieval-Augmented Generation (RAG) is an AI framework that enhances large language models (LLMs) by incorporating information retrieval to access and utilize external knowledge bases, leading to more accurate, up-to-date, and relevant outputs.

In very simple terms, you search for your own data sets/docs/images/etc, then it to ChatGPT with a prompt to do something with it and return the response

## Steps

- 🔲 Client question
- 🔲 Transform question
- 🔲 Use transformed question within a vector search to retrieve documents (no-SQL)
- 🔲 Craft a GenAI prompt and appended with returned documents
- 🔲 Display response

## Nice to have

A method of feedback to the quality of the response 👍 or 👎

## How accurate is RAG?

That depends, the GenAI is a proberbility machine so will use a lot of maths to return a string that looks like it has been resoned. This means that while the responses can sound coherent and well-reasoned, they are ultimately the product of probabilistic calculations rather than true understanding

Take a step back from that the data returned also can suffer in terms of degree of 'correctness'. When you use methods like vector search, it’s important to remember that these techniques are rooted in mathematical algorithms rather than any genuine understanding of the data. Vector searches rely on numerical representations and similarity metrics to identify related content, meaning they are essentially matching patterns rather than grasping the true meaning behind the information.

Additionally, because the process is probabilistic, the results can vary with each run. This inherent variability means that even if you execute the same query multiple times, you might receive different answers. In essence, while these tools are powerful for finding patterns and relationships in large datasets, they don’t “understand” the data in a human sense, and their outputs should be seen as approximations rather than definitive truths.

As noted by figures like Andrej Karpathy, such models sometimes “only remember” parts of the data, which can lead to errors or oversights. It’s a reminder that even advanced tools can falter in accuracy due to the way they process and recall information.

Given these limitations, it is important not to assume that outputs from tools like these are 100% correct. Instead, one should approach the generated content with a critical mindset, verify important details against trusted sources, and understand that the probabilistic nature of these systems means that occasional inaccuracies are an inherent risk. This balanced perspective ensures that while such tools can greatly aid research and decision-making, they should be used as one component of a broader information validation strategy.

✅
🔲
