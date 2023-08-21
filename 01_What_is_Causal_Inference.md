Segment 1: Fundamentals of Causal Inference
Section 01: What is Causal Inference?
Op erating Question: Segment 1
What is causal inference and how do we
mathematically formalize "cause" and "eect"?
Data Science
## I
(Most) common goal in statistics and data science:
Prediction
## I
E.g., regression:
## I
(Another) common goal:
Decision Making
## I
If I take an action, what will b e the result?
## I
Questions of
causal inference
.
## I
Can prediction mo dels/algorithms tell us ab out impacts of
decisions?
## I
That is, can they tell us ab out underlying causal relationships
in the data?
## I
Mayb e...but there's more work to do
Data Science
## I
(Most) common goal in statistics and data science:
Prediction
## I
E.g., regression:
## I
(Another) common goal:
Decision Making
## I
If I take an action, what will b e the result?
## I
Questions of
causal inference
.
## I
Can prediction mo dels/algorithms tell us ab out impacts of
decisions?
## I
That is, can they tell us ab out underlying causal relationships
in the data?
## I
Mayb e...but there's more work to do
Data Science
## I
(Most) common goal in statistics and data science:
Prediction
## I
E.g., regression:
## I
(Another) common goal:
Decision Making
## I
If I take an action, what will b e the result?
## I
Questions of
causal inference
.
## I
Can prediction mo dels/algorithms tell us ab out impacts of
decisions?
## I
That is, can they tell us ab out underlying causal relationships
in the data?
## I
Mayb e...but there's more work to do
Data Science
## I
(Most) common goal in statistics and data science:
Prediction
## I
E.g., regression:
## I
(Another) common goal:
Decision Making
## I
If I take an action, what will b e the result?
## I
Questions of
causal inference
.
## I
Can prediction mo dels/algorithms tell us ab out impacts of
decisions?
## I
That is, can they tell us ab out underlying causal relationships
in the data?
## I
Mayb e...but there's more work to do
Correlation is Not Causation!
So what is causation?
## I
Sounds very intuit iv e...
## I
Technical denition can b e elusive
So what is \causal inference?"
## I
The
causal inference metho dology
in this class will give:
## I
One way of formalizing what is meant by \c ausal eect" in
data science
## I
A set of p ersp ectives/to ols/metho ds for data-based de cision
making that:
1.
Frame questions ab out cause and eect to b e answered with
data
2.
Analyze data in a way sp ecically designed to estimate the
consequences of actions or decisions
3.
Inform the design of prosp ective studies to help uncover causal
eects
Correlation is Not Causation!
So what is causation?
## I
Sounds very intuit iv e...
## I
Technical denition can b e elusive
So what is \causal inference?"
## I
The
causal inference metho dology
in this class will give:
## I
One way of formalizing what is meant by \c ausal eect" in
data science
## I
A set of p ersp ectives/to ols/metho ds for data-based de cision
making that:
1.
Frame questions ab out cause and eect to b e answered with
data
2.
Analyze data in a way sp ecically designed to estimate the
consequences of actions or decisions
3.
Inform the design of prosp ective studies to help uncover causal
eects
Correlation is Not Causation!
So what is causation?
## I
Sounds very intuit iv e...
## I
Technical denition can b e elusive
So what is \causal inference?"
## I
The
causal inference metho dology
in this class will give:
## I
One way of formalizing what is meant by \c ausal eect" in
data science
## I
A set of p ersp ectives/to ols/metho ds for data-based de cision
making that:
1.
Frame questions ab out cause and eect to b e answered with
data
2.
Analyze data in a way sp ecically designed to estimate the
consequences of actions or decisions
3.
Inform the design of prosp ective studies to help uncover causal
eects
Dierent Meanings of \Causation"
Optional Reading:
Holland (1986) Statistics and Ca usal Inference,
Journal of the
American Statistical Asso ciation
81(396) pp. 945-960
1.
Ultimate meaningfulness of causation
## I
Aristotle!
2.
Deducing the causes of a given eect
## I
Which lifesty le factors caused her to have this disease?
3.
Understanding details of causal mechanisms
## I
What is the biological pathway through which inhaled air
p ollution causes cardiovascular disease?
4.
Measuring the eects of c ause s
## I
What is the eect of providing a c us tomer with targete d
advertising?
## I
Statistics/data science has the mos t to say ab out this one
Dierent Meanings of \Causation"
Optional Reading:
Holland (1986) Statistics and Ca usal Inference,
Journal of the
American Statistical Asso ciation
81(396) pp. 945-960
1.
Ultimate meaningfulness of causation
## I
Aristotle!
2.
Deducing the causes of a given eect
## I
Which lifesty le factors caused her to have this disease?
3.
Understanding details of causal mechanisms
## I
What is the biological pathway through which inhaled air
p ollution causes cardiovascular disease?
4.
Measuring the eects of c ause s
## I
What is the eect of providing a c us tomer with targete d
advertising?
## I
Statistics/data science has the mos t to say ab out this one
Dierent Meanings of \Causation"
Optional Reading:
Holland (1986) Statistics and Ca usal Inference,
Journal of the
American Statistical Asso ciation
81(396) pp. 945-960
1.
Ultimate meaningfulness of causation
## I
Aristotle!
2.
Deducing the causes of a given eect
## I
Which lifesty le factors caused her to have this disease?
3.
Understanding details of causal mechanisms
## I
What is the biological pathway through which inhaled air
p ollution causes cardiovascular disease?
4.
Measuring the eects of c ause s
## I
What is the eect of providing a c us tomer with targete d
advertising?
## I
Statistics/data science has the mos t to say ab out this one
Dierent Meanings of \Causation"
Optional Reading:
Holland (1986) Statistics and Ca usal Inference,
Journal of the
American Statistical Asso ciation
81(396) pp. 945-960
1.
Ultimate meaningfulness of causation
## I
Aristotle!
2.
Deducing the causes of a given eect
## I
Which lifesty le factors caused her to have this disease?
3.
Understanding details of causal mechanisms
## I
What is the biological pathway through which inhaled air
p ollution causes cardiovascular disease?
4.
Measuring the eects of c ause s
## I
What is the eect of providing a c us tomer with targete d
advertising?
## I
Statistics/data science has the mos t to say ab out this one
Examples
## I
The aspirin I to ok caused my headache to go away.
## I
I did not get the u this ye ar b ecause I was vaccinated.
## I
Her colon cancer got diagnosed to o late b ecause she is black.
## I
His diab etes c ause d him to have a heart attack.
## I
Turning the car's steering wheel c ause d the car to turn.
## I
Do es he have lung cancer b ecause he smokes?
## I
Will studying for the tes t cause a high score?
## I
Is there a causal link b etween air p ollution and cardiovascular
disease?
Example
From Holla nd (1986)
Three stateme nts , all using dierent meanings of \b ecause" to
explain the same \eect:"
## (A)
She did well on the exam b ecause she was a woman.
## I
\Cause" as an attribute she p ossess es
## (B)
She did well on the test b ecause she studied.
## I
\Cause" is a voluntary activity that was p erformed
## (C)
She did well on the test b ecause she was coached.
## I
\Cause" is an activity that was imp osed
Key Point
Causal inference metho ds in this course will:
## I
Dene explicit actions/states to determine \the cause" of
interest
## I
Dene causal eects as comparisons b etween outcomes under
comp eting states
## I
Discuss ways to use
data
to understand what would have
happ ened under some comp eting state using:
1.
Thoughtful study design (either prosp ective or retrosp ective )
2.
Statistical metho ds and/or mo dels
(The b etter we are at 1, the less 2 matters)
Correlation is Not Causation!
Then what is \causal inference"?
A general analytic p ersp ec tive to:
## I
Frame questions ab out cause and eect to b e ans wered with
data
## I
Analyze data in a way sp ecically designed to estimate the
consequences of actions or decisions
## I
Clarify comm on threats to t he validity of analy ses that
(implicitly or explicitly) aim to characterize causal
relationships
## I
Increase transparency ab out the assumptions re quired to
estimate causal eects with data
Correlation is Not Causation!
Then what is \causal inference"?
A general analytic p ersp ec tive to:
## I
Frame questions ab out cause and eect to b e ans wered with
data
## I
Analyze data in a way sp ecically designed to estimate the
consequences of actions or decisions
## I
Clarify comm on threats to t he validity of analy ses that
(implicitly or explicitly) aim to characterize causal
relationships
## I
Increase transparency ab out the assumptions re quired to
estimate causal eects with data
Some Data Science Frameworks and Persp ectives
1.
Potential Outcomes Framework
, AKA, Rubin Causal
Mo del, counterfactual framework, Neyman-Rubin Causal
Mo del
2.
Causal diagram framework
3.
Structural equation mo deling
4.
Econometrics, \Quasi Exp eriments"
These are related frameworks. One
goal
of this course is to give
the fundamental to ols to navigate, understand, and apply to ols
from this literature.