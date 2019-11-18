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

From this perspective, reliability is stongest when theire is a strong signal and/or little noise. Reliability depends on two things: (1) the extent to which differences in test scores can be attributed to real inter- or intra-individual differencces, and (2) the extent to which differences in test scores are a function of measurement error. In CTT, a person's observed score on a test is a function of that person's true score, plus error. If $Χ_{o}$ represents a person's observed test score, $X_{t}$ is the person's true score on the psychological characteristic, and if $X_{e}$ is the amount of error affecting ther person's responses, then we can write the following formula to represent this assumption:

$Χ_{o} = Χ_{t} +Χ_{e}$

Again, the first fundamental assumption of CTT is that observed scores on a psychological measure are determined by respondents' true scores and by measurement error.

CTT makes an iportant assumption about measurement error. Specifically, CTT assumes that error occurs as if it is random. In part, this means that measurement error is just as likely to inflate any particular score as it is to decrease any particular score. We assume that people's responses to a psychological test are affected in unpredictable ways that might make their observed scores artificially high or artificially low. There are two important consequences of this assumption about error. First, error tends to cancel itself out across respondents. In other words, error inflates the scores of some respondents and deflates the scores of other respondents in such a way that the average effect of error across respondents is 0. The second consequence of the apparent randomness of error is that error scores are uncorrelated with true scores. In other words, error affects observed scores in ways that are independent of the respondents' true scores. So, if we compute the correlation between a person's true scores and their error scores, the correlation is exactly 0 (i.e., $r_{te} = 0$).

#### Variances in observed scores, true scores, and error scores

Reliability reflects the degree to which differences in observed scores are consistent with differences in true scores. In other words, reliability depends on the links among observed score variablity, true score variability, and error score variability. A high degree of error variablity (**error variance**) indicates the potential for poor measurement.

Using the standard formula for variance, we can compute the variance for the observed scores, the variance for the true scores, and the variance for the error scores. Assuming that a person's observed score is the sum of their true score and error score, and that measurement error is random, it follows that the total variance of the observed scores from a group of individuals equals the sum of the true score and error score variances:

$s^{2}_{o} = s^{2}_{t} + s^{2}_{e}$

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

represents the proportion of observed score variance that is a function of error variance. When this proportion is small, the reliability is high. In other words, **reliability is high when error variance is small in comparison with observed score variance**.

For example, when $s^{2}_{e}/ s^{2}_{o} = 0.52,$ 52% of the variance in respondents' observed scores is produced by measurement error, leaving only a remaining 48% attributable to true score differences among the respondents.

<span style="color:blue"> **What would a small degree of error variance indicate?** </span> *It would indicate that the respondents'scores are being affected only slightly by measurement error. More specifically, it would indicate that the error affecting one person's score is not very different from the error affecting another person's score.*


<span style="color:red"> **3. Reliability as the (squared) correlation between observed scores and true scores** </span>

Reliability is the degree to which differences in observed scores are consistent with differences in true scores. Moreover, the correlation coefficient tells us the degree to which differences in one variable are consistent with (i.e., correspond with) differences in another variable. Therefore, reliability can be seen as the (squared) correlation between observed and true scores:

$$ R_{XX} = r^{2}_{ot} $$

The unsquared correlation between observed scores and true scores is sometimes called the "index of reliability". If we square the index of reliability, we get the coefficient of reliability. When people refer to reliability, they are typically referring to the coefficient of reliability ($$ R_{XX} $$).

To gain a better understanding, we can demonstrate algebraically that the squared correlation between the observed scores and true scores ($r^{2}_{ot}$) is equal to the ratio of the true score variance to the observed score variance ($s^{2}_{e}/ s^{2}_{o}$). (The latter is the most common way of conceptualizing the reliability coefficient.)

A correlation is the covariance divided by the product of two standard deviations:

$$ r_{XY} = C_{XY}/s_{X}s_{y} $$

So, the correlation between observed scores and true scores is:

$$ r_{ot} = C_{ot}/s_{o}s_{t} $$

The covariance between observed scores and true scores is:

$$ c_{ot} = \sum(X_{o} - \bar{X}_{o})(X_{t} - \bar{X}_{t})/N $$

