# Trader practice

Mental-maths, trading-interview and ML-interview practice in your browser: a timed maths trainer with test replicas, 14 short technique lessons with drills, 210 trader-style questions and 262 machine-learning interview questions, all with worked solutions, plus exam-style formula sheets for ML and trader maths.

## Start

**On a phone or any computer:** open <https://juanmediavillaa.github.io/trader-practice/>. On a phone, use *Share → Add to Home Screen* (iPhone) or *⋮ → Add to Home screen* (Android) to keep it one tap away. Timed rounds show an on-screen keypad on touch screens.

**Offline copy:** download or clone this repository and double-click **`index.html`**. No install, no account, no server.

It needs an internet connection the first time, to load fonts and the maths typesetting (KaTeX). Everything else runs locally.

Your progress is saved in that browser on that device. Use **Export** in the menu now and then to download a backup, and **Import** to restore it, for example on another device.

## What's inside

### Maths trainer
- **Optiver-style 80 in 8:** 80 questions in 8 minutes, no calculator. Integers, decimals, fractions, percentages and missing numbers. Enter (or Submit on the keypad) submits; +1 right, −1 wrong.
- **Sequences test:** 24 next-term questions in 12 minutes.
- **Classic:** 120 seconds of Zetamac-style + − × ÷. It moves on as soon as you're right.
- **Custom and Weak spots:** pick question types. Weak spots leans towards your slowest and least accurate types.
- **Lessons:** 14 techniques with worked examples and a 60-second drill each. They cover compensation, near-round multiplication, difference of squares, ×5/×25/×125, ×11/×9, squares, division, decimals, the fraction table, percentages, missing numbers, estimation, sequences, and 80-in-8 strategy.
- **Progress:** score history per mode, plus accuracy and median time per question type.

### Trader questions
210 questions across 11 topics:
- probability
- expected value and decision games
- market making
- mental arithmetic
- sequences
- games and sizing (Kelly)
- statistics
- comparisons
- combinatorics
- options
- Fermi estimation

How they work:
- **Numeric answers are checked automatically.** Every one was verified by an independent script when the bank was built.
- **Free-text answers** (market-making reasoning, strategy) show a model answer to mark yourself against.
- **Estimation questions** accept answers within a factor of 3.
- **Review:** questions you miss come back after 1, 3, 7 and 21 days.
- **Lessons:** 28 short lessons, one per problem type (conditional probability, Bayes, waiting times, optimal stopping, Kelly, adverse selection, …). Each explains the maths and the intuition, lists the usual traps and works through a fresh example. Every trader question belongs to one lesson: **Start practising** takes you through its questions, easiest first, and once you've tried a question its lesson is one click away.

### ML interview
262 questions for ML engineer, research engineer and quant-research interviews, modelled on the UCL MSc Machine Learning courses and their past papers:
- Supervised Learning (27)
- Probabilistic & Unsupervised (27)
- Approximate Inference (24)
- Bayesian Deep Learning (24)
- Reinforcement Learning (25)
- IR & Data Mining (26)
- Learning Theory (27)
- Optimisation (20)
- ML fundamentals (25)
- Deep learning & LLMs (25)
- Applied ML scenarios (12)

Kinds: basics, exam-style (often multi-part), concept, derivation, calculation and scenario ("your model does X, what do you check?").

How they work:
- **Basics first.** Each course (apart from the applied scenarios) starts with short basics questions that build towards the harder ones. **Next question** always gives you the next unsolved one, easiest first: basics → easy → medium → hard. "Warm up first" and "Builds towards" links connect each question with its stepping stones.
- **Free-text answers** show a model answer (key points, derivation, intuition and the common trap) to mark yourself against. Calculation answers are checked automatically.
- **Review** works as for the trader questions.
- **Lessons:** 48 short lessons, a few per course (e.g. Supervised Learning: Bayes classifiers, ridge and kernels, boosting, online learning, SVMs, graph Laplacians). Each explains the maths and intuition and works a fresh example, and every ML question belongs to one of them, as with the trader lessons.

### Cheat sheets
Exam-style formula sheets, one for ML and one for trader maths: formulas and definitions grouped by topic, with a few words where needed and no worked answers.
- **ML:** shapes, linear algebra, matrix calculus, probability, distributions, Gaussians, estimation and Bayes, information theory, models and losses, optimisation, deep learning, inference and sampling, kernels and GPs, reinforcement learning, learning theory, and metrics.
- **Trader:** counting (by whether order matters and whether repetition is allowed), probability rules, expectation and variance, distributions (by situation), normal and CLT, random walks and Markov chains, options, market making, statistics, sequences and series, algebra, and inequalities.

Search filters the sheet as you type, and the topic buttons jump to a section. On a question, **Cheat sheet** opens it on top of the question, so you keep your place; on a computer, **Alt+C** opens it from anywhere.

## Tips

- Warm up with one Classic round, then do one lesson and its drill, then take an 80-in-8 to see whether the technique holds under time pressure.
- Test formats change. Treat the 80-in-8 "pass lines" you see online (around 55 net, 70+ strong) as candidate folklore, not official numbers.

## Notes

- Questions are written in our own words. Some adapt classic interview problems (for example from Zhou's *A Practical Guide to Quantitative Finance Interviews*) and say so on the question. Exam-style ML questions are reworded, with new numbers, and name the paper whose style they follow.
- Everything lives in this one `index.html` file.
