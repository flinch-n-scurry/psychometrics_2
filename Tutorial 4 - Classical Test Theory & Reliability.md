# Psychometrics II - Prep Notes

## Week 4 - Reliability in Classical Test Theory

1. Classical Test Theory (CTT)

CLassical Test Theory is a measurement theory that defines the conceptual basis of reliability and outlines procedures for estimating the reliability of psychological measures.
According to CTT, a test's reliability reflects the extent to which **the differences in respondents' test scores are a function of their true psychological differences**, instead of measurement error. Whetehr we are using a measure for research purposes or for applied purposes, we want all our measures to be highly reliable.
Often, we treat reliability as if it an all-or-none issue, with a test being either reliable or unreliable. However, reliability is a **continuum**, a procedure for measuring something will be more or less reliable. Reliability is also a theoretical notion. Reliabilty is a feature of the results of procedures for measuring characterictis of objects or psychological characteristics of people. Just as a psychological characteristic such as intelligence is an unobserved feature of a person, so is reliability an unobserved feature of test scores. And just like we must estimate a person's level of intelligence, we must *estimate a test's reliability*.

**According to CTT, reliability derives from observed scores, true scores, and measurement error**.
-> Observed scores are values that are obtained from measuring a characteristic in a sample of individuals.
-> True scores are the real amounts/true values of that characteristic in that sample of individuals. (*e.g. a person's score on an intelligence test would be an observed score, and this person's true intelligence would be a true score*) (Another definition of the true score: the average score that a participant would obtain if they completed the scale an infinite number of times, or the score that would be obtained if the test or measurement was perfectly precise and thus unaffected by measurement error)

Ideally, we want to interpret people's observed scores as good estimates of their true scores because most behavioural research and decision making are intended to reflect respondents' true pschological characteristics.

Considering the concepts of observed scores and true scores, *reliability* is thus the extent to which differences in respondents' observed scores are consistent with differences in their true scores. More specifically, the reliability for a measurement procedure depends on the extent to which differences in respondents' observed scores can be attributed to differences in their true scores, as opposed to other, often unknown, test administration characteritics.

-> The extent to which these "other" characteristics contribute random noise to measurements is called **measurement error**, or just error, because they create inconsistency between observed scores and true scores.

**To evaluate the reliability of scores from any measure, we must estimate the extent to which individual differences in observed scores are a function if true or reals score differences among respondents**. We can think of reliability in terms of signal and noise. In this framework, true socres are the signal that we would like to detect, and measurement error is the noise that is obscuring the signal and making it difficult to detect. Reliability can then be seen as a ratio of signal and noise:

**$Reliabiliy = Signal/Signal + Noise$**

From this perspective, reliability is stongest when theire is a strong signal and/or little noise. Reliability depends on two things: (1) the extent to which differences in test scores can be attributed to real inter- or intra-individual differencces, and (2) the extent to which differences in test scores are a function of measurement error. In CTT, a person's observed score on a test is a function of that person's true score, plus error. If $Χ$<sub>0</sub> represents a person's observed test score, $X$<sub>t</sub> is the person's true score on the psychological characteristic, and if $X$<sub>e</sub> is the amount of error affecting ther person's responses, then we can write the following formula to represent this assumption:

$Χ$<sub>0</sub> $=$ $Χ$<sub>t</sub> $+$ $Χ$<sub>e</sub>

Again, the first fundamental assumption of CTT is that observed scores on a psychological measure are determined by respondents' true scores and by measurement error.

CTT makes an iportant assumption about measurement error. Specifically, CTT assumes that error occurs as if it is random. In part, this means that measurement error is just as likely to inflate any particular score as it is to decrease any particular score. We assume that people's responses to a psychological test are affected in unpredictable ways that might make their observed scores artificially high or artificially low. There are two important consequences of this assumption about error. First, error tends to cancel itself out across respondents. In other words, error inflates the scores of some respondents and deflates the scores of other respondents in such a way that the average effect of error across respondents is 0. The second consequence of the apparent randomness of error is that error scores are uncorrelated with true scores. In other words, error affects observed scores in ways that are independent of the respondents' true scores. So, if we compute the correlation between a person's true scores and their error scores, the correlation is exactly 0 (i.e., $r$<sub>te</sub> $= 0$).

#### Variances in observed scores, true scores, and error scores

Reliability reflects the degree to which differences in observed scores are consistent with differences in true scores. In other words, reliability depends on the links among observed score variablity, true score variability, and error score variability. A high degree of error variablity (**error variance**) indicates the potential for poor measurement.

