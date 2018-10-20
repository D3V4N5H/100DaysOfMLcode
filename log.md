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
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/bf55b72c9c85170b2f14980bc574d8b7dcd79929)

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
## Link: [Jupyter Notebook](https://github.com/johnymontana/nlp-graph-notebooks/blob/master/Content%20Recommendation.ipynb)

# Day 8: September 26, 2018
## Today's Progress:
✅ Designing 'The Song Attribute Graph' data model and schema for Content Based filtering and Recommendation
## Thoughts:
I'm advocating content based recommendations at this stage of the project  
Today I had to guess what parameters can be taken into account to find patterns that match the environment  
To keep my project simple, I have chosen Release Date, Featuring Actor, Genre AND Keywords
## Link to work: [Commit with Queries](https://github.com/D3V4N5H/StarBoy/commit/b48685dfa9f8a13574be17c33f666fc340185d8a)

# Day 9: September 27, 2018
## Today's Progress:
✅ Created python script to generate User Preference and Song Attributes Graph for Content-based Recommendations  
✅ Signed up for MusixMatch API, got API key and Studied its documentation
## Thoughts:
I wanted to create separate functions for queries to add user, add song, add metadata and link. But because of the limitation of query variables, their scope only exists with the query. So I had to create a common function. If I still wanted to create separate ones, I'd need to MATCH them before making associations to a new variable, which would further complicate the code. I will have a workaround in Python to remedy this by creating query templates and loops.
## Link to work: [New python script to generate User Preference and Song Attributes Graph](https://github.com/D3V4N5H/StarBoy/commit/2dd791e57beaf098c6879e8c50f3b6e831b53c70)

# Day 10: September 28, 2018
## Today's Progress:
✅ Fetched Top Artists using chart.artists.get
## Thoughts:
Following APIs are paid:
track.search
track.subtitle.get
matcher.subtitle.get
## Link to work: [Script to fetch popular artists in India (use your own api key please)](https://github.com/D3V4N5H/StarBoy/blob/master/mxm%20chart.artists.get.py)

# Day 11: September 29, 2018
## Today's Progress:
✅ Updated Python script to Iterated over names of Top Artists in #India from JSON response
## Thoughts:
Now I will combine both python files : The one that fetches data and the one that fires queries to generate nodes in the graph database to associate data.
## Link to work: [Commit to python code](https://github.com/D3V4N5H/StarBoy/commit/61e9663bd47823fd453d3970cf08a3664f256065)

# Day 12: September 30, 2018
## Today's Progress:
✅ Another API call to get songs of Top Artists in India  
✅ Show these associations in the neo4j Graph Database
## Thoughts:
I need more metadata, as I couldn't get some info about tracks from MusixMatch API
## Link to work: [That new python file I thought about making yesterday](https://github.com/D3V4N5H/StarBoy/blob/master/userArtistSongMap.py)

# Day 13: October 1, 2018
## Today's Progress:
✅ Fixed Top Artists for India (country parameter was for US) API call  
✅ Added Top Tracks in India list
## Thoughts:
track.snippet.get didn't work for starboy track_id 144134659, not even in the playground

I'm planning to use the following to compute relevance:  
chart.tracks.get  
chart.artists.get  
matcher.track.get  
track.get  
artist.albums.get  
matcher.lyrics.get  
track.lyrics.get
## Link to work: [Commit to the Fix](https://github.com/D3V4N5H/StarBoy/commit/2bbfafbfbf6a8d2d75d7d5c859c4ba35b9e0b9e8)

# Day 14: October 2, 2018
## Today's Progress:
✅ Made a function to handle APIs better  
✅ Combined approach: Finding Best songs OF Best artists
## Thoughts:
I tested lyrics by watching the Starboy video on Youtube with MusixMatch Chrome Extension and it worked fine.  
This proves that they DO have the lyrics with them.  
But I'm not able to find the lyrics programmatically.  
Now I will try to get metadata, eventually reflecting those in the Graph.
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/425803542ad62e053110398b8d9fd56baa5f9326)

# Day 15: October 3, 2018
## Today's Progress:
✅ Convert listOfTracks to a dictionary with track_name, track_id as values  
✅ Fetch and Parse the Release Date
## Thoughts:
Now I have the Release Date Metadata, but that's not it. A Date Object is convenient in Python. I'm not sure it's a good move to store that information as Node in Graph. I might have to come up with a Hybrid approach if I can't sort it out tomorrow.
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/ae74585ad3f3b1fb100d357af3923cfe42b62d5b)

# Day 16: October 4, 2018
## Today's Progress:
✅ Dropped the getReleaseDateFromTrackId function in favour of iterating from data in Top Tracks which already had the dates
## Thoughts:
The function I defined was taking too long to execute, as it was fetching track details for every top artist's every single top track. That's too many API calls (about 100, depending on number of items).  
After inspecting data from previous API calls, I noticed that if I could iterate into the nested dictionary inside tuple inside list inside the callback (phew)!
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/71ac6ad7a1ca1f3e931c9676031b9b0f20a31443)

# Day 17: October 5, 2018
## Today's Progress:
✅ Take Top Tracks in the geographical place as Training Data for AI
## Thoughts:
At this point my project seems to be leaning towards Collaborative filtering based on other users' activity
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/b4d7072baf1a33bc71a3befdc23b9df0b0196957)

