# NLP project

Natural Language Processing is a way to help computers understand and process the human language.  I wanted to wrap my head around the libraries available and I thought of something I have wanted to do for a while now.

The challenge I’ve always had when working in retail, was to understand what my customers thought about the store I ran.  It was easy to keep an eye out on google reviews and maintain client relationships one on one; but wouldn’t it be easier to focus on what customer were telling me need to improve or wish I had so they could spend more ?
I wanted to identify this using python and I felt like this would be a great idea for a project that would give me a quick glance at what my customers are pointing to.
You can grab the same data set <a href="https://www.kaggle.com/datasets/arushchillar/disneyland-reviews">here</a>.

I have linked the GitHub link <a href="https://github.com/Frozenbabypeas/NPL-Disneyland_analysis">here</a>.

# Problem statement:

1. What is the skew of reviews we are getting?
2. Is it worthwhile to focus on getting better results?
3. What are the negative reviews saying?
4. Where should we put our efforts in?

A quick summary:  the data will have some missing information.  I’m not after the date when the reviews were posted.  To answer the problem statement, I will need to understand the sentiment of the review. 

## Solutions to the problem statement:

#### What is the skew of reviews we are getting?

We can see that the majority of reviews are done in California while the least are in Paris.  Both California and Hong Kong have a good Average Rating whereas Paris is the lowest, even though there are more reviews in Paris than in Hong Kong.  Will this mean that our customers in Paris don't appreciate the attraction more than the other resort?

#### Is it worthwhile to focus on getting better results?

We can see that there are high reviews with negative sentiments and low reviews with positive sentiments.  What this means is that there are elements in the review that were good and elements that were bad.  More reviews can give better insights in these areas.

#### What are the negative reviews saying?

From our poor reviews, 10% of our clients had something positive to say.  And from our poor reviews, 4.7% of our clients had the worst things to say.

#### Where should we put our efforts in?

Europe and Caribbean ranked highest in our location category.  The Caribbean attraction should be looked at.  HK Disney ranked highest with our organisation category.  Chances are they had a terrible experience here and should be investigated.

Alternatively, people loved Space Mountain from our location category which is Great news!.  Hong Kong Disney ranked highest as well in our organisation category, odd that they ranked highest in both positive and negative sentiments, it could be used as a comparison.  The good news is that it is spoken a lot of times in the reviews even though it’s had the least reviews which would mean that there is potential value in the Hong Kong amusement park.

# Future Changes

I will work on a getting live reviews, like getting something from Google.  The google reviews are a great way to find more sentiments of what our customers think about product offerings and changes to the business.

I would like to have presented the findings better but had issues with the Dash library that hasn't been resolved.  Maybe using Canva would make the information more readable.