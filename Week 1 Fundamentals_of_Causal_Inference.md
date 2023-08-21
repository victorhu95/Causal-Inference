
# Fundamentals of Causal Inference"


## What is Causal Inference?

The primary question it seeks to answer is how one can mathematically formalize the notions of "cause" and "effect."

### Goals in Data Science
- **Prediction**: This is one of the most common goals in statistics and data science. Techniques like regression are often used for this purpose.
- **Decision Making**: Another common goal is to understand the result of taking a particular action. This leads to questions about causal inference.

### Causal Inference vs. Prediction
- The document points out that while prediction models can inform us about the outcomes of decisions, they may not necessarily reveal the underlying causal relationships in the data.

### Key Points
- The methods for causal inference discussed in this course will:
  - Define explicit actions or states to determine "the cause" of interest.
  - Define causal effects as comparisons between outcomes under competing states.
  - Discuss ways to use data to understand what would have happened under some competing state using either thoughtful study design or statistical methods.

### Frameworks and Perspectives
- **Potential Outcomes Framework**: Also known as the Rubin Causal Model or counterfactual framework.
- **Causal Diagram Framework**: A graphical representation to understand causality.
- **Structural Equation Modeling**: A statistical modeling technique.
- **Econometrics and 'Quasi Experiments'**: These are techniques often used in economics to understand causality.


### Correlation is Not Causation
- This section emphasizes that correlation does not imply causation. While correlation can indicate a relationship between variables, it does not provide insights into the directional effect one variable has on another.

### What is Causation?
- The document delves into the complexities of defining causation. It suggests that while the idea of causation seems intuitive, formalizing it in a technical sense requires more work.


### Different Meanings of "Causation"
-  It cites optional reading from Holland (1986) in the Journal of the American Statistical Association.

1. **Ultimate Meaningfulness of Causation**: This is often traced back to philosophical underpinnings, such as those presented by Aristotle.
2. **Deducing the Causes of a Given Effect**: For example, identifying lifestyle factors that may have caused a specific disease.
3. **Understanding Details of Causal Mechanisms**: This could involve understanding the biological pathways through which a particular cause leads to an effect, such as how inhaled air pollution causes cardiovascular disease.
4. **Measuring the Effects of Causes**: This entails quantifying the impact of one variable on another, often through statistical methods.

### Key Points Reiterated
- Key takeaways about the methods for causal inference that will be covered in the course. It reiterates the need to:
  - Define explicit actions or states to determine "the cause" of interest.
  - Define causal effects as comparisons between outcomes under different states.
  - Discuss ways to use data for understanding outcomes under different states, either through study design or statistical methods.

### Correlation is Not Causation
- The document ends by revisiting the principle that correlation is not causation, reinforcing the need for careful analysis when aiming to understand causal relationships.

### Study Design and Statistical Methods
- Emphasis is placed on the role of thoughtful study design and statistical methods in achieving more accurate causal inferences. The better the study design, the less reliant one is on statistical methods.

# The "Classical" Paradigm for Causal Inference

It introduces the Classical Paradigm in the context of causal inference. This paradigm involves judging causality based on criteria concerning the relationship between a potential cause and an observed effect.

#### A Useful Distinction Between Causal Inference Paradigms

1. **The Classical Paradigm**: This approach focuses on what one would need to know about an association to determine causality. For example, if smoking is associated with lung cancer, what additional information would be needed to conclude that smoking causes lung cancer?
2. **Potential Outcomes Paradigm**: The document mentions this paradigm as well, although it doesn't elaborate much in the initial pages. It likely contrasts this with the Classical Paradigm.


### Practice of the Classical Paradigm

- **Association Between Cause and Effect**: The document elaborates on how an association between a nominal cause (like smoking) and an effect (like lung cancer) is observed, potentially across different research studies, populations, and statistical models.
- **Bradford Hill Criteria**: This set of criteria is applied to the observed association to judge causality. The criteria consider observed data, biological/physical/mechanistic knowledge, and other considerations.
- **Judgment of Strength**: A judgment is made about the strength of belief that the observed association is causal based on the Bradford Hill criteria.


### Extended Content: Bradford Hill Criteria in the Classical Paradigm

In the Classical Paradigm for causal inference, the Bradford Hill Criteria serve as guidelines for evaluating the plausibility of a causal relationship between two variables, such as a potential cause and its observed effect.

#### Components of the Bradford Hill Criteria

1. **Strength of Association**: A strong association between the cause and effect is more likely to be causal.
2. **Consistency**: The observed association should be consistent when observed under different circumstances.
3. **Specificity**: The association should be specific to particular cause-effect pairs and not be explainable by other variables.
4. **Temporality**: The cause should precede the effect in time.
5. **Biological Gradient (Dose-Response Relationship)**: A biological gradient should exist, meaning that higher exposure should generally lead to higher incidence of the effect.
6. **Plausibility**: The association should make biological or mechanistic sense.
7. **Coherence**: The association should align with existing theories and knowledge.
8. **Experiment**: Experimental evidence should support the causal hypothesis.
9. **Analogy**: Analogous associations should exist for similar cause-effect pairs.

#### Application in the Classical Paradigm

When following the Classical Paradigm, researchers typically apply these criteria to observed data and existing scientific knowledge to judge the strength of the causal relationship. This involves multidisciplinary considerations, including statistical findings, biological mechanisms, and epidemiological evidence.

By applying the Bradford Hill Criteria, researchers can make more informed judgments about the likelihood that a particular association is genuinely causal, rather than coincidental or influenced by other variables.
