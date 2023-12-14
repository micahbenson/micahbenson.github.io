---
title: "Autoevaluating Bias in LLMs"
last_modified_at: 2023-12-13
---

For my natural language processing class final, my partner and I created two new evaluation tasks for LLMs designed to measure their ability to rank social bias in LLM outputs. To establish a baseline for LLM ability to rank severity of social bias in text, we paired biased online comments from the Civil Comments dataset and asked the LLM to select the less biased comment in each pair. To evaluate LLM ability to rank bias in LLM outputs, we used an Anthropic red-teaming dataset that presents pairs of potential model responses to adversarial prompts designed to make the model generate biased language. We then ask the LLM we are evaluating to select the less biased response. 

We ran all our experiments to establish a baseline on these tasks with Google's PaLM-2 model. Our results show that PaLM-2 reaches 0.691 overall accuracy on the online comment bias ranking task and 0.902 accuracy when leaving out ties and invalid responses. On the LLM-output bias ranking task, PaLM-2 reaches 0.424 overall accuracy and 0.688 accuracy when leaving out ties and invalid responses. Another contribution we made in this project is evaluating two methods of ranking pairs of biased text, ranking by asking the model to choose between two options and ranking by asking the model to assign a score to each option individually. We find that the choice method performs better than the score method on our binary ranking tasks. Overall, our results show that LLMs have potential to perform well on the task of ranking biased LLM outputs. 

Check out our git repo: [https://github.com/micahbenson/LLM-judge-harmlessness]

See our final paper for more information: 

<iframe src="/assets/Final_Paper.pdf" style="width:100%; height:800px;" frameborder="0"></iframe>
