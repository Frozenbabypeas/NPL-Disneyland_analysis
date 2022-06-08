# NLP project

Natural Language Processing is a way to help computers understand and process the human language.  The NLP libraries from python are powerful tools to grab a text and assign it a category.  There are many methods in doing this.

The challenge I’ve always had when working in retail, was to understand what my customers thought about the store I ran.  Yes, its easy to look at a review and keep tabs on what people are saying about the business.  But when you're taking all this information from many sources, or you have a large data set, its just one more task that would eventually overload you and move you away from reaching goals.  I wanted to create a solution this using python and I felt like this would be a great idea for a project that would give me a quick glance at what my customers are pointing to.  If there was just one category that my customers are pointing to, life would be soo much easier!

You can grab the same data set <a href="https://www.kaggle.com/datasets/arushchillar/disneyland-reviews">here</a>.

For simplicity, I focused on the spaCy and text.blob libraries.  These libraries will help me idenitfy the words, tag then categorise them into thier sentiments.  My mission here is to learn more about the customer and understanding the category of the review will help solve our problem statement.

# Problem statement:

1. What is the skew of reviews we are getting?
2. Is it worthwhile to focus on getting better results?
3. What are the negative reviews saying?
4. Where should we put our efforts in?

A quick summary:  the data will have some missing information.  I’m not after the date when the reviews were posted.  To answer the problem statement, I will need to understand the sentiment of the review. 

## Solutions to the problem statement:

### What is the skew of reviews we are getting?

We can see that the majority of reviews are done in California while the least are in Paris.  Both California and Hong Kong have a good Average Rating whereas Paris is the lowest, even though there are more reviews in Paris than in Hong Kong.  Will this mean that our customers in Paris don't appreciate the attraction more than the other resort?

### Is it worthwhile to focus on getting better results?

We can see that there are high reviews with negative sentiments and low reviews with positive sentiments.  What this means is that there are elements in the review that were good and elements that were bad.  More reviews can give better insights in these areas.

### What are the negative reviews saying?

From our poor reviews, 10% of our clients had something positive to say.  And from our poor reviews, 4.7% of our clients had the worst things to say.

### Where should we put our efforts in?

#### From our negative scores in the ratings below 5 stars (the worst of the worst):
Europe and Caribbean ranked highest in our location category.  This analysis would suggest that the Caribbean attractions should be looked at.  HK Disney ranked highest with our organisation category.  Chances are they had a terrible experience here and should be investigated.

#### From our positive scores in the ratings below 5 stars (the best in the worst):
Alternatively, people loved Space Mountain from our location category which is Great news!.  Hong Kong Disney ranked highest as well in our organisation category, odd that they ranked highest in both positive and negative sentiments, it could be used as a comparison.  It's interesting to see Hong Kong written a lot of times in the reviews even though it’s had the least reviews.  This would mean that there is potential value in the Hong Kong amusement park.

You can find the notebook at this <a href="https://github.com/Frozenbabypeas/NPL-Disneyland_analysis">GitHub link</a>.

# Future Changes

I will work on a getting live reviews, like getting something from Google.  The google reviews are a great way to find more sentiments of what our customers think about product offerings and changes to the business.

I would like to have presented the findings better but had issues with the Dash library that hasn't been resolved.  Maybe using Canva would make the information more readable.