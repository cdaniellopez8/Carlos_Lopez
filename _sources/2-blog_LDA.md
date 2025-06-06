<div style="text-align: center;">

# **Latent Dirichlet Allocation**
By: <a href="https://www.linkedin.com/in/carlos-daniel-lopez-perez-1b1b521b3/" style="text-decoration: none;">M.Sc. Carlos López</a> and <a href="https://www.linkedin.com/in/humberto-llinas-b1335319/" style="text-decoration: none;">Dr. rer. nat. Humberto Llinás</a>

</div>

<div style="text-align: justify;">

<div style="text-align: center;">

![Detective with magnifying glass “searching for topics” in documents.](detective.png)

**Fig 1.** Detective with magnifying glass “searching for topics” in documents. ***Source:*** *(AI-generated)*

</div>

<h1 style="font-size:2em; font-weight:bold; margin-top:1em;">How Does a Machine Detect What Documents Are About?</h1>

Imagine you have a mountain of articles, emails, tweets, or books. And now imagine you want to automatically discover what topics they talk about, without reading each one. Sounds useful? That’s exactly what a technique with a fancy name does: **Latent Dirichlet Allocation**, or LDA for short.

This blog summarizes and adapts part of the thesis developed by student <a href="https://www.linkedin.com/in/carlos-daniel-lopez-perez-1b1b521b3/" style="text-decoration: none;">Carlos López</a> and advisor <a href="https://www.linkedin.com/in/humberto-llinas-b1335319/" style="text-decoration: none;">Humberto Llinás</a> as part of the Master’s in Applied Statistics. The work is titled <a href="https://www.researchgate.net/publication/388458969_A_Comprehensive_Guide_to_Latent_Dirichlet_Allocation_Building_a_Solid_Foundation_with_Key_Statistical_Concepts?_tp=eyJjb250ZXh0Ijp7InBhZ2UiOiJwcm9maWxlIiwicHJldmlvdXNQYWdlIjoiaG9tZSIsInBvc2l0aW9uIjoicGFnZUNvbnRlbnQifX0" style="text-decoration: none;">***"A Comprehensive Guide to Latent Dirichlet Allocation: Building a Solid Foundation with Key Statistical Concepts"*** (See here)</a> We wrote it with the aim of explaining what LDA is and why it’s so useful today in a simple way. And don’t worry: we’ll explain it here without technical jargon. At the end, you’ll find the full reference if you’d like to read more in detail.

## **What Exactly Does LDA Do?**

<div style="text-align: center;">

![Representation of the LDA model’s objective.](lda.png)

**Fig 2.** Representation of the LDA model’s objective. ***Source:*** *(Own elaboration)*

</div>

Think of LDA as an automatic topic detective. You give it a bunch of texts, and it replies with something like:

- “This text is 60% about politics and 40% about health.”
- “This one is about sports and economics.”

And all that without telling it in advance what topics to expect! The magic is that it ***discovers the hidden topics by itself***, simply by analyzing the words in the texts.

## **And How Does This Magic Work?**

<div style="text-align: center;">

![Representation of words, topics, and topic distribution in a document.](lda_2.png)

**Fig 3.** Representation of words, topics, and topic distribution in a document. ***Source:*** *(Own elaboration)*

</div>

Even though it may sound like sorcery, LDA is based on well-thought-out mathematical ideas. But don’t worry: with a bit of intuition, it’s understandable. In this work, we explain step-by-step how it all works. Here are some of the key ideas:

1. **How do words behave in texts?**

Some words appear together frequently, and that gives us clues. For example, if terms like “vaccine,” “hospital,” and “patient” are repeated, it’s very likely the text is about medicine.

2. **How are hidden topics guessed?**

We use a statistical method (called ***Bayesian inference***) that allows us to make intelligent assumptions based on the words appearing in the texts. As the model finds more clues, it adjusts its ideas about what topics might be present.

3. **How is this model trained?**

We use another method (called ***Gibbs sampling***) that tries out different possible combinations, over and over, until it finds the one that best fits. It’s like solving a puzzle by testing many pieces until everything makes sense.

## **What Else Do I Explain in My Thesis?**

Besides explaining how LDA works, I also discuss:

- How to represent words in a way that machines can understand.
- How to prepare texts so the model can work effectively.
- A real-world case where we applied LDA to a database on statistical distributions (okay, this part is a bit more technical, but it shows the power of this tool!).

## **Why Does All This Matter?**

We’re surrounded by information. Too much! And techniques like LDA allow us to:

- Organize large collections of text.
- Detect trends on social media.
- Analyze open-ended survey responses.
- Better understand what people are saying… without reading everything!

## **In Summary:**

This work is a practical and accessible guide on how to uncover hidden topics in large amounts of text using statistical tools in a clear and useful way. Even though there’s math behind it, the goal is simple: to help people (and machines) better understand the information around us.

**Affiliations**

**Carlos López:** Industrial Engineer, Specialist in Applied Statistics, M.Sc. in Applied Statistics, Universidad del Norte, Colombia.

**Dr. rer. nat. Humberto Llinás Solano:** Coordinator of the Master’s in Applied Statistics and Full-time Professor in the Department of Mathematics and Statistics, Universidad del Norte, Colombia.


</div>