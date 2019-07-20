# The Tower Of Bible
https://bigmark641.github.io/TheTowerOfBible/index.html

## Summary
**The goal of this was to create a web page that could pull a Bible chapter from an API and randomize all its words using a theusarus API.**

## Instructions
**The radio buttons:**

The "Means like" option queries synonyms for each word.  The "Sounds like" option finds words that sound like the original, but doesn't consider their meanings.

**The "Word quality threshhold" slider:**

Each word comes back from the API with a score.  Having the slider all the way to the right always chooses the highest scoring word, while having it all the way to the left will select any of the returned words.  The starting value of 80% means that the word's score must be at least 80% of the highest scoring word.

## Disclaimers
I believe the thesaurus API has a daily limit of something like 20,000 words.

The code is really messy, and maybe I'll go back and clean it up someday.
