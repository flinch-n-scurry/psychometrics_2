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
- Recall that the 1PL includes two determinants of an item response: the respondent's trait level and the item's difficulty level. Let's say that we have data from six people who have taken a hypothetical 5-item test of mathematical ability. We will focus first on information about the respondents, and we will estimate a trait level for each of the six people who have taken the test. We will then estimate item difficulties. Estimation usually proceeds through a series of iterative steps in which trait parameters and item parameters are initially estimated, then revised repeatedly until the estimates seem to be as accurate as possible.

- The initial estimates of trait levels are obtained through a two-step process:
- First, we determine the proportion of items that each respondent answered correctly. For a respondent, the proportion correct is simply the number of items that they answered correctly divided by the total number of items they answered. To obtain initial estimates of trait levels, we take the natural log of the ratio of proportion correct to proportion incorrect. 
- Second we obtain the initial estimates of item difficulties. The initial estimates of item difficulties can also be seen as a two-step process. First we determine the proportion of correct responses for each item. For an item, the proportion of correct responses is the number of respondents who answered the item correctly divided by the total number of respondents who answered the item. To obtain estimates of item difficulty, we compute the natural log of the ratio of the proportion of incorrect responses to the proportion of incorrect responses.
- These initial estimates are revised through an iterative series of steps that, ideally, eventually produce final estimates that are as accurate as possible.

#### Item and test information

- Psychometricians using IRT often examine **item characteristic curves** to present and evaluate characteristics of the items on a test.
- Item characteristic curves reflect the probabilities with which individuals across a range of trait levels are likely to answer each item correctly. For item-characteristic curves, the x-axis reflects a wide range of trait levels, and the y-axis reflects probabilities ranging from 0 to 1.0.
- Each item has a curve, and we can examine an item's curve to find the likelihood that a person with any particular trait level will answer the item correctly. So the item characteristic curve provides clues about the likelihood with which individuals of any trait level would answer any item correctly.
- To draw an item characteristic curve for an item, we can repeatedly use a model to compute the probabilities of correct responses for many trait levels. That is, by entering an item's difficulty and a particular trait level, we can calculate the probability with which a person with that particular trait level will answer that item correctly. We can then enter a different trait level into the model, and obtain the probability with which a person with the different trait level will answer the item correctly. After repeating this procedure for many different trait levels, we simply plot the probabilities that we have calculated. The line connecting these probabilities reflects the item's characteristic curve.

- More complex models (i.e., more complex that the 1PL/2PL models) were designed for more complex measurement scenarios, and so have different item characteristic curves.
- Recall that the GRM model was designed for items with more than two response options, and it includes difficulty and discrimination parameters. Analyses based on this model would produce more complex characteristic curves for each of a test's items. Specifically, each item would have several curves, one for each of its response options. In this case, each curve reflects the probabilities with which people of any trait level would choose a particular response option.
- So, each response option has its own information curve, representing the probability that people of any particular triat level will endorse that option. As we move from one curve to another, from left to right in the figure, the options increase in their level of endorsement. That is, for example, *strongly disagree* is farthest left, while *strongly agree* is farthest right. This ordering of the curves parallels, reflects, and is drived by the four difficult parameters (β values) produced by the analysis. These item characteristic curves can convey visual information about the response tendencies associated with each item.

#### Item information and test information

- Psychometricians using IRT often examine **item characteristic curves** to present and evaluate characteristics of the items on a test.
- Item characteristic curves reflect the probabilities with which individuals across a range of trait levels are likely to answer each item correctly. For item-characteristic curves, the x-axis reflects a wide range of trait levels, and the y-axis reflects probabilities ranging from 0 to 1.0.
- Each item has a curve, and we can examine an item's curve to find the likelihood that a person with any particular trait level will answer the item correctly. So the item characteristic curve provides clues about the likelihood with which individuals of any trait level would answer any item correctly.
- To draw an item characteristic curve for an item, we can repeatedly use a model to compute the probabilities of correct responses for many trait levels. That is, by entering an item's difficulty and a particular trait level, we can calculate the probability with which a person with that particular trait level will answer that item correctly. We can then enter a different trait level into the model, and obtain the probability with which a person with the different trait level will answer the item correctly. After repeating this procedure for many different trait levels, we simply plot the probabilities that we have calculated. The line connecting these probabilities reflects the item's characteristic curve.

- More complex models (i.e., more complex that the 1PL/2PL models) were designed for more complex measurement scenarios, and so have different item characteristic curves.
- Recall that the GRM model was designed for items with more than two response options, and it includes difficulty and discrimination parameters. Analyses based on this model would produce more complex characteristic curves for each of a test's items. Specifically, each item would have several curves, one for each of its response options. In this case, each curve reflects the probabilities with which people of any trait level would choose a particular response option.
- So, each response option has its own information curve, representing the probability that people of any particular triat level will endorse that option. As we move from one curve to another, from left to right in the figure, the options increase in their level of endorsement. That is, for example, *strongly disagree* is farthest left, while *strongly agree* is farthest right. This ordering of the curves parallels, reflects, and is drived by the four difficult parameters (β values) produced by the analysis. These item characteristic curves can convey visual information about the response tendencies associated with each item.

