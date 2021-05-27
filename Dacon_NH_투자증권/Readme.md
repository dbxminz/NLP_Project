## "Find the Real News."

#### This is a "Find the Real News" contest held by NH Investment & Securities. 

⭐Process <br/>
Simple preprocessing and models show high performance.

- Test dataset sentences that match train dataset's fake news sentences were classified as fake news.
- Test dataset sentences that match train dataset's real news sentences were classified as real news.

- Sentences containing words that usually appear in real news, such as "기자","밝혔다","말했다","설명했다","전했다","했다","예정이다","덧붙였다" were classified as real news. </br>
(These words were very infrequent in fake news.)

⭐Result <br/>
- RNN :96.6%
- Naive Bayes : 96.5%
