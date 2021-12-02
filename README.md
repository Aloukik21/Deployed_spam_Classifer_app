# Spam detection web app using streamlit
# Streamlit
Streamlit lets you turn data scripts into sharable web apps in minutes, not weeks. It’s all Python, open-source, and free! And once you’ve created an app you can use our cloud platform to deploy, manage, and share your app!

```
pip install streamlit
```

# How to run
run spam.py file in cmd, using following command:
```
streamlit run spam.py
```
# Naive Bayes

What is Naive Bayes algorithm?
It is a classification technique based on Bayes’ Theorem with an assumption of independence among predictors. In simple terms, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature.

For example, a fruit may be considered to be an apple if it is red, round, and about 3 inches in diameter. Even if these features depend on each other or upon the existence of the other features, all of these properties independently contribute to the probability that this fruit is an apple and that is why it is known as ‘Naive’.

Naive Bayes model is easy to build and particularly useful for very large data sets. Along with simplicity, Naive Bayes is known to outperform even highly sophisticated classification methods.

Bayes theorem provides a way of calculating posterior probability P(c|x) from P(c), P(x) and P(x|c). Look at the equation below:

![image](https://user-images.githubusercontent.com/30460954/144509697-763075bc-eecc-4587-a4b3-5178f3767acc.png)

Above,

1. P(c|x) is the posterior probability of class (c, target) given predictor (x, attributes).
2. P(c) is the prior probability of class.
3. P(x|c) is the likelihood which is the probability of predictor given class.
4. P(x) is the prior probability of predictor.

# Demo:
![ezgif com-gif-maker (4)](https://user-images.githubusercontent.com/30460954/144508976-074f53bb-b64c-438f-9409-908d0eb75995.gif)
