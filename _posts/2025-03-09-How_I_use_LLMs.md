---
layout: post
title: "Review on 'How I use LLMs' by Andrej Karpathy"
---

> **"Embrace the glorious mess that you are."**
>
> — *Elizabeth Gilbert*


# "How I use LLMs" by Andrej Karpathy

[![Watch the video](https://img.youtube.com/vi/EWvNQjAaOHw/hqdefault.jpg)](https://youtu.be/EWvNQjAaOHw?si=pZC5pFFtLzJGYLkb)



- ChatGPT: deployed 2022 by OpenAI, first LLM that people could talk to through text-based interface
- ChatGPT-like (Ecosystem)
  - ChatGPT: OG incumbent, most popular, most feature-rich
  - big tech:
    - Gemini: Google's version
    - Meta AI: Meta's version
    - Copilot: Microsoft's version
  - startups:
    - Claude: Anthropic's version
    - Grok: xAI's version
    - Perplexity
    - DeepSeek (Chinese Co)
    - Le Chat: Mistral's verison (French co)
- Learderboards:
  - arena
  - scale

- Give text, Give back text
- Token

- new chat: reset's the token string (reset the context window (working memory))
- pre-training stage: copy all the internet and compressing to zip file, have knowledge cutoff (outdated), vague (probabilitic)
- post-training stage: help model take a persona of assistant (good at conversations)
  - style of assistant and knowledge of internet

- fully self-contained entity: no tool use "yet"


- when switching topic, start new chat (wiping context window)
- context window is expensive
      - distracted by the tokens in the past when sampling a new token (decrease the accuracy)
      - more expensive to sample the next token (just by a little bit)
  - precious resource (working memory of model)
      - don't overload

- what model you are using
    - Plus users can send 80 messages/3-hour on GPT-4o (flagship model)

  
- thinking models
  - pretraining + sft + rl
  -   - rl: practice large collection of problems
  - discovers thinking strategies that lead to outcomes
  - resemble that the thinking process that you have
  - only 1~2 year ago (large breakthrough)
  - DeepSeek: incentivizing ... thr RL
- optional thinking bubble (thinking model)
-   - additionally tuned with RL
    - qualitative: higgher accuracy esp math, code, require a lot of thinking
    -   - simple might not benefit, deep and hard may benefit a lot
    - thinking (many token)
    - difficult problems: hight accuracy
- GPT-4o: flagship, most powerful model w/o thinking
    - thinking models: start with o (o1, o3, ...) are thinking models
        - all tuned with RL
- tool use
-   - only thr text
    - give model the ability to use tools
    - 
    -   - internet search: stuff the internet pages in the context window
        - "search the internet" token: after all internet searches, and after into the context window, reference back to the question
        - w/o internet search: no chance to give correct answer b/c of knowledge cutoff
      - model itself knows that it has to do the internet search, or sometimes we have to manually click the "search" button
  - deep research
  -   - 1~2month (pro version)
      - internet search + thinking
      - chatgpt is the best so far (thorough, reads the best, longest, makes sense)
      - still can be hallucinations (citations are important!)
  - we can give concrete documents to LLM by search or deep research, but also manually file upload
  -   - likely images are thrown away
      - PDF -> text file -> context window
  - use of python interpreter
      - calculator
      - very useful for chatgpt data analysis
  - artifacts (claude)
  - 






