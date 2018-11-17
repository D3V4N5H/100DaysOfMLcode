My name is **Devansh Trivedi** and this is the log of my progress in the _100 Days of ML code challenge_

![Image from 100 Days of ML Code Challenge Siraj's Video](https://pbs.twimg.com/media/DnSpGyWX4AAZnSo.jpg)

I'm following guidelines from [Siraj Raval](https://sirajraval.com): Click on the thumbnail below to watch the video

[![100 Days of ML Code Challenge](https://img.youtube.com/vi/cuQMBj1cWPo/0.jpg)](https://www.youtube.com/watch?v=cuQMBj1cWPo)

**The idea is simple:**
1. Pick an industry
2. Find a Problem
3. Locate a Dataset
4. Apply AI to Data
5. Create a Solution

# Find my everyday progress at this  <a href="https://twitter.com/i/moments/1042119370896539649">Twitter Moment</a>


<blockquote>
is this things on?
<br>*microphone screeches*
<br>
<br>*Looks at <a href="https://twitter.com/sirajraval">@SirajRaval</a> @ <a href="https://twitter.com/SchoolOfAIOffic">@SchoolOfai</a>*
<br>*clears throat*<br>
<br>I&#39;m publicly pledging to the <a href="https://twitter.com/hashtag/100DaysOfMLCode">#100DaysOfMLCode</a> challenge starting today!<br>
<br>Learn more @ <a href="dvnsh.com">DVNSH.com</a>
</p>&mdash; <a href="https://twitter.com/devanshRtrivedi">Devansh Trivedi (@devanshRtrivedi)</a> 
<br><a href="https://twitter.com/devanshRtrivedi/status/1041671282411155456">September 17, 2018</a></blockquote>

# Day 0: September 18, 2018
# [**Full Report on Medium Article**](http://sync.dvnsh.com/mlday0)
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
![Starboy NLP image from MusixMatch Developer site](https://pbs.twimg.com/media/DnZZQCkXsAAvZFU.jpg)

# Day 1: September 19, 2018
# [**Full Report on Medium Article**](http://sync.dvnsh.com/mlday1)
## Today's Progress:
✅ Coded together a Python script with officially supported 'idiomatic' Neo4j Python driver v1 to use GraphDatabase
## Thoughts:
NLP is possible to implement natively in Node4j using Cypher queries.  
However, the ability to access it from python will open doors to many new possibilities
## Link to work: [StarBoy.py](https://github.com/D3V4N5H/StarBoy/blob/master/StarBoy.py)
![](https://pbs.twimg.com/media/DnddcjDWsAIafYS.png)
![](https://pbs.twimg.com/media/DnZZQCwXoAAUaR0.jpg)
![](https://pbs.twimg.com/media/DnZZQCoXcAAIJMd.jpg)

# Day 2: September 20, 2018
# [**Full Report on Medium Article**](http://sync.dvnsh.com/mlday2)
## Today's Progress:
✅ Fetch word frequencies into a Python dictionary  
To achieve this, I'm using Auto-commit transactions in the driver's session.
## Thoughts:
I concluded that a dictionary would be the right data structure to store the frequencies of each word
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/962e549919bba2d6375cb52ae856419f19cad604)
![](https://pbs.twimg.com/media/Dnjon_OW4AEM5dY.png)

# Day 3: September 21, 2018
# [**Full Report on Medium Article**](http://sync.dvnsh.com/mlday3)
## Today's Progress:
✅ Word-Pair Frequency into Python Dictionary with tuples as keys and count as values
## Thoughts:
I made the variable name easier to read.  
Now that I have the Text Adjacency Graph, I can go ahead for the Mining Word Associations
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/05c96ab331569f1831943aa3d168921935e88888)
![](https://pbs.twimg.com/media/DnozcbOWwAEZ4pJ.jpg)

# Day 4: September 22, 2018
# [**Full Report on Medium Article**](http://sync.dvnsh.com/mlday4)
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

![](https://pbs.twimg.com/media/Dns5yfpUwAAGaND.jpg)

# Day 5: September 23, 2018
# [**Full Report on Medium Article**](http://sync.dvnsh.com/mlday5)
## Today's Progress:
✅ Mining Paradigmatic Word Associations using Jaccard Index to compute similarity
## Thoughts:
Very successful, many interesting discoveries  
Yet I'm still surprised and sad that the AI could not find similarity of the word "starboy"
## Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/bf55b72c9c85170b2f14980bc574d8b7dcd79929)
![](https://pbs.twimg.com/media/Dn4S4tVU8AEQ_yy.jpg)
![](https://pbs.twimg.com/media/Dn4S6clV4AATEgM.jpg)

# Day 6: September 24, 2018
# [**Full Report on Medium Article**](http://sync.dvnsh.com/mlday6)
## Today's Progress:
✅ Graph based Summarization and Keyword Extraction
## Thoughts:
I'm grateful for, yet disappointed by TextRank  
I will now work on comparing my results with the environment
## Links to work:
[Commit: Queries in starboyGraphQueries.cql](https://github.com/D3V4N5H/StarBoy/commit/97fc56baf9c71e07e20a2175a10f770b617efe9a)  
[TextRank Python code](https://github.com/D3V4N5H/StarBoy/blob/master/TextRank.py)
![](https://pbs.twimg.com/media/Dn4S8v2V4AAuFVi.jpg)
![](https://pbs.twimg.com/media/Dn4TAb4V4AYh-fp.jpg)

## Day 7: September 25, 2018
### Today's Progress:
✅ Working on a Jupyter notebook on Content Recommendation
### Thoughts:
I now need datasets more than ever.  
MusixMatch has  
43 million tracks  
14 million lyrics  
### Link: [Jupyter Notebook](https://github.com/johnymontana/nlp-graph-notebooks/blob/master/Content%20Recommendation.ipynb)


## Day 8: September 26, 2018
### Today's Progress:
✅ Designing 'The Song Attribute Graph' data model and schema for Content Based filtering and Recommendation
### Thoughts:
I'm advocating content based recommendations at this stage of the project  
Today I had to guess what parameters can be taken into account to find patterns that match the environment  
To keep my project simple, I have chosen Release Date, Featuring Actor, Genre AND Keywords
### Link to work: [Commit with Queries](https://github.com/D3V4N5H/StarBoy/commit/b48685dfa9f8a13574be17c33f666fc340185d8a)
![](https://pbs.twimg.com/media/DoCI71DXoAAH6ia.jpg)
![](https://pbs.twimg.com/media/DoCLGOJX0AAlKmi.jpg)
![](https://pbs.twimg.com/media/DoCI6laWkAAhML8.jpg)

## Day 9: September 27, 2018
### Today's Progress:
✅ Created python script to generate User Preference and Song Attributes Graph for Content-based Recommendations  

✅ Signed up for MusixMatch API, got API key and Studied its documentation
### Thoughts:
I wanted to create separate functions for queries to add user, add song, add metadata and link. But because of the limitation of query variables, their scope only exists with the query. So I had to create a common function. If I still wanted to create separate ones, I'd need to MATCH them before making associations to a new variable, which would further complicate the code. I will have a workaround in Python to remedy this by creating query templates and loops.
### Link to work: [New python script to generate User Preference and Song Attributes Graph](https://github.com/D3V4N5H/StarBoy/commit/2dd791e57beaf098c6879e8c50f3b6e831b53c70)
![](https://pbs.twimg.com/media/DoGGcv-XoAA7TxE.jpg)
![](https://pbs.twimg.com/media/DoGGJWmXkAAxEca.jpg)
![](https://pbs.twimg.com/media/DoGGMtRXUAAeljC.jpg)
![](https://pbs.twimg.com/media/DoGGMtaXoAAFzQk.jpg)

## Day 10: September 28, 2018
### Today's Progress:
✅ Fetched Top Artists using chart.artists.get
### Thoughts:
Following APIs are paid:
track.search
track.subtitle.get
matcher.subtitle.get
### Link to work: [Script to fetch popular artists in India (use your own api key please)](https://github.com/D3V4N5H/StarBoy/blob/master/mxm%20chart.artists.get.py)
![](https://pbs.twimg.com/media/DoKkwK3UUAE4HWD.jpg)
![](https://pbs.twimg.com/media/DoKky3UUwAAq35a.jpg)
![](https://pbs.twimg.com/media/DoKk035U4AEZGLs.jpg)
![](https://pbs.twimg.com/media/DoKk4s9UcAAp3o8.jpg)

## Day 11: September 29, 2018
### Today's Progress:
✅ Updated Python script to Iterated over names of Top Artists in #India from JSON response
### Thoughts:
Now I will combine both python files : The one that fetches data and the one that fires queries to generate nodes in the graph database to associate data.
### Link to work: [Commit to python code](https://github.com/D3V4N5H/StarBoy/commit/61e9663bd47823fd453d3970cf08a3664f256065)
![](https://pbs.twimg.com/media/DoSJZzXX0AAjOth.png)

## Day 12: September 30, 2018
### Today's Progress:
✅ Another API call to get songs of Top Artists in India  

✅ Show these associations in the neo4j Graph Database
### Thoughts:
I need more metadata, as I couldn't get some info about tracks from MusixMatch API
### Link to work: [That new python file I thought about making yesterday](https://github.com/D3V4N5H/StarBoy/blob/master/userArtistSongMap.py)
![](https://pbs.twimg.com/media/DoXbojbXgAEeFnr.jpg)
![](https://pbs.twimg.com/media/DoXbrTGXgAE0gDv.jpg)
![](https://pbs.twimg.com/media/DoXbtn9X0AAfoaf.jpg)
![](https://pbs.twimg.com/media/DoXbu81X0AMaJEZ.jpg)

## Day 13: October 1, 2018
### Today's Progress:
✅ Fixed Top Artists for India (country parameter was for US) API call  

✅ Added Top Tracks in India list
### Thoughts:
track.snippet.get didn't work for starboy track_id 144134659, not even in the playground

I'm planning to use the following to compute relevance:  
chart.tracks.get  
chart.artists.get  
matcher.track.get  
track.get  
artist.albums.get  
matcher.lyrics.get  
track.lyrics.get
### Link to work: [Commit to the Fix](https://github.com/D3V4N5H/StarBoy/commit/2bbfafbfbf6a8d2d75d7d5c859c4ba35b9e0b9e8)
![](https://pbs.twimg.com/media/DocwmCnWkAImWF9.jpg)


# [**Week 2 Report as Explainer Article**](http://sync.dvnsh.com/mlday7)


## Day 14: October 2, 2018
### Today's Progress:
✅ Made a function to handle APIs better  

✅ Combined approach: Finding Best songs OF Best artists
### Thoughts:
I tested lyrics by watching the Starboy video on Youtube with MusixMatch Chrome Extension and it worked fine.  
This proves that they DO have the lyrics with them.  
But I'm not able to find the lyrics programmatically.  
Now I will try to get metadata, eventually reflecting those in the Graph.
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/425803542ad62e053110398b8d9fd56baa5f9326)
![](https://pbs.twimg.com/media/DohesfiX0AUMkrs.jpg)
![](https://pbs.twimg.com/media/DohexlyXgAAPMA0.jpg)
![](https://pbs.twimg.com/media/Dohe7p2W0AAtEib.jpg)
![](https://pbs.twimg.com/media/Dohe2tJXUAE08xg.jpg)

## Day 15: October 3, 2018
### Today's Progress:
✅ Convert listOfTracks to a dictionary with track_name, track_id as values  

✅ Fetch and Parse the Release Date
### Thoughts:
Now I have the Release Date Metadata, but that's not it. A Date Object is convenient in Python. I'm not sure it's a good move to store that information as Node in Graph. I might have to come up with a Hybrid approach if I can't sort it out tomorrow.
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/ae74585ad3f3b1fb100d357af3923cfe42b62d5b)
![](https://pbs.twimg.com/media/DomY127XsAERHkb.jpg)
![](https://pbs.twimg.com/media/DomY3eBW4AIgJ8w.jpg)
![](https://pbs.twimg.com/media/DomY5YuX0AA6yGs.jpg)
![](https://pbs.twimg.com/media/DomY7r2XUAEBneo.jpg)

## Day 16: October 4, 2018
### Today's Progress:
✅ Dropped the getReleaseDateFromTrackId function in favour of iterating from data in Top Tracks which already had the dates
### Thoughts:
The function I defined was taking too long to execute, as it was fetching track details for every top artist's every single top track. That's too many API calls (about 100, depending on number of items).  
After inspecting data from previous API calls, I noticed that if I could iterate into the nested dictionary inside tuple inside list inside the callback (phew)!
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/71ac6ad7a1ca1f3e931c9676031b9b0f20a31443)
![](https://pbs.twimg.com/media/DorFwtOW0AAwEas.jpg)
![](https://pbs.twimg.com/media/DorFz_cX0AA0b2p.jpg)
![](https://pbs.twimg.com/media/DorF1dpXUAA-R74.jpg)
![](https://pbs.twimg.com/media/DorF1syXkAApifY.jpg)

## Day 17: October 5, 2018
### Today's Progress:
✅ Take Top Tracks in the geographical place as Training Data for AI
### Thoughts:
At this point my project seems to be leaning towards Collaborative filtering based on other users' activity
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/b4d7072baf1a33bc71a3befdc23b9df0b0196957)
![](https://pbs.twimg.com/media/Dow7xRVW0AArAIN.jpg)
![](https://pbs.twimg.com/media/Dow710SXsAAxrYG.jpg)

## Day 18: October 6, 2018
### Today's Progress:
✅ Finally managed to fetch lyrics of Top Songs in #India songs to train the AI  

✅ Made API method much better
### Thoughts:
I'm not able to fetch the whole lyrics. I'll work with what I have now.  
I'm planning to take Top Tracks of India as Training Data and use Top Artists' Songs to find recommendations.
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/4ef724a446cf1e2bd85d277156942b2b29603f35)
![](https://pbs.twimg.com/media/Do2EfgEXkAEpp61.jpg)
![](https://pbs.twimg.com/media/Do2Er5GW0AA9FPK.jpg)
![](https://pbs.twimg.com/media/Do2Er5aXsAEkc1s.jpg)
![](https://pbs.twimg.com/media/Do2Er5KXgAEQYFz.jpg)

## Day 19: October 7, 2018
### Today's Progress:
✅ Cleared other parts in the lyrics, so it's much more readable now (Compared to yesterday)  

✅ Refactored the code
### Thoughts:
This is where my previous work about generating weighted keywords can pitch in to UNDERSTAND the lyrics.
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/08cbeb7d3c51b4fcb50dd5675bd20917c04a4e86)
![](https://pbs.twimg.com/media/Do5wsOfX4AAjkUW.jpg)
![](https://pbs.twimg.com/media/Do5wumGXgAAx71V.jpg)
![](https://pbs.twimg.com/media/Do5wv-YXsAAdBFT.jpg)
![](https://pbs.twimg.com/media/Do5wx-AXoAAOcMv.jpg)

## Day 20: October 8, 2018
### Today's Progress:
✅ New Python file to parse the #StarBoy lyrics  

✅ Removed background vocals in brackets
### Thoughts:
Genius.com [resources](https://genius.com/3317959) helped understand parts of the lyrics  
The data in my file is analogous to the csv file that I manually generated at the beginning of the project. Getting lyrics is now officially automated !!
### Link to work: [Commit to New File](https://github.com/D3V4N5H/StarBoy/commit/5b38af182c69b2dff9036bcb3ed21881456430f9)
![](https://pbs.twimg.com/media/Do_blFoUUAAcISl.jpg)
![](https://pbs.twimg.com/media/Do_bnQ4VAAECuFC.jpg)
![](https://pbs.twimg.com/media/Do_bo97V4AMWAVS.jpg)

# [**Week 3 Report as Explainer Article**](http://sync.dvnsh.com/mlday14)
![](https://pbs.twimg.com/media/Do_jaeRUYAEpi-7.jpg)


## Day 21: October 9, 2018
### Today's Progress:
😭 Failed to import line by line lyrics into @neo4j (without using CSV)
### Thoughts:
Tried doing this for 4 Hours. It's too complicated.
![](https://pbs.twimg.com/media/DpFXg2PWwAMiuzj.jpg)

## Day 22: October 10, 2018
### Today's Progress:
✅ [Michael Hunger](https://twitter.com/@mesirii) helps me import the data to the graph  

✅ Mining Paradigmatic Word Associations in lyrics from API calls
### Thoughts:
Today's date is 10 on 10 (10/10), and so was my progress.  
As I was wondering why the word frequency from the API fetched lyrics didn't match that of the CSV lyrics, it was comforting to recollect that I don't get FULL lyrics from the free account. Hence the difference.  
Despite that, my mining was very accurate.

I was tempted to use an iterator for the word-by-word query but when it didn't work, so I sticked with coding that part from the scratch.
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/4695d4e1dd30ea86528356ef4bdaa57a0d3a7cbd)
![](https://pbs.twimg.com/media/DpKrkTEW0AAGDeL.jpg)
![](https://pbs.twimg.com/media/DpKrkSxW0AAlJAL.jpg)

## Day 23: October 11, 2018
### Today's Progress:
✅ Create nodes from words of ALL top tracks in india
### Thoughts:
I tried to create nodes with separate labels for each song, but it seems that's not possible. So now I will have to mine each of the tracks one-by-one inside the same loop instead of batch mining !
### Link to work: [Commit Creating 'Mining Top Tracks in india.py](https://github.com/D3V4N5H/StarBoy/commit/00d2ea4feb035da7aaa1321d38fdf6ecab2a7dec)
![](https://pbs.twimg.com/media/DpP1LGpW0AAlvD5.jpg)
![](https://pbs.twimg.com/media/DpP1LSsWsAUmjWq.jpg)
![](https://pbs.twimg.com/media/DpP1N6VW4AAo-Up.jpg)

## Day 24: October 12, 2018
### Today's Progress:
✅ Adding names of songs as Labels using APOC
### Thoughts:
Now I can batch-mine all songs in the graph, and know which song a particular cluster of nodes belongs to :D  
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/7217f4048ee686811c6213cb4d08d780940353bb)
![](https://pbs.twimg.com/media/DpU5VcjWwAAiJ6P.jpg)
![](https://pbs.twimg.com/media/DpU5XA9XoAAiIsv.jpg)

## Day 25: October 13, 2018
### Today's Progress:
✅ Mining from Lyrics of Songs
### Thoughts:
Some words are repeated as nodes. I will need to debug this, as most weighted pairs are the same words in the results
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/c4667d792249211593b6eb52e816e72f125eb72a)
![](https://pbs.twimg.com/media/DpaHNlpW0AIESch.jpg)
![](https://pbs.twimg.com/media/DpaHPRSW0AAo1Cc.jpg)
![](https://pbs.twimg.com/media/DpaHR1vWkAAIOte.jpg)

## Day 26: October 14, 2018
### Today's Progress:
👀 Deep inspection of the mined data
### Thoughts:
I found multiple nodes(at least two) with same words  
Something is wrong. I'm expecting unique nodes.
### Link to image: [pic on Twitter](https://pbs.twimg.com/media/DpkJRxoW0AMHxT0.jpg:large)
![](https://pbs.twimg.com/media/DpkJRxoW0AMHxT0.jpg)

## Day 27: October 15, 2018
### Today's Progress:
✅ Refactor the Mining process
### Thoughts:
After refactoring the mining process, another instance of the mined graph indicates that the issue has prevailed.
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/756852ee834a0cf661b6c036ac9df221c55558e1)
![](https://pbs.twimg.com/media/DpkeA55XcAAeQmw.jpg)

# [**Week 4 Report as Explainer Article**](http://sync.dvnsh.com/mlday21)
![](https://pbs.twimg.com/media/Dp8OGC_UUAArIcD.jpg)

## Day 28: October 16, 2018
### Today's Progress:
✅ Underscored Variable names for readability  
🕵🏻‍♂️Found issues in parsing of lyrics
### Thoughts:
I have no idea of the weird unexpected codes I'm looking at. This has never happened before.
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/6634918160f8f6fe396c5aecb6c445ce0de45e30)
![](https://pbs.twimg.com/media/DppjZ4QWwAEIMf2.jpg)

## Day 29: October 17, 2018
### Today's Progress:
✅ Implemented query and calls with a different approach to prevent duplicate nodes before Mining
### Thoughts:
Finally it works as intended, can't wait to fetch and display keywords mined from each song now !
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/72161604f84be9c3a9c80fd0bef7fe57d27cfb13)
![](https://pbs.twimg.com/media/Dpu64hIW0AI2pnj.jpg)

## Day 30: October 18, 2018
### Today's Progress:
⚙️ Importing weighted keywords from mined graph
### Thoughts:
The script is taking significant time to execute
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/9e1298606051cf92607e7d5ca67d6af6f5b129e4)
![](https://pbs.twimg.com/media/DpzETgpU4AA3yL4.jpg)

## Day 31: October 19, 2018
### Today's Progress:
⚙️ Trying different approaches to read Response code from the BoltStatementResult object
### Thoughts:
I really wish I could just iterate on it!
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/aed6b05e5feae8ce5078f08342286a4b4402ef24)
![](https://pbs.twimg.com/media/DpzETgdU8AADIf0.jpg)

## Day 32: October 20, 2018
### Today's Progress:
✅ Learned Pypher  

✅ Finally imported from Graph (though strangely all weights are 1.0)
### Thoughts:
I couldn't find how Pypher could help me access records from the graph, so I implemented the code without it
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/924311c7c81b6eee7b7f11fc6c68a75b16e23d01)
![](https://pbs.twimg.com/media/Dp8GBncU4AA3lUV.jpg)
![](https://pbs.twimg.com/media/Dp8GBnNVsAMCRvt.jpg)

## Day 33: October 21, 2018
### Today's Progress:
✅ Recreated the same problem with Starboy Lyrics
### Thoughts:
This is really interesting, and I suspect this is due to the way I'm passing words to the graph
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/ea3c9a7fd09cfbcfd12d210ae33e1b00e6238d78)
![](https://pbs.twimg.com/media/DqBn_IdVAAERbS1.jpg)

## Day 34: October 22, 2018
### Today's Progress:
✅ Create CSV file to store lyrics and FIRE the original Cypher Query for proper mining to get expected weight range
### Thoughts:
I hope to get a Comma-Separated-LINES instead of Comma-Separated-WORDS tomorrow
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/d0abf13b640083255e31df566eccc96cc1f08d03)
![](https://pbs.twimg.com/media/DqHQa7nVYAImYoj.jpg)
![](https://pbs.twimg.com/media/DqHQZyPVsAAYrHc.png)
![](https://pbs.twimg.com/media/DqHQYuKUwAA7Q9w.png)
![](https://pbs.twimg.com/media/DqHQXR1UUAEh5KW.png)

# [**Week 5 Report as Explainer Article**](http://sync.dvnsh.com/mlday28)


## Day 35: October 23, 2018
### Today's Progress:
✅ Exported lyrics into a CSV
### Thoughts:
Interestingly, some lines were blank
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/2126251d2b83b0369026a43be8dc0abf5da5ad99)
![](https://pbs.twimg.com/media/DqMK_kKU8AELgN7.jpg)
![](https://pbs.twimg.com/media/DqMLAzRUUAECRfK.png)
![](https://pbs.twimg.com/media/DqMK-EsVYAA-k5E.png)
![](https://pbs.twimg.com/media/DqMLCZMVsAAa-oL.png)

## Day 36: October 24, 2018
### Today's Progress:
✅ Imporved Lyrics cleaning using loops  

✅ CSV export is tip top, no blank lines now
### Thoughts:
The number of nodes surprisingly increased after removing blank lines
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/9c1cd4721dbfa9fde551eef9a12ef6b39e07fef2)
![](https://pbs.twimg.com/media/DqQWA2HXgAErOdT.jpg)
![](https://pbs.twimg.com/media/DqQWCMoWwAAtvj5.jpg)

## Day 37: October 25, 2018
### Today's Progress:
✅ Export Starboy lyrics csv directly to the path of graph import directory
### Thoughts:
I wish there was a way to FIND OUT where is the current graph located using the driver
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/7ed65e5a6508918c668518ec778a6b0b25424069)
![](https://pbs.twimg.com/media/DqWAoV5WkAAD38o.jpg)

## Day 38: October 26, 2018
### Today's Progress:
✅ Mine the lyrics imported from CSV  

✅ Store the result in a Python dictionary
### Thoughts:
Found '0' values for words...  
I checked the CSV file, and it didn't have any '0' in it !
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/b405c9b59fada21989851d7bf2c4edb642f4d4f0)


## Day 39: October 27, 2018
### Today's Progress:
✅ Replicate the successful mining in Starboy in the loop of 'Mining Top Tracks in india' script
### Thoughts:
My code is right, but the Database throws Illegal Character error for songs that have SPACE in their name
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/d5547344d5f22137ff7f802126e06aa430de2abf)
![](https://pbs.twimg.com/media/DqhGPf6X0AAUlcj.jpg)

## Day 40: October 28, 2018
### Today's Progress:
😿 Encoding the File Name didn't help
### Thoughts:
Feels like I'm hitting a wall here
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/c8593c416e7a1d2f522527841d216a78a5c91ccb)
![](https://pbs.twimg.com/media/DqmUEejX0AEfFZi.jpg)
![](https://pbs.twimg.com/media/DqmUGCjXgAEZlKR.jpg)
![](https://pbs.twimg.com/media/DqmUJsvXQAYvQXd.jpg)

## Day 41: October 29, 2018
### Today's Progress:
✅ Fix file encoding issue
### Thoughts:
"Cannot merge node using null property value for word"  
I removed the last empty line in the CSV manually and checked for other NULL values with Python.  
Starboy lyrics had null and still worked fine.
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/46c5b75186998288d4a5317d14e3bf41ea8d263d)
![](https://pbs.twimg.com/media/DqrBqxsVAAEUKAl.jpg)
![](https://pbs.twimg.com/media/DqrBmAuU4AE7Mo1.jpg)
![](https://pbs.twimg.com/media/DqrBo6DUUAIHAp_.jpg)


# [**Week 6 Report as Explainer Article**](http://sync.dvnsh.com/mlday35)


## Day 42: October 30, 2018
### Today's Progress:
✅ Sentiment Analysis using TextBlob
### Thoughts:
Graph based Mining was fancy, but on hiatus for now, until I figure out how to import from CSV without that NULL error
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/3d689e09a3e1beb9f3f51066c5c1456893e43efb)
![](https://pbs.twimg.com/media/DqwsDnVU4AAw3AG.jpg)
![](https://pbs.twimg.com/media/DqwsF_8U0AAU4j-.jpg)
![](https://pbs.twimg.com/media/DqwrwcZVAAA3Kdy.jpg)

## Day 43: October 31, 2018
### Today's Progress:
✅ Sentiment polarity to Percentage  

✅ Fixed script breaking when @MusixMatch doesn't have lyrics  

✅ Only showing lines with non-zero sentiment
### Thoughts:
Sometimes, MusixMatch doesn't have lyrics, in which case it sends an empty list instead of dictionary. So that was breaking my script today (even though it worked fine yesterday, as it had lyrics for all top songs in india of yesterday's charts). So I had to put a condition to make sure the script doesn't fail

I'm not showing lines and songs that don't yield a sentiment (i.e. polarity is 0)
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/71c26298cb9f3c8f28c3b12495d36e825b414d77)
![](https://pbs.twimg.com/media/Dq2j9_NXQAA8vCL.jpg)
![](https://pbs.twimg.com/media/Dq2kEYjWkAIz5es.jpg)
![](https://pbs.twimg.com/media/Dq2kGOqXgAAh0ge.jpg)
![](https://pbs.twimg.com/media/Dq2kAQaWkAE1nQ_.jpg)

## Day 44: November 1, 2018
### Today's Progress:
✅ Test Language Detection  

✅ Test NLTK Part Of Speech (POS) tagging
### Thoughts:
Kamariya is controversial. It's based on a Gujarati song, but the song in Hindi. So detecting it as either is good enough; I'm happy it detected it as Gujarati.

However, Language Detection was not accurate for all songs. Proper Patola is in Punjabi, yet it was detected as Gujarati. I will see if I can verify it with data from the API.

#### Tags:
* Basic:
  * N	Noun
  * V	Verb
  * ADJ	Adjective
  * ADV	Adverb
  * P	Preposition
  * CON	Conjunction
  * PRO	Pronoun
  * INT	Interjection
* Advanced
  * CC	coordinating conjunction
  * RB	adverbs
  * IN	preposition
  * NN	noun
  * JJ	adjective
  * VBP	present tense verb

### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/72f9c2c8c4a56378e67dcf8cb74b4b45b052abf2)
![](https://pbs.twimg.com/media/Dq7enGYW4AA2hq2.jpg)
![](https://pbs.twimg.com/media/Dq7eqs7XgAE0GJy.jpg)
![](https://pbs.twimg.com/media/Dq7eu5oWkAADwso.jpg)
![](https://pbs.twimg.com/media/Dq7etBWX4AAyrgo.jpg)

## Day 45: November 2, 2018
### Today's Progress:
✅ Compare Language Detection result with data from API
### Thoughts:
Initially, I should mine tracks that are in English according to both: API and Language Detection result
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/280af0a6cfc7c1b83e4c6b9cd0ea8ff51996858c)
![](https://pbs.twimg.com/media/DrAvWfxWwAAVtXK.png)
![](https://pbs.twimg.com/media/DrAvSaoXQAIoto1.jpg)

## Day 46: November 3, 2018
### Today's Progress:
✅ Restrict mining to english by detecting the language and verifying the detection with labeled data from API
### Thoughts:
I will now work on finding all the ways to compare environmental factors with lyrics in English language
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/7639c3515d8c42ecdb06d95df4d9dc4a2f1c3ae0)
![](https://pbs.twimg.com/media/DrFHRZNW4AA_cuo.jpg)

## Day 47: November 4, 2018
### Today's Progress:
✅ Sad percentage value should be absolute, not negative  

✅ Naive Bayes Tokenization and comparison with Pattern Analyzer
### Thoughts:
I would tolerate percentage difference, but in some cases the polarity is totally opposite. I will need to listen these songs, read lyrics and manually verify if the sentiments are consistent with the algorithms (which can be subjective).
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/8b702b46880a8d0418d9ce85094493cae74e3e2f)
![](https://pbs.twimg.com/media/DrKYV0-WwAAwpbn.jpg)
![](https://pbs.twimg.com/media/DrKYYfEX0AE_3DV.jpg)
![](https://pbs.twimg.com/media/DrKYZ8ZWoAAuAFp.jpg)

## Day 48: November 5, 2018
### Today's Progress:
✅ Use @IBM Watson from BlueMix Console for Natural Language Understanding of 'Entities and Keywords'
### Thoughts:
I will need more time to go through the documentation for taking full advantage of Watson's services
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/4946ba2e6986862655d4a458981fc2180f0206a9)
![](https://pbs.twimg.com/media/DrQktr4U0AEBLmD.png)
![](https://pbs.twimg.com/media/DrQkvG9U4AAZbCe.jpg)


# [**Week 7 Report as Explainer Article**](http://sync.dvnsh.com/mlday42)
![](https://cdn-images-1.medium.com/max/800/0*kCCt18G0Im6hBY57)


## Day 49: November 6, 2018
### Today's Progress:
✅ Line-By-Line comparison of Sentiment Analysis Result from PatternAnalyzer and NaiveBayesAnalyzer (an NLTK classifier)
### Thoughts:
I will use IBM Watson's Natural Language Understanding only when there is conflict between these two (One thinks sad, another happy)
### Link to work: [IBM NLU.py](https://github.com/D3V4N5H/StarBoy/commit/0af5009373ddd9d5b41e1fe3e5f4ab079645b4cd)
![](https://pbs.twimg.com/media/DrUyKwwU0AYKlFK.jpg)
![](https://pbs.twimg.com/media/DrUyMFPUUAA6AdD.jpg)

## Day 50: November 7, 2018
### Today's Progress:
✅ Emotional Understanding by IBM Watson of The Weeknd song 'Starboy'
### Thoughts:
I wish I could find out why Watson thinks Jamie Foxx has something to do with this song.
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/44ddfa260536cdcdb01d782d76eb05c467cc6011)
![](https://pbs.twimg.com/media/DrZxLq3VAAUADEn.jpg)
![](https://pbs.twimg.com/media/DrZxOmNU8AAlmY9.jpg)
![](https://pbs.twimg.com/media/DrZxQY5VYAEeYLt.jpg)
![](https://pbs.twimg.com/media/DrZxRxfUcAMwyRw.jpg)

## Day 51: November 8, 2018
### Today's Progress:
✅ Sentiment Analysis head to head showdown "Pattern Analyzer" vs. "Naive Bayes" judged by our chief guest IBM Watson
### Thoughts:
This is hard to judge as I'm not getting full lyrics from the MusixMatch API
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/b39d8fc37c7ae85636866833f0d1d3507ff0cbca)
![](https://pbs.twimg.com/media/DrgBhIRU8AA1p62.jpg)

## Day 52: November 9, 2018
### Today's Progress:
✅ Deeper insights from IBM Watson from full lyrics of The Weeknd 'Starboy'
### Thoughts:
This is very useful. I think I should stick with IBM for understanding both - enviroment and song
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/08cccca8b1ecbfae2b0829aee5418fdbed64d48e)
![](https://pbs.twimg.com/media/DrjRoLaU4AAVsRU.jpg)
***
![](https://pbs.twimg.com/media/DrjRrH0VsAA_JJX.jpg)
***
![](https://pbs.twimg.com/media/DrjRrIxV4AIPo3o.jpg)
***
![](https://pbs.twimg.com/media/DrjRrIwVsAU51Tn.jpg)

## Day 53: November 10, 2018
### Today's Progress:
✅ Search for Song ID in @Genius.com database  

✅ Use song ID to fetch description of the song  

✅ Sentiment Analysis of : Lyrics + Description
### Thoughts:
Implementing OAuth2 Access Token based Authorization was really challenging
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/89fbaf71bf3943c61b1daa573b0365a3fa0cb4b9)
![](https://pbs.twimg.com/media/DrqJCj2UwAA_Lou.jpg)
![](https://pbs.twimg.com/media/DrqJEgRVAAA74KF.jpg)
![](https://pbs.twimg.com/media/DrqJH6ZU0AAus4P.png)
![](https://pbs.twimg.com/media/DrqJKUwUUAE2Y-e.jpg)

## Day 54: November 11, 2018
### Today's Progress:
✅ Scrape Full lyrics from @Genius.com  

✅ Perform Sentiment Analysis on it  

✅ Change Country from india to USA as I only want to mine English songs
### Thoughts:
Didn't get any output from the script as I had configured it to only mine English songs, and all top songs happened to be non-English today.

I'm not sure if scraping is allowed, I didn't find anything against it in the official documentation

Will keep MusixMatch as a fallback in case I can't find lyrics from Genius.com
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/9f94e2887c1815816a52f00843c3ca47897c9f53)
![](https://pbs.twimg.com/media/DrvoMBkUcAAIH1N.jpg)
![](https://pbs.twimg.com/media/DrvoOsQVAAEJvx9.jpg)

## Day 55: November 12, 2018
### Today's Progress:
✅ Get lyrics from #PoweredByMusixMatch when not available in @Genius  

✅ Extract Noun phrases from the blob  

✅ Change Country back to India for testing  
### Thoughts:
I also did some refactoring that made the script faster  
I will need to decide how to deal with Language labels coming from different APIs  
Maybe I can match noun phrases with data from environment
### Link to work: [Commit with changes](https://github.com/D3V4N5H/StarBoy/commit/b93d54e3470c1cd5b08c400c2a853985e5d1c987)
![](https://pbs.twimg.com/media/Dr0uyuVVsAAeiyu.jpg)
![](https://pbs.twimg.com/media/Dr0u0GDVsAAZJV8.jpg)

## Day 56: November 13, 2018
### Today's Progress:
✅ LIVE Watson Speech-To-Text from Microphone  

✅ Submit Pull Request to update their example script from docs
### Thoughts:
Tried Google Speech to Text API but enabling the service requires connecting a Payment method that has automatic recurring payments support
My card doesn't have that
### Link to work: [Pull Request](https://github.com/watson-developer-cloud/python-sdk/pull/595)
![](https://pbs.twimg.com/media/Dr88hVUU0AIAxWF.jpg)
![](https://pbs.twimg.com/media/Dr88refVAAAwPWx.jpg)

## Day 57: November 14, 2018
### Today's Progress:
✅ IBM Watson continuous Speech-To-Text transcription from Microphone using WebSocket
### Thoughts:
"Now the output is much more neat"  
We're not shaking hands yet
### Link to work: [sttibm.py](https://github.com/D3V4N5H/StarBoy/commit/4b617cf60c7c3c2fee4bdf97c63da3170ba52c93)
![](https://pbs.twimg.com/media/Dr-YBPcU0AE4Tw2.jpg)
![](https://pbs.twimg.com/media/Dr-YDyHVAAEK0On.jpg)
![](https://pbs.twimg.com/media/Dr-YGQlU8AAGN2g.jpg)
![](https://pbs.twimg.com/media/Dr-YHvAVYAAZ9wx.jpg)

## Day 58: November 15, 2018
### Today's Progress:
✅ Setup a Configuration file for my API keys and authentication passwords in so that they don't appear in the Github
### Thoughts:
I will need to edit all the scripts to use the config file  
I will also release a template for others to edit and be able to use the scripts using their credentials
### Link to work: [config.py](https://github.com/D3V4N5H/StarBoy/commit/681c363ea6700f6b84f96b7ed78724619f0cc179)
![](https://pbs.twimg.com/media/DsEqHYhVAAAchZM.jpg)

## Day 59: November 16, 2018
### Today's Progress:
✅ Update deprecated Neo4j driver  

✅ Modify each script to use the config file for credentials  

✅ Analyze Taki Taki and summarize using TextRank
### Thoughts:
I was surprised to find some phrases when I was coding AI to understand Lyrics of Songs  

1. I'm learning Spanish  
2. I have respect for their culture  
3. I just watched TakiTaki Song's Video  

Now I do CARA PALMA (FacePalm: 🤦🏻‍♂️)  

Disclaimer  
I'm disappointed by the message, not music  
### Links to work: [Commits Today](https://github.com/search?utf8=%E2%9C%93&q=committer-date%3A2018-11-16..2018-11-18+repo%3AD3V4N5H%2FStarBoy&type=Commits)

## Day 60: November 17, 2018
### Today's Progress:
✅ Dynamically add method to Graph class using Decorator  

✅ Added Modularity by making Modules for Graph and MusixMatch
### Thoughts:
I did major refactoring today.  
I'm thinking about putting IBM code in a separate module too
### Link to work: [Commits Today](https://github.com/search?utf8=%E2%9C%93&q=committer-date%3A2018-11-17..2018-11-19+repo%3AD3V4N5H%2FStarBoy&type=Commits)
![](https://pbs.twimg.com/media/DsO2LRiVAAA9IqK.png)
