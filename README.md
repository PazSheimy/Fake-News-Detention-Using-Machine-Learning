# Fake-News-Detention-Using-Machine-Learning
# Fake News Detection With Transformer Models
# REU Data Science and AI FGLSAMP Fall 2021
# Sheimy Paz1, Jonathan Burrel2, and Yohn Jairo Parra, PhD3
# Affiliation, Town/City, Country
# Florida A&M University/Tallahassee, USA
# Abstract. 
The advent of the digital world and the acceptance of social
media have bring along many advantages to society. However,The easy
access to news at low cost has enable the fast dissemination of fake and
misleading information. Fake news have a significant negative societal
effects and is a serious problem that our society is facing today that
lead to confusion and misunderstanding about important social, polit-
ical, technological, medical and environmental issues and trusting false
information lead to wrong decisions about important social issues. Auto-
mated classification of a text article as misinformation or disinformation
using technologies like data mining are emerging with the purpose of
lead society into a positive and educated world. This project propose a
data mining method with the use of transformers. Introducing the basic
concepts and characteristics of the process used by the model and its
advantages(reference) [6]

# Keywords: News, Fake News, Transformers.

# 1 Introduction
# 1.1 Danger of Fake News.
Fakes news is any false or misleading content presented as news and communi-
cited in formats spanning spoken, written, printed, electronic, and digital com-
munication. Fakes news is designed to manipulate people’s perception of reality
causing social conflict and misinformation in society.

# 1.2 Why is the fake news problem Important to Society.
Let’s see some definitions for fake news that can help us to understand the
danger of fakes news: Misinformation: Some spread false information without
the intent to spread harm. People spreading misinformation believe it to be true
before sharing it with others. Disinformation: People may spread information
to cause harm or manipulate people. Disinformation describes actual lies that
people tell for money, influence, or to cause the disorder. Malformation: Information
that may be true but is spread with malicious intent or taken out of context.

2 F. Author et al.
Examples include divulging private information or manipulating facts to fit a
false narrative.

A question like how we are going to combat the climate change if fake news
discredit all scientific efforts made to solve this issue with made up a slogan to grab
the consumer attention stating that climate change does not exist. Making any
confused readers to take an unhealthy decision about our planet’s care.
1.3 Approaches used and Solutions founded by similar Research
Approaches like verifying if the headline and body text match, detecting mis-
matched sentences in the body text and identifying dissemination of fake news
is done using deep learning techniques, machine learning, or rule-based methods
for detentions.[7]

# 1.4 Why do we use BERT-based transformers instead of GPT?
Let’s look at some of the differences between BERT (Bidirectional Encoder Repre-
sentations from Transformers) and GPT (Generative Pre-trained Transformer).
GPT Transformers are language models known to produce text like humans.
Both BERT and GPT became the most popular deep learning models achieving
state-of-the-art across many NLP tasks.[8, 9]
Title Suppressed Due to Excessive Length 3
[8]
[8]
We chose to use BERT in our project instead of GPT because BERT is
an open-source tool is easily available for users. GPT on the other hand is not
open-sourced. It has limited access to users. Other of another capability of BERT is it
bidirectional nature making it more suitable for detecting inaccurate information
with an 80.4 percent General Language Understanding Evaluation(GLUE) and a
93.3 percent of accuracy.[8]
1.5 Let’s introduce PyTorch
Pytorch is an open-source machine learning library that is based on the Torch
1. Author, F.: Article title. Journal 2(5), 99–110 (2016)
2. Author, F., Author, S.: Title of a proceedings paper. In: Editor, F., Editor, S.
(eds.) CONFERENCE 2016, LNCS, vol. 9999, pp. 1–13. Springer, Heidelberg (2016).
https://doi.org/10.10007/1234567890
3. Author, F., Author, S., Author, T.: Book title. 2nd and. Publisher, Location (1999)
4. Author, A.-B.: Contribution title. In: 9th International Proceedings on Proceedings,
pp. 1–2. Publisher, Location (2010)
5. LNCS Homepage, http://www.springer.com/lncs. Last accessed 4 Oct 2017
6. Fake News and Alternative Facts: Finding Accurate News: Why is Fake
News Harmful? https://researchguides.austincc.edu/c.php?g=612891p=4258046.
Last accessed 4 July 2021
7. Jwa, H., Oh, D., Park, K., Kang, J. and Lim, H., 2021. exBAKE: Automatic Fake
News Detection Model Based on Bidirectional Encoder Representations from Trans-
formers (BERT). https://www.mdpi.com/2076-3417/9/19/4062/htm
8. Group, 3., 2021. GPT vs BERT in Artificial Intelligence- 360DigiTMG. [online]
360digitmg.com. https://360digitmg.com/gpt-vs-bert. Last accessed 22 November
2021
9. Huggingface. co. 2021. Transformers. [online] Available at:
https://huggingface.co/transformers/ [Accessed 22 November 2021].
