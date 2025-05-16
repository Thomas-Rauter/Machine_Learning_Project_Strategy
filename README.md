# Machine Learning Project Strategy

This repository is a curated collection of resources focused on the 
**strategic and practical aspects** of executing machine learning projects — 
not the theory of models or algorithms. These resources focus on decision 
making in real machine learning projects.

In other words, this is about the *art and strategy* of machine learning: 
deciding on which problems to work on in the first place, knowing when to 
collect more data, deciding for the right learning algorithms for your 
problem, knowing what the best strategies are to deploy your model, etc.

This list includes textbooks, guides, cheatsheets, links to courses, and ebooks 
that I have written (also available as `.tex` files) that explore these themes.

When the resources were freely available, I directly linked them here with 
the PDF to download (the titles are linked), otherwise, I linked to the website 
where they are available (for purchase).

---

## 📚 Resources

### [Machine Learning Engineering – Andriy Burkov](https://drive.google.com/file/d/1TquRrTp-nsZYCYYE-UNVp_y_lsglPWF8/view?usp=sharing)

A concise but broad book that covers the end-to-end lifecycle of machine 
learning systems. It’s not a deep dive into algorithms — instead, it focuses 
on **design decisions**, **system architecture**, **monitoring**, and 
**real-world constraints** in ML projects. Ideal for engineers and 
practitioners who need to bridge the gap between experimentation and production.

---

### [Machine Learning Yearning – Andrew Ng](https://drive.google.com/file/d/1oEFiyoxlkZT8ocqCNiCMMHLa9MgDpopr/view?usp=sharing)

This book provides a practical guide to structuring machine learning 
projects effectively. It emphasizes strategies for setting up training and 
test sets, selecting appropriate evaluation metrics, and conducting error 
analysis. Aimed at practitioners, it offers insights into diagnosing issues 
like bias and variance, and making informed decisions about model design and 
iteration.

---

### [Coursera: Machine Learning in Production – Andrew Ng](https://www.coursera.org/learn/introduction-to-machine-learning-in-production)

This course teaches how to design and manage the full lifecycle of machine 
learning systems in production. It covers choosing deployment and monitoring 
strategies, improving model performance by focusing on critical data slices, 
and handling real-world data challenges — from inconsistent labels to 
working with both small and large, structured and unstructured datasets.

---

### [Coursera: Structuring Machine Learning Projects – Andrew Ng](https://www.coursera.org/learn/machine-learning-projects)

This course focuses on the strategic decision-making needed to lead 
successful ML projects. It covers diagnosing and reducing model errors, 
handling mismatches between training and test data, and deciding when to use 
techniques like transfer learning or end-to-end models. Geared toward 
aspiring ML leaders, it distills hard-earned industry experience into a 
practical framework for managing complex ML development challenges.

---

### [Building Machine Learning Powered Applications – Emmanuel Ameise](https://drive.google.com/file/d/1EgQvOkIdzW8TaEPL3VkvWJ9TCz_4A-RB/view?usp=sharing)

This book provides a practical, end-to-end guide for developing machine 
learning applications, focusing on the entire lifecycle from concept to 
deployment. Ameisen emphasizes starting with simple, rule-based solutions to 
validate ideas before introducing ML components. The book covers key aspects 
such as data collection, model training, evaluation, deployment, and 
monitoring. It also discusses the importance of aligning ML solutions with 
business objectives and includes real-world examples and interviews with 
industry professionals to illustrate common challenges and best practices.

---

### [Machine Learning Algorithm Cheatsheet – Microsoft Azure](https://drive.google.com/file/d/1AOpHXBeJEcc1EKzY1_1nwuV6STjDcIQ1/view?usp=sharing)

This cheat sheet helps you choose the best machine learning algorithm for 
your predictive analytics solution. 
Your decision is driven by both the nature of your data and the goal you 
want to achieve with your data.

---

### [Scikit Learn Algorithm Cheat Sheet](https://drive.google.com/file/d/1i_FoEc3f-HS8NIWeCTBZvOUGCp731u07/view?usp=sharing)

Similar to the one above but from Scikit Learn. It essentially is a decision 
tree that helps you decide which algorithm to use for your problem. I 
personally find that it ignores top algorithms, such as XGBoost and Neural 
Networks, which surprises me. But it a well known cheat sheet, and I find it 
still helpful.

---

### [Rules of Machine Learning – Google](https://developers.google.com/machine-learning/guides/rules-of-ml)

Google made a webpage with 43 practical rules for machine learning. Those 
rules are short and quite dense in information. They are for advanced 
practioners, and some of them are quite specific. They are not really 
necessary when you just work on private projects, but I am sure are 
invaluable as soon as you are working in large real world projects and want 
to make the best decisions.

---

### [Hidden Technical Debt in Machine Learning Systems (Google Research)](https://drive.google.com/file/d/1VVVJ4jP6hlm9WUcr-8PTVpnJMbNAAhDV/view?usp=sharing)

A seminal paper that introduced the idea of "ML technical debt." It explains 
how ML systems tend to accumulate complexity over time — through 
configuration, data dependencies, monitoring, etc. Useful for understanding 
why ML in production is hard, and why traditional software engineering 
intuition often fails in ML contexts.

---

### My ebook 1: Navigating Machine Learning Projects

This book is similar to the book Machine Learning Engineering from Andriy 
Burkov. It is about how to make effective decisions in real world machine 
learning projects. For example, you might have great knowledge about neural 
networks and know exactly how to technically implement them. You train one, 
but the prediction performance is not good enough. What do you do now? Do 
you train a bigger neural network? Or a smaller one? Or do you collect more 
data? Or do you fix the labels? In ML projects, you will face many such 
decisions, and you rarely have enough time to try out all options. This book 
helps you to make smart decisions in all the stages of the ML project 
lifecycle, which includes scoping, data, modeling, insights, and deployment.

📄 **Download Versions**:
- [v0.2.1](https://drive.google.com/file/d/1gKLJnRJP-NZ2LitpHEZH3PKT3TgFsf_k/view?usp=sharing)

Note: I uploaded the .tex document of this ebook to this repo. However, this 
ebook contains several figures, and many of them I generated with custom 
Python scripts. Therefore, this ebook has its [separate GitHub repo](https://github.com/Thomas-Rauter/Navigating-Machine-Learning-Projects).

---

### My ebook 2: Organising Machine Learning Projects

This book is about best practices and guidelinesfor organising ML projects. It 
covers environment and dependency management, best practices for Git commits,
documentation of the different levels of a project (project, data, model, 
and code), experiment logging and tracking, dataset versioning, and model 
storage and versioning. While many things written down in this book can be 
considered common sense, I know from my own experience that one too easily 
throws them overboard or never starts doing those things, because one "does 
not have the time for this", or "as long as I work on the project, I 
remember all the things". Simple private project might not suffer from a 
lack of organisation, but when a project goes over months and multiple 
people are working on it, a poor organisation soon can be come a nightmare. 
This book attempts to adress this. 

📄 **Download Versions**:
- [v0.1.0](https://drive.google.com/file/d/1DkmUbE2-YYde9TxsPjORo_MMUvzeGEMU/view?usp=sharing)

---


## 💬 Feedback

I would love to hear your thoughts. When think something in those books or 
resources is incorrect (especially in the ones I have written) then you can 
open an issue and start a discussion like this. Thank you!