Using the standard formula for variance, we can compute the variance for the observed scores, the variance for the true scores, and the variance for the error scores. Assuming that a person's observed score is the sum of their true score and error score, and that measurement error is random, it follows that the total variance of the observed scores from a group of individuals equals the sum of the true score and error score variances:

$s$<sup>2</sup><sub>o</sub> $=$ $s$<sup>2</sup><sub>t</sub> $+$ $s$<sup>2</sup><sub>e</sub>

**Conclusion: The observed score variance is the sum of the true score variance and the error score variance**.

(**Note:** We might expect that the variance of the observed score will be equal to true score variance plus error variance plus the covariance of true scores and error scores. However, as mentioned, we assume that error is independent of true scores, which implies that the correlation {$r$} between error scores and true scores is 0.)

#### Four ways to think of reliability

In CTT, there are four ways to think about reliability. Each one arises from the associations among observed scores, true scores and measurement error. The approaches may differ only with respect to the methods used to algebraically arrange the terms associated with these variances, or represent different was of conceptualizing/characterizing the concept of reliability.

These 4 approaches reflect 2 distintions in the conceptualization of reliability. The distinctions are whether an approach conceptualizes reliability in terms of:
-> "proportion of variance" or correlations
-> observed scores as related to true scores or to measurement error


<span style="color:red"> **1. Reliability as the ratio of true score variance to observed score variance** </span>

In this case, reliability is defined as the proportion of observed score variance that is attributable to true score variance:

$$

R_{XX} = s^{2}_{t} / s^{2}_{o},

$$

where $R_{XX}$ is the reliability coefficient.

For example, if we have a reliability coefficient of .48, then this value tells us that about 48% of the differences that we see among respondents' observed scores can be attributed to differences among their true trait levels.

The size of the reliability coefficient indicates a test's reliability. Reliability ranges between 0 and 1, and larger $R_{XX}$ values indicate greater psychometric quality. This is because, as $R_{XX}$ increases, a greater proportion of the differences among observed scores can be attributed to differences among true scores. **If true score variance is 0, then reliability is 0.** This underscores the fact that reliability is tied to diffrences among people: if respondents don't differ in the characteristic being assessed by a test (i.e., if $s^{2} = 0$), then the test's reliability is 0 for those respondents. If true score variance is equal to observed score variance, the $R_{XX} = 1$. This would indicate that there is absolutely no measurement error affecting observed scores. In reality, measurement error always occurs to some degree.

<span style="color:red"> **2. Reliability as lack of error variance** </span>

A second way of conceptualizing reliability is in terms of a lack of measurement error. Error variance represents the degree to ehich error affects different people in diffrent ways- artificially inflating some people's scores and artificially deflating other people's scores. These effecs obscure the true differences among people. Therefore, reliability can be viewed as the degree to which error variance is minimal in comparison with the variance of observed scores.

We've already mentioned that **reliabilty can be seen as the proportion of observed score variance that is attributable to true score variance**:

$$ R_{XX} = s^{2}_{t} / s^{2}_{o} $$

We've also noted that **observed score variance is the sum of true score variance and error variance**:

$$ s^{2}_{o} = s^{2}_{t} + s^{2}_{e} $$

First, we rearrange the equation above algebraically:

$$ s^{2}_{t} = s^{2}_{o} - s^{2}_{e} $$

Then, we substitute this result into the numerator of the first equation:

$$ R_{XX} = s^{2}_{o} - s^{2}_{e} / s^{2}_{o} $$

$$ R_{XX} = s^{2}_{o}/ s^{2}_{o} - s^{2}_{e}/ s^{2}_{o} $$

$$ R_{XX} = 1 - s^{2}_{e}/ s^{2}_{o} $$

We note that:

$$ s^{2}_{e}/ s^{2}_{o} $$

represents the proportion of observed score variance that is a function of error variance. When this proportion is small, the reliability is high. In other words, **reliability is high when error varaince is small in comparison with observed score variance**.

For example, when $s^{2}_{e}/ s^{2}_{o} = 0.52,$ 52% of the variance in respondents' observed scores is produced by measurement error, leaving only a remaining 48% attributable to true score differences among the respondents.

<span style="color:blue"> **What would a small degree of error variance indicate?** </span> *It would indicate that the respondents'scores are being affected only sligtlyby measurement error. More specifically, it would indicate that the error affecting one person's score is not very different from the error affecting another perosn's score.*  
