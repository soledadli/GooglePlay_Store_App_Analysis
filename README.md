# GooglePlay_Store_App_Analysis
<p>The notebook intends to analyse over ten thousand apps from Google Play Store apps to devise pricing strategies.</p>
<p>The data consists of two files:</p>
<ul>
<li><code>apps.csv</code>: contains all the details of the applications on Google Play. There are 13 features that describe a given app.</li>
<li><code>user_reviews.csv</code>: contains 100 reviews for each app. <a href="https://www.androidpolice.com/2019/01/21/google-play-stores-redesigned-ratings-and-reviews-section-lets-you-easily-filter-by-star-rating/">The ranking is based on the contribution to the sentiment analysis</a>. The text in each review has been pre-processed and attributed with three new features: <br> <strong>Sentiment</strong> (Positive, Negative or Neutral), <strong>Sentiment Polarity</strong> and <strong>Sentiment Subjectivity</strong>.</li>
</ul>
    
<p><strong>Structure</strong>
<ol>
<li>Import Packages</li>
<li>Dataset Information</li>
<li>Data Cleaning</li>    
<li>Exploring app categories</li> 
<li>Distribution of app ratings</li> 
<li>Size and price of an app</li> 
<li>Relation between app category and app price</li> 
<li>Filter out "junk" apps</li> 
<li>Popularity of paid apps vs free apps</li> 
<li>Sentiment analysis of user reviews</li> </ol></p>
<p><strong> Features to work wiht</strong>:
<br> <code>Installs</code>, <code>Size</code>, <code>Rating</code> and <code>Price</code> 
    
<p><strong>Key Findings</strong>:
<ol>
<li>Categories about <strong> personal growth and management</strong> tend to have higher rates. 
<ul>
    <li>Top 5 Ratings: <em>Event (4.4), Education, Art_and_Design, Books_and_Reference, Personalization</em></ul></li>
<li>Large Market Share and large installments does not help with app ratings 
    <ul>
 <li> <em>Tools</em> holds the third largest market share and the third largest installment times, but is rated as the third from the bottom.</ul></li>
<li>The downloading difference between paid/free apps are, unexpectedly, <strong> relatively low</strong></li>
<li>From the sentiment analysis, it shows that free apps receive lots of negative comments, which is within expectations</li>
</ol>
