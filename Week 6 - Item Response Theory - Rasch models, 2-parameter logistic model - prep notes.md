# (6\6) Psychometrics II - Prep Notes

## Week 6 - Item Response Theory

- Item Response Theory (IRT) is a contemporary alternative to classical test theory (CTT). IRT has emerged relatively recently as an alternative way of conceptualizing and analyzing measurement in the behavioural sciences.
- IRT is more computationally complex than CTT, but it is thought that this complexity is iffset by several important advantages.
- We will describe some the most fundamental concepts in IRT, including the idea of item parameters, measurement models, and test information.
- IRT is based on the belief that a person's response to a particular test item is influenced by qualities of the individual and by qualities of the item. Based on this perspective, IRT provides procedures for obtaining information about individuals, items, and tests.

- The basic form of IRT states that a person's response to an item is affected by the individual's **trait level** and **the item's difficulty level**:
1. **Respondent trait level as a determinant of item responses**: One factor affecting a person's probability of responding in a particular way to an item is the individual's level on the psychological trait being assessed by the item. **For example**, someone with a high level of mathematical ability is more likely to respond correctly to a math item than someone with a low level of mathematical ability. Or, a person who has a high level of extroversion is more likely to endorse or agree with an item that measures extroversion that a person who has a low level of extroversion, etc.
2. **Item difficulty as a determinant of item responses**: An item's level of difficulty is another factor affecting a person's probability of responding in a particular way. **For example**, a math item that has a high level of difficulty will be less likely to be answered correctly than an item that has a low level of difficulty (i.e., an easy item).

- Although they are separate issues in IRT analysis, trait level and item difficulty are intrinsically connected: Item difficulty is conceived in terms of trait level. Specifically, a difficult item requires a relatively high trait level to be answered correctly. **For example**, students might need to have a ninth-grade mathematical ability in order to have a good chance of answering correctly a question that involves the concept of a square root. In constract, they might only need a second-grade mathematical ability in order to have a good chance of answering correctly a question that only involves addition. Thus, the item's difficulty can be described in terms of levels of the relevant trait.
- In an IRT analysis, trait levels and item difficulties are usually scored on a standardized metric, so that their means are 0 and the standard deviations are 1. Thus, a person who has a trait level of 0 has an average level of that trait, and a person who has a trait level of 1.5 has a trait level that is 1.5 standard deviations above the mean. Similarly, an item with a difficulty level of 0 is an average item, and an item with a difficulty level of 1.5 is a relatively difficult item.
- **Item difficulty is expressed in terms of trait level**: An item's difficulty is defined as the trait level required for participants to have a .50 probability of answering the item correctly. If an item has a difficulty of 0, then a person with an average trait level (i.e., a trait level of 0) will have a 50:50 chance of answering the item correctly. For that same item (i.e., an item with a difficulty of 0), a person with a higher trait level (i.e., a trait level greater than 0) will have a higher chance of answering the item correctly, and a person with a lower trait level will have a lower chance of answering the item correctly. **More generally, higher item difficutly indicates that higher trait levels are required for a person th have a 50:50 chance of answering the item correctly**. **For example**, if an item has a difficulty of 1.5, then a person with a trait level of 1.5 (i.e. a trait level that is 1.5 standard deviations aboves the mean) will have a 50:50 chance of answering the item correctly. Similarly, lower difficulty levels indicate that only realtively low trait levels are required for participants to have a 50:50 chance of answering the item correctly.

#### Item discrimination as a determinant of item responses

- Just as the items on a test might differ in terms of their difficulties (with some items being more difficult than others), they might also differ in terms of the degree to which they can differentiate individuals who have high trait levels from individuals who have low trait levels.
- This item characteristic is called **item discrimination**, and it is analogous to item-total correlation from classical test theory.
- An item's discrimination value indicates the relevance of the item to the trait being measured by the test. An item with a **positive discrimination value** at least somewhat consistent with the inderlying trait that is being measured, and a relatively large discrimination value indicates a relatively strong consistency between the item and the underlying trait. An item with a **discrimination value of 0** is unrelated to the underlying trait that is supposedly being measured. An item with a **negative discrimination value** is inversely related to the underlying trait (i.e., higher trait scores make it less likely that the item will be answered correctly). So, it is generally desirable for items to have a **large positive discrimination value**.

*Why would some items have good discrimination and others have poor discrimination?*
Let's consider the following two items that could be written for a mathematics test:
1. How many pecks in three bushels?
2. What is 4 times 3?

To answer the first item correctly, a student needs to have enough mathematical ability to perform multiplication. But, the item also requires that the student know the number of pecks in a bushel. The fact that this item requires something beyond basic mathematical ability means that it is not very closely, or purely, related to mathematical ability. In other words, having a high enough level of mathematical ability may not be enough to answer the item correctly. So, this item would likely have a low discrimination value, as it is only weakly related to the underlying trait being assessed by the test of mathematical ability. In other words, this item does not do a very good job of discriminating students who have a relatively high level fo mathematical ability from students who have relatively low mathematical ability. Even if one person answers the item incorrectly and another answers the item correctly, we might not feel confident concluding the one person has a higher mathematical ability than the other, as the person who answered the item incorrectly may also have the required mathematical ability, but may simply not know the number of pecks in a bushel. Responding correclty to the second item requires the ability to perform mutliplication, but it requires no additional knowledge or ability. The only quality of the student that is relevant to answering the item correctly is mathematical ability. Thus, the second item is a much more "pure" mathematical item, and it is more stronglyrelated to the underlying trait of mathematical ability than the first item. Consequently, it would have a relatively high item discrimination value. This item does a better job of discriminating students who have a relatively high level of mathematical ability from students who have a relatively low level of mathematical ability.

