# [ml4fin] Machine Learning for Finance

Course No. 351699001

Class 2026 Fall, NCCU, Taipei.

Instructor: Richard Dien Giau Bui

[`Introduction`](#introduction)  | [`Lectures`](#lectures) |
[`FAQ`](#faq) | [`License`](#license)


## Introduction

This is a graduate course taught by Richard Dien Giau Bui at the National Chengchi University (NCCU). Here is the course description, taken from the syllabus:

> Introduction to machine learning methods with applications in financial markets, risk management, asset pricing, and empirical finance research. The course emphasizes prediction, model evaluation, economic interpretation, and the reading and replication of influential academic papers.

> The course combines between foundation theories (using one must-read textbook ISLR/ISLP), recent research in finance journals, and the empirical practice (lab). Each topic is covered by a simple empirical lab to show the students the practical examples and how to employ the machine learning models into practice and research. The students must have basic understanding about empirical research and programming skills (either R or Python).



Please read the full description at [Syllabus website](https://newdoc.nccu.edu.tw/teaschm/1151/schmPrv.jsp-yy=115&smt=1&num=351699&gop=00&s=1.html).


## Lectures

### Slides:

1. Class Introduction: [md](00_intro.qmd), [html](https://raw.githack.com/diengiau/ml4fin/main/slides/00_intro.html)
2. Statistical learning: [pdf](https://raw.githack.com/diengiau/ml4fin/main/slides/Ch2_Statistical_Learning.pdf), [python lab](https://colab.research.google.com/github/intro-stat-learning/ISLP_labs/blob/v2.2/Ch02-statlearn-lab.ipynb)
3. Linear regressions: [pdf](https://raw.githack.com/diengiau/ml4fin/main/slides/Ch3_Linear_Regression.pdf), [python lab](https://colab.research.google.com/github/intro-stat-learning/ISLP_labs/blob/v2.2/Ch03-linreg-lab.ipynb)
4. Classification: [pdf](https://raw.githack.com/diengiau/ml4fin/main/slides/Ch4_Classification.pdf), [python lab](https://colab.research.google.com/github/intro-stat-learning/ISLP_labs/blob/v2.2/Ch04-classification-lab.ipynb)


### Recommended textbook:

-   James, Gareth, Daniela Witten, Trevor Hastie, and Robert Tibshirani, 2023. An introduction to statistical learning: with applications in Python. New York: Springer. **\[ISLP\]**
-   James, Gareth, Daniela Witten, Trevor Hastie, and Robert Tibshirani, 2021. An introduction to statistical learning: with applications in R New York: Springer. **\[ISLR\]**

### Journal list (to be updated):

**Machine Learning**
1.  Dong, X., Y. Li, D. E. Rapach, and G. Zhou. 2022. Anomalies and the Expected Market Return. The Journal of Finance 77 (1): 639-681.
1.  Gu, S., B. Kelly, and D. Xiu. 2020. Empirical Asset Pricing via Machine Learning. The Review of Financial Studies 33 (5): 2223-2273.
1. Bao, Y., B. Ke, B. Li, Y. J. Yu, and J. Zhang. 2020. Detecting Accounting Fraud in Publicly Traded U.S. Firms Using a Machine Learning Approach. Journal of Accounting Research 58 (1): 199–235.
1. Leippold, M., Wang, Q. and Zhou, W., 2022. Machine learning in the Chinese stock market. *Journal of financial economics*, *145*(2), pp.64-82.
1. Bianchi, D., Büchner, M. and Tamoni, A., 2021. Bond risk premiums with machine learning. *The Review of Financial Studies*, *34*(2), pp.1046-1089.
1. Bell, S., Kakhbod, A., Lettau, M. and Nazemi, A., 2026. Glass box machine learning and corporate bond returns. *Journal of Financial Economics*, *181*, p.104294.
1. Bali, T.G., Beckmeyer, H., Moerke, M. and Weigert, F., 2023. Option return predictability with machine learning and big data. *The Review of Financial Studies*, *36*(9), pp.3548-3602.
1. Avramov, D., Cheng, S. and Metzker, L., 2023. Machine learning vs. economic restrictions: Evidence from stock return predictability. *Management Science*, *69*(5), pp.2587-2619.
1. Chen, X., Cho, Y.H., Dou, Y. and Lev, B., 2022. Predicting future earnings changes using machine learning and detailed financial data. *Journal of Accounting Research*, *60*(2), pp.467-515.
1. Kaniel, R., Lin, Z., Pelger, M. and Van Nieuwerburgh, S., 2023. Machine-learning the skill of mutual fund managers. *Journal of Financial Economics*, *150*(1), pp.94-138.
1. DeMiguel, V., Gil-Bazo, J., Nogales, F.J. and Santos, A.A., 2023. Machine learning and fund characteristics help to select mutual funds with positive alpha. *Journal of Financial Economics*, *150*(3), p.103737.


**Text Analysis**
1. Engle, R. F., S. Giglio, B. Kelly, H. Lee, and J. Stroebel. 2020. Hedging Climate Change News. The Review of Financial Studies 33 (3): 1184–1216.
1.  Li, K., F. Mai, R. Shen, and X. Yan. 2020. Measuring Corporate Culture Using Machine Learning. The Review of Financial Studies (hhaa079).
1. Harrison, J. S., G. R. Thurgood, S. Boivie, and M. D. Pfarrer. 2019. Measuring CEO personality: Developing, validating, and testing a linguistic tool. Strategic Management Journal 40 (8): 1316-1330.
1. Buehlmaier, M. M. M., and T. M. Whited. 2018. Are Financial Constraints Priced? Evidence from Textual Analysis. The Review of Financial Studies 31 (7): 2693–2728.
1. Hoberg, G., and C. Lewis. 2017. Do fraudulent firms produce abnormal disclosure? Journal of Corporate Finance 43: 58-85.
1. Li, F. 2008. Annual report readability, current earnings, and earnings persistence. Journal of Accounting and Economics 45 (2). Economic Consequences of Alternative Accounting Standards and Regulation: 221-247.
1. Das, S. R., and M. Y. Chen. 2007. Yahoo! for Amazon: Sentiment Extraction from Small Talk on the Web. Management Science 53 (9): 1375-1388.
1. Florackis, C., Louca, C., Michaely, R. and Weber, M., 2023. Cybersecurity risk. *The Review of Financial Studies*, *36*(1), pp.351-407.
1. Bybee, L., Kelly, B. and Su, Y., 2023. Narrative asset pricing: Interpretable systematic risk factors from news text. *The Review of Financial Studies*, *36*(12), pp.4759-4787.

**LLM**
1. Brown, A. B., V. X. Wang, and A. Zhou. 2025. Employee Perceptions of Corporate Culture and Management Forecast Accuracy: Evidence from Glassdoor and ChatGPT. Accounting Horizons: 1-20.
1. Cheng, Q., P. Lin, and Y. Zhao. 2025. Does generative AI facilitate investor Trading? Early evidence from ChatGPT outages. Journal of Accounting and Economics: 101821.
1. Ming, J., H. Malloch, and P. J. Westerholm. 2024. Can ChatGPT Replicate Analyst Recommendations? SSRN Scholarly Paper. Rochester, NY: Social Science Research Network.
1. Lopez-Lira, A. and Tang, Y., 2026. Can chatgpt forecast stock price movements? return predictability and large language models. Journal of Financial Economics, 184, p.104335.

**Computer Vision**
1. Cao, S., W. Jiang, J. Wang, and B. Yang. 2024. From Man vs. Machine to Man + Machine: The art and AI of stock analyses. Journal of Financial Economics 160: 103910.
1. Christensen, T. E., K. E. Fronk, J. A. Lee, and K. K. Nelson. 2024. Data visualization in 10-K filings. Journal of Accounting and Economics 77 (2): 101631.
1. Jiang, J., B. Kelly, and D. Xiu. 2023. (Re-)Imag(in)ing Price Trends. The Journal of Finance 78 (6): 3193–3249.
1. Peng, L., S. H. Teoh, Y. Wang, and J. Yan. 2022. Face Value: Trait Impressions, Performance Characteristics, and Market Outcomes for Financial Analysts. Journal of Accounting Research 60 (2): 653–705.
1. Obaid, K. and Pukthuanthong, K., 2022. A picture is worth a thousand words: Measuring investor sentiment by combining machine learning and photos from news. Journal of Financial Economics, 144(1), pp.273-297.

**Others**
1. Gofman, M. and Jin, Z., 2024. Artificial intelligence, education, and entrepreneurship. The Journal of Finance, 79(1), pp.631-667.

## FAQ

TBA.

## License

The material in this repository is made available under the [MIT license](http://opensource.org/licenses/mit-license.php).