We previously saw that $X_{o} = X_{t} + X_{e}$. **Because the mean error score is assumed to be 0, the mean observed score is equal to the mean true score**. This gives us:

$$ c_{ot} = \sum(X_{t} + X_{e} - \bar{X}_{t})(X_{t} - \bar{X}_{t})/N $$

Algebraically simplifying this equation, we see that the covariance between observed scores and true scores is equal to the sum of (1) the variance in true scores and (2) the covariance between true scores and error scores: $c_{ot} = s^{2}_{t}$. However, we've previously assumed that error scores and true scores are independent and thus are not correlated with each other. (i.e. $r_{te} = 0$ and thus also $c_{te} = 0$). So, **the covariance between observed scores and true scores is simply equal to the variance in true scores**: $c_{ot} = s^{2}_{t}$.

Returning to the correlation between true scores and observed scores we have: $r_{ot} = s^{2}/s_{o}s_{t}$. Simplifying this, we find: %r_{ot} = s_{t}/s_{o}. Squaring this, we see that the squared correlation between observed scores and true scores is equal to the ratio of true score variance to observed score variance:

$$ r^{2}_{ot} = s^{2}_{e}/ s^{2}_{o} $$

Therefore, reliability can be seen as the squared correlation between observed scores and true scores.
-> A reliability of 1 would indicate that the differences among respondents' observed scores are perfectly consistent with the differences among respondents' true scores.
-> A reliability of 0 would indicate that the differences among respondents' observed tests scores are totally inconsistent with the differences among their true test scores. In this case, the test is completely useless as a measure of a psychological characteristic. In practice, reliability is usually in between these two extremes.

<span style="color:red"> **4. Reliability as the lack of (squared) correlation between observed scores and error scores** </span>

Reliability can also be seen as the degree to which observed scores are uncorrelated with error scores. If differences in observed test scores reflect differences in the effects of error (instead of true scores), then the test is unreliable. So, we can say:

$$ R_{XX} = 1 - r^{2}_{oe} $$

where $r^{2}_{oe}$ is the squared correlation between observed scores and error scores.

We have:

$$ R_{XX} = 1 - r^{2}_{oe} = 1 - (s^{2}_{e}/s^{2}_{o}) $$

From the equation above we can see that if the correlation $r_{oe}$ between observed scores and error scores is 0, then $R_{XX}$ will equal 1. As the correlation between observed scores and error scores increases, the size ir $R_{XX}$ will decrease. Thus, reliability will be relatively strong when observed scores have relatively low correlations with error scores.

#### Reliability and the standard error of measurement

Reliability does not directly reflect the size of measurement error associated with a test. In other words, is doesn't tell us, in test score units, the average size of error scores that we can expect to find when a test is administered to a group of people. The size of measurement error has important implications for interpreting the accuracy of test scores and for computing probablities of scores in testing and research settings.

The standard deviation of error scores is a useful way of expressing the amount of error affecting responses to a test. The standard deviation of error scores is called the **standard error of measurement** ($se_{m}$), and is one of the most important concepts in measurement theory. The standard error of measurement represents the average size of the error scores. **The larger the standard error of measurement, the greater the average difference between observed scores and true scores, and the less reliable the test**. A test's standard error of measurement is closely linked its reliability. In fact, we will need to estimate the $se_{m}$ from an estimate of reliability. We can use reliability to find the standard error if measurement:

$$ se_{m} = s_{o} \sqrt{1-R_{XX}}, $$

where $s_{o}$ is the standard deviation of the observed scores, and $R_{XX}$ is the reliability. The value of $se_{m}$ is equal to the standard deviation that is computed directly from the error scores ($s_{e}$). If $R_{XX} = 1$, then $se_{m} = 0$. That is, if there is no measurement error, then reliability will be perfect. Also, $se_{m}$ can never be larger than $s_{o}$. That is, the standard deviation of error scores will always be less that or equal to the standard deivation of observed scores.

### Workbook 4 summary

1. Reliability in Classical Test Theory
2. The evaluation of items in CTT
3. The relationship between item reliability and test reliability
4. The evaluation of test reliability based on internal consistency
5. Uses of test reliability (confidence interval and correction for attenuation)

1. Reliability in CTT