### IRT measurement models

- From an IRT perspective, we can identify the components affecting the probability that a person will respond in a particular way to a particular item. A *measurement model* expresses the links between an outcome (e.g., a person's response to a particular item) and the components that affect that outcome (e.g., qualities of the person and/or qualities of the item).
- IRT models express these links mathematically, in terms of the probability that a person with a particular trait level will respond in a particular way to a particular item.
- Different models have been developed from the IRT perspective, and these models differ from each other in at least two important ways. One difference among the measurement models is in terms of **item characteristics**, or **parameters**. Some models are designed to account for only one parameter, whereas other, more complex models account for two or more parameters. A second difference is in terms of the response option format. Some models are designed to be used for binary items (e.g., true/false, yes/no, correct/incorrect). Others are designed for items with more than two response options (i.e., polytomous items).

#### One-parameter logistic model - Rasch Model:

- The simplest IRT model is called the *Rasch model* or the *one-parameter logistic model* (1PL). According to this model, a person's response to a binary item is determiend by the individual's trait level and only a signle item characteristic or parameter: the item's difficulty.
- One way of expressing the Rasch model is in terms of the probability that a person with a particular trait level will correctly answer an item that has a particular difficulty. This can be presented as:

$$ P(X_{is} = 1 | θ_{s}, β_{i}) = e^{(θ_{s} - β_{i})} / 1 + e^{(θ_{s} - β_{i})} $$

In the above equation:
 - $P$ refers to probability. In this case, it refers to a "conditional" probability
 - $X_{is}$ refers to a particular response (*X*) made by subject *s* to item *i*. More specifically, $X_{is} = 1$ refers to a "correct respnse" or an endorsement of the item
 - $θ_{s}$ refers to the trait level of subject *s*
 - $β_{i}$ refers to the difficulty of item *i*
 - *e* is the base of the natural logarithm

- So,  $P(X_{is} = 1 | θ_{s}, β_{i})$ refers to the probablity (*P*) that subject *s* will respond to item *i* correctly. The vertical bar in this statement indicates that this is a "conditional" probability. That is, it indicates that the probability that the subject will respond correctly to the item is conditional upon (i.e., *depends on*) the person's trait level and the item's difficulty. (As mentioned earlier, in an IRT analysis, trait levels and item difficulties are usually scaled on a standardized metric, so that their means equal 0 and their standard deviations equal 1.)
- Remember that the item difficulty difficulty represents the trait level at which a person will have a 50:50 chance of correctly answering the item. So, if a person's trait levle is slightly higher than the item's difficulty level, then the probability that the person will correctly answer the item is slightly higher than .50.
- In sum, the 1PL model is intended to reflect the connections between respondent trait level, item difficulty level, and the probablity of correctly answering a binary item.
- Based on the mathematical connections defined in such models, and based on a set of actual responses from multiple test takers, we can estimate values for the parameters in the model. That is, **we can estimate a trait level for each person and a difficulty level for each item**. Once we know, or have estimated respondents' trait levels and the item's difficulty levels, we can estimate the probability that each respondent will correctly answer each item.
- To sum up, the 1PL model is a relatively simple model, as it applies only to binary items and includes only one item parameter: item difficulty. Other IRT measurement models are more complex, in that they include additional parameters.

#### Two-parameter logistic model

- A slightly more complex model is the *two-parameter logistic model* (2PL), because it includes two item parameters.
- **According to the 2PL, a person's response to an items is determined by the person's trait level, the item difficulty, and the item discrimination**.
- So, the difference between the 2PL and the 1PL (or Rasch model) is the inclusion of the item discrimination parameter in the 2PL model. This can be presented as:

$$ P(X_{is} = 1 | θ_{s}, β_{i}, α_{i}) = e^{α_{i}(θ_{s} - β_{i})} / 1 + e^{α_{i}(θ_{s} - β_{i})} $$

In the above equation:
- $α_{i}$ refers to the discrimination of item *i*, with higher values representing more discriminating items

All other terms are defined as in the 1PL model:
- $P$ refers to probability. In this case, it refers to a "conditional" probability
- $X_{is}$ refers to a particular response (*X*) made by subject *s* to item *i*. More specifically, $X_{is} = 1$ refers to a "correct respnse" or an endorsement of the item
- $θ_{s}$ refers to the trait level of subject *s*
- $β_{i}$ refers to the difficulty of item *i*
- *e* is the base of the natural logarithm

For example, consider the case where there is a relatively large difference in trait level between two people, but a relatively small difference in the likelihood of naswering the item correctly. Thus, the item does not seem to reflect the difference between the respondents very well: the people are quite different in terms of trait level, but they are not very different in terms of the likelihood that they will answer the item correctly. The difference in trait levels is not clearly reflected by the difference in their probabilities for this item. That is, the item does not discriminate very robustly between people at different trait levels. Generally, the item with a high discrimination value draws a more robust distinction between individuals who have different trait levels. This type of information may be used to select items for a test, opting for items with greater discrimination values.

#### Obtaining parameter estimates: A 1PL example

- In real-world research, we would not have knowledge about the values of trait level item difficulty, and item discrimination. Obtaining estimates of these parameters is precicely one of the main reasons why we might conduct an IRT-based analysis in the first place.