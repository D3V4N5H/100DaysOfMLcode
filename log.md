My name is Devansh Trivedi and this is the log of my progress in the 100 Days of ML code challenge

I'm following guidelines from this Siraj video: [100 Days of ML Code Challenge](https://youtu.be/cuQMBj1cWPo)

**The idea is simple:**
1. Pick an industry
2. Find a Problem
3. Locate a Dataset
4. Apply AI to Data
5. Create a Solution

# Day 0: September 18, 2018
[**Full Report on Medium Article**](http://sync.dvnsh.com/mlday0)
## Today's Progress:
✅ Step 1: Picked Music Industry  
✅ Step 2: Found a Problem: ProActive Music Selection  
✅ Made Word-Pair Frequency Graph in Neo4j using Cypher language
Used Starboy lyrics csv
## Thoughts:
This idea comes from a movie as old as me, Flubber (1997).  
Robin Williams plays 'The Professor' with this cute flying robot 'Weebo'. It [uses memes to communicate](https://youtu.be/3iO14Rxdrwk)  
It always has the perfect cartoon/clip for the occasion. I felt such need for sound effects in my life.  
Some songs are perfect for some moods and contexts.  
Hopefully, I will be able to code an AI so everyone can train it to their taste, and experience music effortlessly.  

The idea is simple: The song should match the environment. Initially, I will try **Lyrics Text Analysis** to match the lyrics with the words spoken.  
Then **Linguistic Analysis** of song lyrics will help me detect and interpret emotions, social tendencies, and language style to analyze emotions and feelings that musical artists express in their songs.
## Link to work: [StarBoy Repository](https://github.com/D3V4N5H/StarBoy)

# Day 1: September 19, 2018
[**Full Report on Medium Article**](http://sync.dvnsh.com/mlday1)
## Today's Progress:
✅ Coded together a Python script with officially supported 'idiomatic' Neo4j Python driver v1 to use GraphDatabase
## Thoughts:
NLP is possible to implement natively in Node4j using Cypher queries.  
However, the ability to access it from python will open doors to many new possibilities
## Link to work: [StarBoy.py](https://github.com/D3V4N5H/StarBoy/blob/master/StarBoy.py)

# Day 2: September 20, 2018
[**Full Report on Medium Article**](http://sync.dvnsh.com/mlday2)
## Today's Progress:
✅ Fetch word frequencies into a Python dictionary  
To achieve this, I'm using Auto-commit transactions in the driver's session.
## Thoughts:
I concluded that a dictionary would be the right data structure to store the frequencies of each word
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/962e549919bba2d6375cb52ae856419f19cad604)

# Day 3: September 21, 2018
[**Full Report on Medium Article**](http://sync.dvnsh.com/mlday3)
## Today's Progress:
✅ Word-Pair Frequency into Python Dictionary with tuples as keys and count as values
## Thoughts:
I made the variable name easier to read.  
Now that I have the Text Adjacency Graph, I can go ahead for the Mining Word Associations
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/05c96ab331569f1831943aa3d168921935e88888)

# Day 4: September 22, 2018
[**Full Report on Medium Article**](http://sync.dvnsh.com/mlday4)
## Today's Progress:
✅ Implemented Left1, Right1, Count Left1 and Right1, Find highest Left1 and Right1  
✅ Uploaded starboy.csv  
✅ Created a list of queries on Github repository for everyone else to try the same
## Thoughts:
I was amazed by the fact that the grammar articles "the" and "a" came out to be the most frequent Adjacent nodes in the graph.
I'm not sure how implementing Left2 and Right2 will help me, and how to implement those the right way.
## Links to work:
[starboy.csv](https://github.com/D3V4N5H/StarBoy/blob/master/starboy.csv)  
[Queries](https://github.com/D3V4N5H/StarBoy/blob/master/CypherQueries)

# Day 5: September 23, 2018
[**Full Report on Medium Article**](http://sync.dvnsh.com/mlday5)
## Today's Progress:
✅ Mining Paradigmatic Word Associations using Jaccard Index to compute similarity
## Thoughts:
Very successful, many interesting discoveries  
Yet I'm still surprised and sad that the AI could not find similarity of the word "starboy"
## Links to work:
[Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/bf55b72c9c85170b2f14980bc574d8b7dcd79929)

# Day 6: September 24, 2018
[**Full Report on Medium Article**](http://sync.dvnsh.com/mlday6)
## Today's Progress:
✅ Graph based Summarization and Keyword Extraction
## Thoughts:
I'm grateful for, yet disappointed by TextRank  
I will now work on comparing my results with the environment
## Links to work:
[Commit: Queries in starboyGraphQueries.cql](https://github.com/D3V4N5H/StarBoy/commit/97fc56baf9c71e07e20a2175a10f770b617efe9a)  
[TextRank Python code](https://github.com/D3V4N5H/StarBoy/blob/master/TextRank.py)

# Day 7: September 25, 2018
## Today's Progress:
✅ Working on a Jupyter notebook on Content Recommendation
## Thoughts:
I now need datasets more than ever.  
MusixMatch has  
43 million tracks  
14 million lyrics  
## Link:
[Jupyter Notebook](https://github.com/johnymontana/nlp-graph-notebooks/blob/master/Content%20Recommendation.ipynb)

# Day 8: September 26, 2018
## Today's Progress:
✅ Designing 'The Song Attribute Graph' data model and schema for Content Based filtering and Recommendation
## Thoughts:
I'm advocating content based recommmendations at this stage of the project  
Today I had to guess what parameters can be taken into account to find patterns that match the environment  
To keep my project simple, I have chosen Release Date, Featuring Actor, Genre AND Keywords
## Link:
[Commit with Queries](https://github.com/D3V4N5H/StarBoy/commit/b48685dfa9f8a13574be17c33f666fc340185d8a)

# Day 9: September 27, 2018
## Today's Progress:
✅ Created python script to generate User Preference and Song Attributes Graph for Content-based Recommendations  
✅ Signed up for and MusixMatch API, got API key and Studied its documentation
## Thoughts:
I wanted to create separate functions for queries to add user, add song, add metadata and link. But because of the limitation of query variables, their scope only exists with the query. So I had to create a common function. If I still wanted to create separate ones, I'd need to MATCH them before making associations to a new variable, which would further complicate the code. I will have a workaround in Python to remedy this by creating query templates and loops.
## Link to work:
[New python script to generate User Preference and Song Attributes Graph](https://github.com/D3V4N5H/StarBoy/commit/2dd791e57beaf098c6879e8c50f3b6e831b53c70)
