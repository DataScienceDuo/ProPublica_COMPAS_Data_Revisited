Minor Clarifications
================



<!-- author: "Matias Barenstein" -->

<!-- date: "August 13, 2019" -->

Here I list a few *minor* clarifications regarding some of the writing
in my arXiv and the copy of that paper on GitHub in the file
*ProPub\_COMPAS\_Revisited\_arXiv.md*. (I do make some of these edits in
my more recent *Towards Data Science* [blog
post](https://towardsdatascience.com/the-data-processing-error-in-one-of-the-most-prominent-fair-machine-learning-datasets-4fa205daa3c4?source=friends_link&sk=258477f738e83d46808bc9bb9d34591b),
where I write a summarized version of my paper)

**i.** In the *Abstract, Introduction*, and *Conclusion*, I write:

> ‘I take a new yet simple approach to visualize these data…’

    For clarity, perhaps I should have written instead:

> ‘I take a ***different*** approach to visualize these data…’

    Since I do not want to give the impression that a histogram is a
‘new’ visualization technique. It is *‘new’*  
    only in the sense that I seem to be the first to visualize the
COMPAS screening dates in ProPublica’s two-year  
    recidivism dataset(s).

**ii.** In the *Introduction* I write:

> ‘Doing so, I find that ProPublica made an important data processing
> error creating some of the key datasets most often used by other
> researchers.’

    For clarity, perhaps I should have written instead:

> ‘Doing so, I find that ProPublica made an important data processing
> error creating these ***two-year recidivism sub-datasets***.’

**iii.** In section 3 *ProPublica’s Data Processing Mistake*, perhaps I
should have added the following text for clarity:

> ‘While it is logical not to implement a requirement that recidivists
> be observed outside jail or prison for two years, one should still
> apply a COMPAS screen date cutoff on or before April 1, 2014, for
> them. (But ProPublica failed to do so)’

**iv.** In section 5 *Confusion Matrix*, at the end, when discussing the
results by race, I have the following sentence:

> ‘The utility of focusing on the differences in the FPR and FNR across
> race groups, however, has been called into question by other
> researchers’

    Perhaps I should have added further detail for clarification as
follows:

> ‘The utility of focusing on the differences in the FPR and FNR across
> race groups, however, has been called into question by other
> researchers, *especially when the underlying distribution of risk
> across groups appears to be different*’

**v.** In the last paragraph of the *Conclusion*, for clarity, perhaps I
should have added:

> Many potential measurement issues may affect the estimated recidivism
> rate (as I mention in the Appendix). Some of these could be putting
> downward pressure on the estimate, offsetting to some degree the
> upward bias I identify here. Nevertheless, this does not invalidate
> the data processing issue I identify here and the ensuing data
> correction I call for. My focus is on the *internal validity* of the
> data processing. I am not claiming that after this correction the data
> will be completely accurate, nor have *external* validity. I have not
> explored some of these other potential data issues, and external
> validity is beyond the scope of the analysis in this paper.

Matias Barenstein