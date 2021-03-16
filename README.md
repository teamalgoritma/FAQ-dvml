This repository contains a Frequently Ask Question about data visualization and machine learning

# Contents:
- Data Wrangling
- Data Visualization and Interactive Plotting
- Regression Model
- Classification 1
- Classification 2
- Unsupervised Learning
- Time Series
- Neural Network and Deep Learning

# Contributing Articles

Please follow the submission guidelines below:

1. Fork the repository.
   
   a. On github, navigate to the [](https://github.com/teamalgoritma/FAQ-dvml) repository.
   b. On the top-right corner of the page, click *fork*.
   c. Keep your fork synced using Git. If you haven't yet, you should first [set up Git](https://docs.github.com/en/github/getting-started-with-github/set-up-git#setting-up-git).
   d. On github, click **fork** on the *algoritmablog* repository.
   e. Open Git Bash
   f. Type `git clone`, and then paste the URL of repository. It will look like this, with your GitHub username instead of `YOUR-USERNAME`:

```   
`$ git clone https://github.com/YOUR-USERNAME/algoritmablog`
```
   g. Press **Enter**. Your local clone will be created.

```   
$ git clone https://github.com/wulanandriyani/FAQ-dvml.git
Cloning into 'FAQ-dvml'...
remote: Enumerating objects: 864, done.
remote: Counting objects: 100% (864/864), done.
remote: Compressing objects: 100% (596/596), done.
remote: Total 864 (delta 374), reused 668 (delta 186), pack-reused 0
Receiving objects: 100% (864/864), 18.29 MiB | 1.12 MiB/s, done.
Resolving deltas: 100% (374/374), done.
Updating files: 100% (491/491), done.
```   

2. Make a development version and add your article.
   
   a. Add questions according to the section in the content above in the respective Rmd file
   b. After you finished, Open your console and type `bookdown::render_book("gitbook")` for rendering the file  
   c. On folder book delete index.html and rename FAQ.html to index.html
   
3. Submit a pull request.
   
   a. Open git bash
      
      * `git add .`
      * `git commit -m 'your message'`
      * `git push`
   
   b. then submit a pull request to algoritma blog repository.

If the project owner agrees with your work, they will merge your request into the original repository.
