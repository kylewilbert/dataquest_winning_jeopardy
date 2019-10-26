# Dataquest Guided Project: Winning Jeopardy
*This is a Guided Project I completed for the Data Analyst/Data Science path on Dataquest. Dataquest does provide solution code that is available while completing this project. As a result, I do not claim that all of this code is mine or original. At times when I got stuck or when my code didn't fit the direction of the guided analysis, I matched their code for the sake of completing the exercise and learning the structure of the analysis.
So while the code is not 100% original or unique, I believe one of the strengths of these projects is that it helps students like me identify business problems where analysis like this can be valuable. As a result, I'm confident that I can adapt this particular analysis to similar business problems I may face in my day-to-day work.*

## Introduction
Let's say you want to compete on Jeopardy, and you're looking for any edge you can get to win. In this project, you'll work with a dataset of Jeopardy questions to figure out some patterns in the questions that could help you win.

### Methods Used
- data cleaning/processing
- chi-squared testing

### Technologies Used
- Python
    - Pandas
    - Numpy
    - Scipy/chisquare

## Next Steps
Here are some potential next steps:

- Find a better way to eliminate non-informative words than just removing words that are less than 6 characters long. Some ideas:
    - Manually create a list of words to remove, like the, than, etc.
    - Find a list of stopwords to remove.
    - Remove words that occur in more than a certain percentage (like 5%) of questions.
- Perform the chi-squared test across more terms to see what terms have larger differences. This is hard to do currently because the code is slow, but here are some ideas:
    - Use the apply method to make the code that calculates frequencies more efficient.
    - Only select terms that have high frequencies across the dataset, and ignore the others.
- Look more into the Category column and see if any interesting analysis can be done with it. Some ideas:
    - See which categories appear the most often.
    - Find the probability of each category appearing in each round.
- Use the whole Jeopardy dataset (available here) instead of the subset we used in this mission.
- Use phrases instead of single words when seeing if there's overlap between questions. Single words don't capture the whole context of the question well.
