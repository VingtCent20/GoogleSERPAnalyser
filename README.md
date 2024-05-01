# GoogleSERPAnalyser
Can scrap any Google SERP of any keyword to determine similarity and avoid cannibalization

SET UP: 
- Choose your google region. In the "url=" line, please use the google link from the keyword region. If your keywords are in French, use google.fr.  
- On the line "search_terms =", please give all of your keywords (KW) into the two brackets [ ].
- Run the program. The code launches and gradually tells you the keywords it is analyzing. When it is finished it will show you the similarity percentages between all the keywords.

WITH OR WITHOUT TIMER? 
- If you want to compare less than 100 KW, you don't have to use any timer. I still recommand to wait a couple of minutes to avoid google IP ban.
- If you want to compare more than 100 KW, I recomand to use the code with the timer.
- With more than 200-250 KW, a timer is mandatory to avoid IP ban.

HOW TO EDIT SOME OPTIONS? 
- 



A few comments :
- The code compares URLs accurately and analyzes the first 10 URLs in the SERP for each keyword. 1 similar URL = 10% similarity.
- When the similarity is 20% or less, the code displays the keyword as "unique".
- When the similarity is 50% or more with this tool, for me it is cannibalization.
- When the similarity is 30% or 40%, I advise you to check the SERP manually and/or use other similar tools (12pages and/or Haloscan) to compare the results, then make a decision arbitrarily.
- It is common to identify +/-10% or even +/-20% difference from one analysis to another and depending on the tools used and when you are using it.

Common errors:
- "Check your keyword or your connection": When you misuse the code, Google may temporarily block your IP (waiting a couple of hours or changing your connection will solve the problem). The query limit in a single session is 250 keywords. I advise you not to run more than 100 keywords in a row and not to restart the code for several minutes. Also avoid running the same code twice at the same time and if you stop the code wait at least a few seconds before running it again. To run more keywords, use a the timer version.
- "Syntax error": there is often a problem with the given keywords. Punctuation is prohibited, check that the quotation marks " " are closed for each keyword and that all the keywords are in closed brackets [ ].
