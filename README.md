# Awesome GPT Prompt Engineering <div> <a href="https://awesome.re"> <img src="https://awesome.re/badge-flat2.svg" alt="Awesome"> </a> <a href="https://discord.gg/XhyEWG3PTr"> <img src="https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white" style="height: 20px;"> </a> </div>

A curated list of awesome resources, tools, and other shiny things for GPT prompt engineering.

Consider giving it a ⭐️ if you like it to show your support!

**Table of Contents**

- [Awesome GPT Prompt Engineering        ](#awesome-gpt-prompt-engineering--------)
	- [Roadmaps](#roadmaps)
	- [Guides](#guides)
	- [Techniques](#techniques)
	- [Prompt Collections](#prompt-collections)
	- [Papers](#papers)
	- [Books](#books)
	- [Communities](#communities)
	- [Prompt Generators](#prompt-generators)
	- [Auto-GPT Related](#auto-gpt-related)
	- [Prompt Injection](#prompt-injection)
	- [Playgrounds and Alternative UIs](#playgrounds-and-alternative-uis)
	- [ChatGPT Plug-ins](#chatgpt-plug-ins)
	- [Prompt Engineering Jobs Offers](#prompt-engineering-jobs-offers)
	- [AI Links Directories](#ai-links-directories)
- [Contributing](#contributing)

## Roadmaps

- [Prompt Engineering Roadmap](https://roadmap.sh/prompt-engineering): Step by step guide to learning Prompt Engineering.

<a href="#guides">
	<img src="https://github.com/snwfdhmp/awesome-gpt-prompt-engineering/blob/main/assets/roadmap.png?raw=true" width="700">
</a>

## Guides

- [Learn Prompting](https://learnprompting.org/docs/category/-basics): Introduction to Prompt Engineering and Prompt Engineering techniques.
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide): Guides, papers, lecture, notebooks and resources for prompt engineering.
- [Prompt Engineering 101](https://www.linkedin.com/pulse/prompt-engineering-101-introduction-resources-amatriain): Prompt Engineering guide by Xavi.
- [Prompt Engineering 101](https://humanloop.com/blog/prompt-engineering-101): Prompt Engineering guide by Raza Habib & Sinan Ozdemir.
- [Prompt Engineering Guide](https://github.com/SudalaiRajkumar/Talks_Webinars/blob/master/Slides/PromptEngineering_20230208.pdf): Prompt Engineering guide by Sudalai Rajkumar.
- [How to generate text: using different decoding methods for language generation with Transformers](https://huggingface.co/blog/how-to-generate): A guide to decoding methods for language generation with Transformers.
- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/): A visual guide to transformers, the core model used in GPT.
- [Reddit's r/aipromptprogramming Tutorials Collection](https://www.reddit.com/r/aipromptprogramming/collection/d3a393ad-ef15-4f2a-a23e-18a5c90ff48d): A collection of tutorials for prompt engineering.
- [Prompt Engineering Guide](https://www.promptingguide.ai/): A comprehensive guide that contains all the latest papers, learning resources, and developments in the field of prompt engineering.
- [dair-ai/Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide): A GitHub repository that provides a prompt engineering guide with the latest papers and learning guides.
- [How to Communicate with ChatGPT – A Guide to Prompt Engineering](https://www.freecodecamp.org/news/how-to-communicate-with-chatgpt-a-guide-to-prompt-engineering/): A guide that explains what prompt engineering is and how you can use it to improve your communication with AI tools.
- [A Beginner's Guide to ChatGPT Prompt Engineering](https://www.datacamp.com/tutorial/a-beginners-guide-to-chatgpt-prompt-engineering): A beginner-friendly guide that delves into the art and science of Prompt Engineering.
- [A Complete Introduction to Prompt Engineering for Large Language Models](https://www.mihaileric.com/posts/a-complete-introduction-to-prompt-engineering)
- [Prompt Engineering Guide: How to Engineer the Perfect Prompts](https://richardbatt.co.uk/prompt-engineering-guide-how-to-engineer-the-perfect-prompts)
- [Best practices for prompt engineering with OpenAI API](https://help.openai.com/articles/6654000-best-practices-for-prompt-engineering-with-openai-api): A guide by OpenAI that provides best practices for prompt engineering.
- [ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/): A short course on prompt engineering by deeplearning.ai.
- [Natural Language Processing](https://www.coursera.org/specializations/natural-language-processing): Coursera specialization focusing on NLP.
- [Learn Prompting](https://learnprompting.org/): A Free, Open Source Course on Communicating with AI.
- [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning): Coursera specialization by Andrew Ng, which includes a course on Sequence Models.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook): OpenAI's cookbook includes examples of prompt engineering.
- [Tokens and Tokenization: Understanding Cost, Speed, and Limits with OpenAI's APIs](https://www.prompthub.us/blog/tokens-and-tokenization-understanding-cost-speed-and-limits-with-openais-apis): Everything tokens and tokenization. How to control costs/performance, how to handle Max Token limits, and a real-world example on how you can make your prompts more efficient.
- [How OpenAI Parameters Actuallly Work](https://www.prompthub.us/blog/understanding-openai-parameters-how-to-optimize-your-prompts-for-better-outputs): How to use OpenAI's parameters to experiment with prompts and get better outputs.
- [A Beginner's Guide on Embeddings and Their Impact on Prompts](https://www.prompthub.us/blog/a-beginners-guide-on-embeddings-and-their-impact-on-prompts): A Beginner's Guide on Embeddings and Their Impact on Prompts.


## Techniques

- [Few Shot Learning](https://blog.paperspace.com/few-shot-learning/): Everything you need to know about Few-Shot Learning.
- [Zero Shot Learning](https://arxiv.org/pdf/2205.11916.pdf): Large Language Models are Zero-Shot Reasoners.
- [Chain of Thought](https://learnprompting.org/docs/intermediate/chain_of_thought): Encourages the LLM to explain its reasoning to improve its accuracy.
- [Zero Shot Chain of Thought](https://learnprompting.org/docs/intermediate/zero_shot_cot): Enable Chain of Thought with only a few words.
- [Tree of Thoughts](https://arxiv.org/pdf/2305.10601.pdf): Tree of Thoughts: Deliberate Problem Solving.
with Large Language Models.
- [Mastering ChatGPT Prompts](https://www.reddit.com/r/aipromptprogramming/collection/d3a393ad-ef15-4f2a-a23e-18a5c90ff48d/): Mastering ChatGPT Prompts: Harnessing Zero, One, and Few-Shot Learning, Fine-Tuning, and Embeddings for Enhanced GPT Performance.
- [Prompting GPT-3 To Be Reliable](https://arxiv.org/abs/2210.09150): Prompting GPT-3 To Be Reliable.
- [Decomposed Prompting](https://arxiv.org/abs/2210.02406): A Modular Approach for Solving Complex Tasks.
- [AutoPrompt](https://arxiv.org/abs/2010.15980): Eliciting Knowledge from Language Models with Automatically Generated Prompts.
- [LangChain Github Repository](https://github.com/hwchase17/langchain): Building applications with LLMs through composability.
- [Conju.ai](https://app.conju.ai/): A visual prompt chaining app.
- [Voiceflow](https://www.voiceflow.com): Professional collaborative visual prompt-chaining tool.
  
## Prompt Collections

- [FlowGPT](https://flowgpt.com/): FlowGPT is the largest open source prompt community.
- [awesomegptprompts.com](https://www.awesomegptprompts.com/): Explore hundreds of the best ChatGPT Prompts.
- [fka/awesome-chatgpt-prompts](https://huggingface.co/datasets/fka/awesome-chatgpt-prompts): Dataset of awesome chatgpt prompts.
- [f/awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts): This repo includes ChatGPT prompt curation to use ChatGPT better. .
- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts)
- [PromptHub](https://prompthub.space/)
- [ShowGPT.co](https://showgpt.co/templates)
- [Best Data Science ChatGPT Prompts](https://github.com/travistangvh/ChatGPT-Data-Science-Prompts)
- [ChatGPT prompts uploaded by the FlowGPT community](https://flowgpt.com)
- [Ignacio Velásquez Prompt Templates](https://ignacio-velasquez.notion.site/ignacio-velasquez/500-ChatGPT-Prompt-Templates-d9541e901b2b4e8f800e819bdc0256da): 500+ ChatGPT Prompt Templates.
- [PromptPal](https://www.promptpal.net/): A collection of prompts for GPT-3 and other language models.
- [Hero GPT](https://hero.page/ai-prompts): AI Prompt Library.
- [Reddit's ChatGPT Prompts](https://www.reddit.com/r/ChatGPT_Prompts/)
- [Snack Prompt](https://snackprompt.com): GPT prompts collection, has a a Chrome extension.
- [ShareGPT](https://sharegpt.com): Share your prompts and your entire conversations.
- [Prompt Search](https://www.ptsearch.info/tags/list/): a search engine for AI Prompts.
- [PromptBase](https://promptbase.com/): The largest prompts marketplace on the web.
- [The Ultimate 5 ChatGPT Prompts](https://ngmi.gumroad.com/l/nobsprompts): Simplify Your AI Experience.
- [The Prompt Index](https://www.thepromptindex.com/): A vast collection of carefully curated prompts, stimulating imagination and fueling creative endeavours.
- [PromptDen](https://promptden.com): A growing list of thousands of prompts for both text and image generation. Free to explore, add your own, save your favorites and even create a profile page for prompt engineering.

## Papers

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762): Transformer introduction paper.
- [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165): GPT-3 introduction paper by OpenAI.
- [Fine-Tuning Language Models from Human Preferences](https://arxiv.org/abs/1909.08593): Important paper on fine-tuning language models by OpenAI.
- [The Power of Scale for Parameter-Efficient Prompt Tuning](https://arxiv.org/abs/2104.08691): Explores the benefits of "prompt tuning" for robust task performance.
- [Deep Attentive Learning for Stock Movement Prediction From Social Media Text and Company Correlations](https://aclanthology.org/2020.emnlp-main.676): Introduces an architecture for accurate stock forecasting using financial data and social media signals.
- [A Prompt Pattern Catalog to Enhance Prompt Engineering with ChatGPT](https://arxiv.org/abs/2302.11382)
- [Hard Prompts Made Easy](https://arxiv.org/abs/2302.03668): Gradient-Based Discrete Optimization for Prompt Tuning and Discovery.
- [Synthetic Prompting](https://arxiv.org/abs/2302.00618): Generating Chain-of-Thought Demonstrations for Large Language Models.
- [Progressive Prompts](https://arxiv.org/abs/2301.12314): Continual Learning for Language Models.
- [Batch Prompting](https://arxiv.org/abs/2301.08721): Efficient Inference with LLM APIs.
- [Successive Prompting for Decompleting Complex Questions](https://arxiv.org/abs/2212.04092)
- [Structured Prompting](https://arxiv.org/abs/2212.06713): Scaling In-Context Learning to 1,000 Examples.
- [Large Language Models Are Human-Level Prompt Engineers](https://arxiv.org/abs/2211.01910)
- [Ask Me Anything](https://paperswithcode.com/paper/ask-me-anything-a-simple-strategy-for): A simple strategy for prompting language models.
- [PromptChainer](https://arxiv.org/abs/2203.06566): Chaining Large Language Model Prompts through Visual Programming.
- [Reframing Instructional Prompts to GPTk's Language](https://arxiv.org/abs/2109.07830)
- [Prompt Programming for Large Language Models](https://arxiv.org/abs/2102.07350): Beyond the Few-Shot Paradigm.
- [Prefix-Tuning: Optimizing Continuous Prompts for Generation](https://arxiv.org/abs/2101.00190)
- [Multimodal Chain-of-Thought Reasoning in Language Models](https://arxiv.org/abs/2302.00923)
- [On Second Thought, Let's Not Think Step by Step!](https://arxiv.org/abs/2212.08061): Bias and Toxicity in Zero-Shot Reasoning.
- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)
- [Language Models Are Greedy Reasoners](https://arxiv.org/abs/2210.01240v3): A Systematic Formal Analysis of Chain-of-Thought.
- [On the Advance of Making Language Models Better Reasoners](https://arxiv.org/abs/2206.02336)
- [Large Language Models are Zero-Shot Reasoners](https://arxiv.org/abs/2205.11916)
- [Reasoning Like Program Executors](https://arxiv.org/abs/2201.11473)
- [Self-Consistency Improves Chain of Thought Reasoning in Language Models](https://arxiv.org/abs/2203.11171)
- [Chain of Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)
- [Generated Knowledge Prompting for Commonsense Reasoning](https://arxiv.org/abs/2110.08387)
- [Large Language Models Can Be Easily Distracted by Irrelevant Context](https://arxiv.org/abs/2302.00093)
- [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073)

## Books

- [The ChatGPT Prompt Book](https://lifearchitect.ai/chatgpt-prompt-book/): A book dedicated to ChatGPT prompts.
- [You Look Like a Thing and I Love You](https://janelleshane.com/book-you-look-like-a-thing-and-i-love-you): A book about AI with a focus on language models.

## Communities

- [OpenAI Discord Server](https://discord.com/invite/openai): The official OpenAI Discord server.
- [ChatGPT Prompt Engineering Discord Server](https://dsc.gg/chatgpt): A Discord server dedicated to prompt engineering.
- [Attention Architects](https://discord.gg/XhyEWG3PTr): Prompt Engineering open source community.
- [r/MachineLearning](https://www.reddit.com/r/MachineLearning/): The Machine Learning subreddit often has discussions on GPT and other language models.
- [Hugging Face Forum](https://discuss.huggingface.co/): A forum for discussing Hugging Face's transformer models, including GPT.
- [ChatGPT Community Discord Server](https://discord.gg/cgpt): A Discord server dedicated to ChatGPT.
- [Reddit's ChatGPT Discord Server](https://discord.gg/NuefU36EC2): r/chatgpt Discord server.
- [PromptsLab Discord](https://discord.gg/m88xfYMbK6): Knowledge sharing community for Generative Models, Prompt Engineering, LLMs.
- [Learn Prompting](https://discord.gg/7enStJXQzD): A Discord server dedicated to learning about prompts.
- [Artificial Intelligence Discord](https://discord.gg/XhyEWG3PTr): Discord server for AI enthusiasts and prompt engineers.

## Prompt Generators

- [Promptify](https://promptify.pro): Automatically improve your prompt.
- [Fusion](https://fusion.tiiny.site/home.html): Elevate your output with Fusion's smart prompts.
- [Bumble-Prompts](https://bumble-prompts.vercel.app/): Let AI Write your bumble prompt.
- [ChatGPT Prompt Generator](https://huggingface.co/spaces/merve/ChatGPT-prompt-generator): Generates ChatGPT prompts based on a BART model.
- [PromptPerfect](https://promptperfect.jina.ai/): Prompt optimizer.
- [Hero GPT](https://hero.page/ai-prompts): AI Prompt Generator.
- [LMQL](https://github.com/eth-sri/lmql): Query language for programming large language models.
- [OpenPromptStudio](https://moonvy.com/apps/ops/)
- [BossGPT](https://www.gptboss.com)

## Auto-GPT Related

- [Auto-GPT Official Repo](https://github.com/Significant-Gravitas/Auto-GPT)
- [Auto-GPT God Mode](https://godmode.space/)
- [OpenAIMaster's Guide to Auto-GPT](https://openaimaster.com/how-does-autogpt-work-an-ai-tool-to-create-full-projects/): How does Auto-GPT work, an AI tool to create full projects.
- [AgentGPT](https://agentgpt.reworkd.ai): GPT agents in browser.

## Prompt Injection

- [Understanding Prompt Injections and What You Can Do About Them](https://www.prompthub.us/blog/understanding-prompt-injections-and-what-you-can-do-about-them): An introduction to prompt injections with examples and tactics you can use to mitigate potential risks in your application.
- [Learn Prompting's Prompt Injection guide](https://learnprompting.org/docs/prompt_hacking/injection): A guide to prompt injections with examples.
- [Prompt injection: What's the worst that can happen?](https://simonwillison.net/2023/Apr/14/worst-that-can-happen/)
- [Prompt injections are bad, mkay?](https://greshake.github.io/)

## Playgrounds and Alternative UIs

- [Official OpenAI Playground](https://platform.openai.com/playground)
- [Nat.Dev](https://nat.dev): Multiple Chat AI Playground & Comparer.
- [Poe.com](https://poe.com): All in one playground: GPT4, Sage, Claude+, Dragonfly, and more...
- [Ora.sh GPT-4 Chatbots](https://ora.sh/gpt-4)
- [Better ChatGPT](https://bettergpt.chat): A web app with a better UI for exploring OpenAI's ChatGPT API.
- [LMQL.AI](https://lmql.ai/playground/#calc): A programming language and platform for language models.
- [Vercel Ai Playground](https://play.vercel.ai): One prompt, multiple Models (including GPT-4).

## ChatGPT Plug-ins

- [ChatGPT plugins](https://openai.com/blog/chatgpt-plugins): OpenAI Official Page.
- [Plug-in example code in Python](https://github.com/ruvnet/chatgpt_plugin_python): Example code for creating a ChatGPT plug-in in Python.
- [Surfer Plug-in source code](https://github.com/ruvnet/Surfer)
- [Security](https://www.security.dev/): (PAID) Create, deploy, monitor and secure LLM Plugins.

## Prompt Engineering Jobs Offers

- [Prompt-Talent](https://www.prompt-talent.com): Prompt engineering job offers.

## AI Links Directories

- [FuturePedia](https://www.futurepedia.io/ai-tools): The Largest AI Tools Directory Updated Daily.
- [Theresanaiforthat](https://theresanaiforthat.com/s/gpt/): The biggest AI aggregator.
- [Awesome-Prompt-Engineering](https://github.com/promptslab/Awesome-Prompt-Engineering)
- [AiTreasureBox](https://github.com/superiorlu/AiTreasureBox)
- [EwingYangs Awesome-open-gpt](https://github.com/EwingYangs/awesome-open-gpt)
- [KennethanCeyer Awesome-llmops](https://github.com/KennethanCeyer/awesome-llmops)
- [KennethanCeyer awesome-llm](https://github.com/KennethanCeyer/awesome-llm)
- [tensorchord Awesome-LLMOps](https://github.com/tensorchord/Awesome-LLMOps)

# Contributing

Contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.

How to help:

- Give a ⭐️ to increase the repository's visibility.
- Add descriptions for resources that don't have them.
- Add new resources to the list.
- Fix typos or grammatical errors.
- Share this repository with others.
