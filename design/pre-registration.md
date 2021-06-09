# Effect of Experiment Framing on Game Data

## Description

Investigating whether the design of an applied game for data collection affects data quality through the way it frames itself (implicitly) as experiment or game.

This study will determine whether there is an effect of implicit experimental framing on the accuracy of the data collected and enjoyment. Implicit experimental framing will be manipulated through the design of the game. Specifically, we believe designing the game to instruct players exactly which move to make throughout the game (removing strategic choice) will lead to it being percieved by participants within an "experiment" frame and thus improve accuracy.

## Hypotheses

1. With high implicit experimental framing, a greater proportion of the data will be accurate
2. With high implicit experimental framing, participants will enjoy the game less
3. Manipulation check: With high implicit experimental framing, participants will experience the game with an 'experiment' frame rather than a 'play' frame.

Design Plan
-----------

### Study type

Experiment - A researcher randomly assigns treatments to study subjects, this includes field or lab experiments. This is also known as an intervention experiment and includes randomized controlled trials.

### Blinding

* For studies that involve human subjects, they will not know the treatment group to which they have been assigned.
* Personnel who interact directly with the study subjects (either human or non-human subjects) will not be aware of the assigned treatments. (Commonly known as “double blind”)

### Is there any additional blinding in this study?

Participants will be assigned automatically by the game.

### Study design

Between-participant design with two groups.

### Randomization

Simple randomisation. However, the sample size will be extended if one of the groups has too few participants (see sampling plan).

Sampling Plan
-------------

### Existing Data

Registration prior to creation of data

### Data collection procedures

Participants will be recruited from Prolific with a study description as in `description.md`. The following filters will apply on Prolific:

1. Age >= 18
2. First language English
3. Have not participated in any of my previous studies

Participants will be paid £1.00 for a 10 minute task. 

### Sample Size

200 participants

### Sample Size Rationale

See the file `power-analysis.Rout`.

Variables
---------

### Manipulated Variable

We will manipulate the design of the game. Specifically, whether the game instructs the player what move they should make at every point (which removes any strategic choice). The purpose of this manipulation is to make the game 'play' like an experiment with a series of controlled trials. There were two conditions:

**High-Implicit-Framing:** Throughout the game players are shown which blocks they have to clear for every move. Moves that don't clear (only and all) those blocks do not progress the game.

**Low-Implicit-Framing:** Players are not shown particular blocks to clear. The restriction on what moves progress the game does not apply.

### Measured Variables

**Accuracy**: Accuracy will be measured as the proportion of data collected that corresponds to standard English word order.

**Enjoyment**: Enjoyment will be measured using the Intrinsic Motivation Inventory: Enjoyment Subscale. (Deci and Ryan, n.d.)

**Play Framing** Play Framing will be measured with adapted versions of the "Direct Play" questions of the Play Experience Scale (Pavlas et al. 2012):

1. When I was using the game, it felt like I was playing rather than doing an experiment
2. I would characterize my experience with the game as playing
3. I was playing a game rather than doing an experiment
4. (R) Using the game felt like doing an experiment 

Analysis Plan
-------------

**Hypothesis 1**: A two-tailed Mann-Whitney U test will be used to test whether the distribution of Accuracy differs significantly between the high-framing condition than the low-framing condition.

**Hypothesis 2**: A two-tailed two-sample t-test will be used to test whether the mean scores of Enjoyment are greater in the low-framing condition than the high-framing condition.

**Hypothesis 3**: A two-tailed two-sample t-test will be used to test whether the mean scores of Play Framing are greater in the low-framing condition than the high-framing condition.

### Inference criteria

P values for Hypotheses 1 and 2 will be adjusted using the Holm-Bonferoni method, maintaining a family-wise error rate of 0.05.

P value for Hypothesis 3 (manipulation check) will be compared against a comparison-wise error rate of 0.05.

### Exclusion Criteria

The following will be excluded:

1. Participants reporting their age as under 18
2. Participants reporting their first language as other than English.
3. Participants with fewer than 16 moves
4. Participants reporting a bug

### Missing data

Incomplete records will be excluded from hypothesis tests

References
----------

Deci, E. L., and Ryan, R. M. (n.d.). Intrinsic Motivation Inventory. Available at: https://selfdeterminationtheory.org/questionnaires/

Pavlas D, Jentsch F, Salas E, Fiore SM, Sims V. The Play Experience Scale: Development and Validation of a Measure of Play. Human Factors. 2012;54(2):214-225. doi:10.1177/0018720811434513