# Day 18: October 6, 2018
## Today's Progress:
✅ Finally managed to fetch lyrics of Top Songs in #India songs to train the AI  
✅ Made API method much better
## Thoughts:
I'm not able to fetch the whole lyrics. I'll work with what I have now.  
I'm planning to take Top Tracks of India as Training Data and use Top Artists' Songs to find recommendations.
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/4ef724a446cf1e2bd85d277156942b2b29603f35)

# Day 19: October 7, 2018
## Today's Progress:
✅ Cleared other parts in the lyrics, so it's much more readable now (Compared to yesterday)  
✅ Refactored the code
## Thoughts:
This is where my previous work about generating weighted keywords can pitch in to UNDERSTAND the lyrics.
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/08cbeb7d3c51b4fcb50dd5675bd20917c04a4e86)

# Day 20: October 8, 2018
## Today's Progress:
✅ New Python file to parse the #StarBoy lyrics  
✅ Removed background vocals in brackets
## Thoughts:
Genius.com [resources](https://genius.com/3317959) helped understand parts of the lyrics  
The data in my file is analogous to the csv file that I manually generated at the beginning of the project. Getting lyrics is now officially automated !!
## Link to work: [Commit to New File](https://github.com/D3V4N5H/StarBoy/commit/5b38af182c69b2dff9036bcb3ed21881456430f9)

# Day 21: October 9, 2018
## Today's Progress:
😭 Failed to import line by line lyrics into @neo4j (without using CSV)
## Thoughts:
Tried doing this for 4 Hours. It's too complicated.

# Day 22: October 10, 2018
## Today's Progress:
✅ [Michael Hunger](https://twitter.com/@mesirii) helps me import the data to the graph  
✅ Mining Paradigmatic Word Associations in lyrics from API calls
## Thoughts:
Today's date is 10 on 10 (10/10), and so was my progress.  
As I was wondering why the word frequency from the API fetched lyrics didn't match that of the CSV lyrics, it was comforting to recollect that I don't get FULL lyrics from the free account. Hence the difference.  
Despite that, my mining was very accurate.

I was tempted to use an iterator for the word-by-word query but when it didn't work, so I sticked with coding that part from the scratch.
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/4695d4e1dd30ea86528356ef4bdaa57a0d3a7cbd)

# Day 23: October 11, 2018
## Today's Progress:
✅ Create nodes from words of ALL top tracks in india
## Thoughts:
I tried to create nodes with separate labels for each song, but it seems that's not possible. So now I will have to mine each of the tracks one-by-one inside the same loop instead of batch mining !
## Link to work: [Commit Creating 'Mining Top Tracks in india.py](https://github.com/D3V4N5H/StarBoy/commit/00d2ea4feb035da7aaa1321d38fdf6ecab2a7dec)

# Day 24: October 12, 2018
## Today's Progress:
✅ Adding names of songs as Labels using APOC
## Thoughts:
Now I can batch-mine all songs in the graph, and know which song a particular cluster of nodes belongs to :D  
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/7217f4048ee686811c6213cb4d08d780940353bb)

# Day 25: October 13, 2018
## Today's Progress:
✅ Mining from Lyrics of Songs
## Thoughts:
Some words are repeated as nodes. I will need to debug this, as most weighted pairs are the same words in the results
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/c4667d792249211593b6eb52e816e72f125eb72a)

# Day 26: October 14, 2018
## Today's Progress:
👀 Deep inspection of the mined data
## Thoughts:
I found multiple nodes(at least two) with same words  
Something is wrong. I'm expecting unique nodes.
## Link to image: [pic on Twitter](https://pbs.twimg.com/media/DpkJRxoW0AMHxT0.jpg:large)

# Day 27: October 15, 2018
## Today's Progress:
✅ Refactor the Mining process
## Thoughts:
After refactoring the mining process, another instance of the mined graph indicates that the issue has prevailed.
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/756852ee834a0cf661b6c036ac9df221c55558e1)

# Day 28: October 16, 2018
## Today's Progress:
✅ Underscored Variable names for readability  
🕵🏻‍♂️Found issues in parsing of lyrics
## Thoughts:
I have no idea of the weird unexpected codes I'm looking at. This has never happened before.
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/6634918160f8f6fe396c5aecb6c445ce0de45e30)

# Day 29: October 17, 2018
## Today's Progress:
✅ Implemented query and calls with a different approach to prevent duplicate nodes before Mining
## Thoughts:
Finally it works as intended, can't wait to fetch and display keywords mined from each song now !
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/72161604f84be9c3a9c80fd0bef7fe57d27cfb13)

# Day 30: October 18, 2018
## Today's Progress:
⚙️ Importing weighted keywords from mined graph
## Thoughts:
The script is taking significant time to execute
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/9e1298606051cf92607e7d5ca67d6af6f5b129e4)

# Day 31: October 19, 2018
## Today's Progress:
⚙️ Trying different approaches to read Response code from the BoltStatementResult object
## Thoughts:

## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/aed6b05e5feae8ce5078f08342286a4b4402ef24)

# Day 32: October 20, 2018
## Today's Progress:
✅ Learned Pypher  
✅ Finally imported from Graph (though strangely all weights are 1.0)
## Thoughts:
I couldn't find how Pypher could help me access records from the graph, so I implemented the code without it
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/924311c7c81b6eee7b7f11fc6c68a75b16e23d01)