#### Item information and test information

- Recall that, from the perspective of Classical Test Theory, *reliability* is an important psychometric consideration ofr a test. In CTT, we might compute Cronbach's alpha as an estimate of a test's reliability. It is important to note that we would compute *only one* reliability estimate for a test, and that one estimate would indicate the degree to which observed test scores are correlated with true scores. The idea is that there is a single reliability for a particular test.
- This is an important way in which CTT differs from IRT.
- For the perspective of IRT, a test score does not have a single "reliability". Instead a test might have stronger psychometric quality for some people than for others. That is, a test might provide better information at some trait levels than at other trait levels.
- The purpose of psychological tests is to detect psychological variability Indeed, the key goal of most psychological testing is to differentiate (i.e., discriminate between) people with relatively high trait levels from people with lower trait levels. From an IRT perspective, a test provides "good information" when it can accurately detect differences between individuals at different trait levels.
- Even a test that has modest psychometric quality should be able to reflect large differences in trait levels. For example, a test with moderate psychometric quality should be able to differentiate between two people with below-average triat scores, on the one hand, and two people with above-average trait scores, on the other.
- However, if we want to reflect much smaller and more subtle differences between test takers, then we would need a test with strong psychometric properties. For example, if we wanted to detect the difference between two people with above-average trait scores, then the test would need to be quite sensitive to differences in trait levels.
- Importantly, IRT allows for the possiblity that a test might be better at reflecting differences at some trait levels rather than at other trait levels. For example, a test might provide better information at high trait levels than at low trait levels.
- In sum, if a test's items have characteristics (e.g., item difficulty levels) that are more strongly represented at some trait levels than at others, then the test's psychometric quality might differ by trait levels. For example, if a mathematics test has items with only high difficulty levels, then it does not provide clear information discriminating among people with low trait levels.

- We can use IRT to pinpoint the psychometric quality of a test across a wide range of trait levels. This can be seen as a two-step process: First we evaluate the psychometric quality of each item across a range of trait levels. Just as we can calculate the probability of a correct answer for an item at a wide range of trait levels, we can use those probabilities to compute information at the same range of trait levels. For the 1PL (Rasch) model, item information can be calculated as such:

$$ I(θ) = P_{i}(θ)(1 - P_{i}(θ)) $$

where $I(θ)$ is the item's information value at a particular trait level ($θ$), and $P_{i}(θ)$ is the probability that a respondent with a particular trait level will answer the item correctly.

- Higher information values indicate higher psychometric quality. For example, an item might have better psychometric quality at reltively low trait levels that at relatively high trait levels. That is, it is more capable of discriminating maong people with low trait levels than at people with high trait levels (presumably because almost everyone with high trait levels will answer the item correctly).
- So, if we compute informtion values at many more trait levels, we could display the results in a graph called an **item information curve**.
- There are some important notes to consider when interpreting item information curves:
1. The height of the curve indicates the amount of information that the item provides, with higher curves indicating greater psychometric quality.
2. The highest point on a curve represents the trait level at which the item provides the most information. An item provides the most information at a trait level that corresponds with its difficulty level.
3. The items differ in the points at which they provide good information. For example, one item couldp rovide good information at relativelt low trait levels, another item could provide good information at average trait levels, wheareas another item might provide good information at relatively high trait levels.

- When we actually use a psychological test, we are usually more concerned with the quality of the test as a whole thatn the qualities of the individual items.
- **So, we can combine item information values to obtain test information values**. Specifically, item information values at a particular trait level can be added together to obtain a test information value at that trait level. For example, the test information score at an average trait level (θ = 0) is simply the sum of the item information values at this trait level.
- Again, it we compute test information scores at many trait levels, we can plot the results in a **test information cuve**.
- A test information curve is useful for illustrating the degree to which a test provides a different quality of information at different trait levels.

- The 1PL/Rasch model only includes one type of item parameter: item difficulty). So, we might see that items can provide maximal information at different trait levels. That is, the items differ in their difficulty, and each one has its best psychometric quality at its specific difficulty level.
- But, of course, item and test information can also be estimated based on other models as well (e.g., 2PL, GRM).
- For models that include both difficulty and discrimination as item parameters, item information curves can vary in two ways. **First**, as we have seen for the 1PL model, the curves can vary in terms of location. That is they can vary in the trait levels at which their maximal information occurs, as refelcted in the fact that the curves "top out" at different points along the *x*-axis. **Second**, item information curves can also vary in terms of height. That is, they can vary in the amount of information that they provide, as reflected in the fact that the curves "top out" at different points long the *y*-axis.
