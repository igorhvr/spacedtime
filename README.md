# SpacedTime
Remember the important things in life. Permenantly store informaiton in your brain, not the cloud. Using spaced time repition techniques, we will create an app that allows you to easily recall and memorize. 

## How to get started

```
1. yarn global add spacedtime
2. spacedtime add "What is my anniversary" "2010-10-10"
3. spacedtime recall //this will now pull a question for you to remember
```

## SpacedTime recall
This will ask you the question. Traditional time spaced reptition apps do not ask you input your answer. It only asks if you were able to remember. 

```
> spacedtime recall
What is your anniversary?

Press Any Key to Continue ...

"2010-10-10"

Did you remember successfully? yes(y) or no(n)
y

congrats, we are going to ask you again later in 60 minutes
```

Given how frequently you answer yes, the question will be asked less over time. If you answer no, you'll be asked this question more frequently.