Classical Test Theory (CTT) is about the reliability of test scores. CTT is based on the following equation:

$$ X_{i} = T_{i} + E_{i} $$

Here, $X_{i}$ is the *observed* test score of person i. In psychology, $x_{i}$ is often the sum of person i's item scores, the responses to the items in a test. $T_{i}$ is the *true* score of person i on the test, and $E_{i}$ is the *error* term, reflecting **measurement error**. 

or:

$$ X_{o} = X_{t} + X_{e} $$

(notation varies)

When we administer a psychological test, we consider the variance of the test scores X, $var(X)$ or $σ^{2}_{X}$, as such:

$$ σ^{2}_{X} = σ^{2}_{T} + σ^{2}_{E} $$

or 

$$ var(X) = var(T) + var(E) $$

CTT focuses on estimating the reliability of test scores X, denoted $r_{XX}$. Reliability is defined as the proportion of variance in X ($σ^{2}_{X}$) that is due to/that is attributable to T ($σ^{2}_{T}$):

$$ r_{XX} = σ^{2}_{T} / (σ^{2}_{T} + σ^{2}_{E}) $$
$$ r_{XX} = var(T)/var(T) + var(E) => r_{XX} = var(T)/var(X) $$

**Note**: $r_{XX}$ depends on two unknowns: $var(T)$ and $var(E)$. However, CTT offers different ways to *estimate* the reliability.

-> As the observed score X is often the sum of individual item scores, it is important to first ask whether the items are unidimensional.
-> We can address this question using **factor analysis**.

In CCT, the focus is on the reliability of the sum or test score. However, assuming unidimensionality of the items, CTT also includes methods of item analysis, i.e., methods to evaluate the quality of the individual items. CTT item analysis methods are based on the relationship (correlation) between the item scores and the sum scores, *and based on the variance and means of the individual items*.

We first consider item-level analyses.

##### A. Evaluating individual items: Item-test and item-rest correlations.

We start CTT item analyses with the correlation between the sum score and the item scores, where the sum score ($x_{i}$) is viewed as a proxy for/approximation of $T_{i}$, the respondent's true score.

**Reminder**: In factor analysis, the factor loadings in single common factor (unidimensional) model can be interpreted as standardized regression coefficients, which equal correlations.

If we compare factor loadings with item-test correlations, we will notice that item-test correlations are larger. This is expected, as the test score also includes the item score, which increases the correlation between the test score and the item score. The solution is to base the test score on all the items except the item we are investigating, i.e. *calculate the test score without the item*. **This is called the item-rest correlation**. The item-rest correlation resembles the factor loading.

**In SPSS, the item-rest correlations are shown in the results of a Reliability Analysis, in the column titled "*Corrected-Item Total Correlation*"**.
The factor analysis output also includes "communalities", which we interpret as the proportion of explained variance in the regression of the item on the common factor. Remember, in factor analysis the common factor is used as the predictor, and the individual items as dependent variables. We predict the item scores based on the common factor, i.e., the items are regressed on the common factor. Communalities tell us: How much of the variance in the item score is explained by/attributable to the common factor? <span style="color:red"> **By squaring the item-rest correlations, we get the same kind of information. These are interpretable as item-level reliabilities** </span>.

Let X be the test score and item<sub>1</sub> be the item score. We have the CTT model and the definition of reliability:

$$ X_{i} = T_{i} + E_{i} $$
$$ var(X) = var(T) + var(E) $$

The test reliability is: $var(T)/var(T) + var(E)$

We can apply these definitions to the items. For example:

$$ item_{1i} = T_{item1i} + E_{item1i} and r = var(T_{item1})/var(T_{item1}) + var(E_{item1}) $$

The latter gives us the item reliability of item 1. In a similar way, we can get the item reliability of items2, and so on...

The true score underlying each item is exactly the same: $T_{item1} = T_{item2} = T_{item3}$ etc. Since the items are unidimensional, it follows that each item measures the same undelying variable. So, all the items share the true score, which can be expressed as $T_{item}$. So,we can simplify an item's reliability score as such:

$$ item_{1i} = T_{itemi} + E_{item1i} and r = var(T_{item})/var(T_{item}) + var(E_{item1}) $$
