Run `npm install` and add Openai key in .env

Step 1: make sure analysis.json is empty. 

Step 2: run node `review_analyzer.js --url "Googleplay store app url" --out analysis.json` 

Step 3: then run `node summarize_reviews.js` 

For a different game, clean analysis.json and repeat from step 1.
