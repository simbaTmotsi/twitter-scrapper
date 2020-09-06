<div class="flex-shrink-0 col-12 col-md-9 mb-4 mb-md-0">
            <div id="wiki-body" class="gollum-markdown-content">
            <div class="markdown-body">
              <h2>Twint Options</h2>
<table role="table">
<thead>
<tr>
<th>Command</th>
<th>Usage</th>
</tr>
</thead>
<tbody>
<tr>
<td>
<code>-u</code>, <code>--username</code>
</td>
<td>User's Tweets you want to scrape.</td>
</tr>
<tr>
<td>
<code>-s</code>, <code>--search</code>
</td>
<td>Search for Tweets containing this word or phrase.</td>
</tr>
<tr>
<td>
<code>-g</code>, <code>--geo</code>
</td>
<td>Search for geocoded Tweets.</td>
</tr>
<tr>
<td><code>--near</code></td>
<td>Near a specified city.</td>
</tr>
<tr>
<td><code>--location</code></td>
<td>Show user's location (Experimental).</td>
</tr>
<tr>
<td>
<code>-l</code>, <code>--lang</code>
</td>
<td>Search for Tweets in a specific language (See <a href="https://github.com/haccer/twint/wiki/Langauge-codes">language codes</a>).</td>
</tr>
<tr>
<td>
<code>-o</code>, <code>--output</code>
</td>
<td>Save output to a file.</td>
</tr>
<tr>
<td>
<code>-es</code>, <code>--elasticsearch</code>
</td>
<td>Index to Elasticsearch.</td>
</tr>
<tr>
<td><code>--year</code></td>
<td>Filter Tweets before specified year.</td>
</tr>
<tr>
<td><code>--since</code></td>
<td>Filter Tweets sent since date (Example: 2017-12-27).</td>
</tr>
<tr>
<td><code>--until</code></td>
<td>Filter Tweets sent until date (Example: 2017-12-27).</td>
</tr>
<tr>
<td><code>--email</code></td>
<td>Filter Tweets that might have email addresses.</td>
</tr>
<tr>
<td><code>--phone</code></td>
<td>Filter Tweets that might have phone numbers.</td>
</tr>
<tr>
<td><code>--verified</code></td>
<td>Display Tweets only from verified users (Use with -s).</td>
</tr>
<tr>
<td><code>--csv</code></td>
<td>Write as .csv file.</td>
</tr>
<tr>
<td><code>--json</code></td>
<td>Write as .json file.</td>
</tr>
<tr>
<td><code>--hashtags</code></td>
<td>Output hashtags in seperate column.</td>
</tr>
<tr>
<td><code>--userid</code></td>
<td>Twitter user id.</td>
</tr>
<tr>
<td><code>--limit</code></td>
<td>Number of Tweets to pull (Increments of 20).</td>
</tr>
<tr>
<td><code>--count</code></td>
<td>Display number of Tweets scraped at the end of session.</td>
</tr>
<tr>
<td><code>--stats</code></td>
<td>Show number of replies, retweets, and likes.</td>
</tr>
<tr>
<td>
<code>-db</code>, <code>--database</code>
</td>
<td>Store Tweets in a sqlite3 database.</td>
</tr>
<tr>
<td><code>--to</code></td>
<td>Search Tweets to a user.</td>
</tr>
<tr>
<td><code>--all</code></td>
<td>Search all Tweets associated with a user.</td>
</tr>
<tr>
<td><code>--followers</code></td>
<td>Scrape a person's followers.</td>
</tr>
<tr>
<td><code>--following</code></td>
<td>Scrape a person's follows.</td>
</tr>
<tr>
<td><code>--favorites</code></td>
<td>Scrape Tweets a user has liked.</td>
</tr>
<tr>
<td><code>--proxy-type</code></td>
<td>Socks5, HTTP, etc.</td>
</tr>
<tr>
<td><code>--proxy-host</code></td>
<td>Proxy hostname or IP.</td>
</tr>
<tr>
<td><code>--proxy-port</code></td>
<td>The port of the proxy server.</td>
</tr>
<tr>
<td><code>--essid</code></td>
<td>Elasticsearch Session ID, use this to differentiate scraping sessions.</td>
</tr>
<tr>
<td><code>--userlist</code></td>
<td>Userlist from list or file.</td>
</tr>
<tr>
<td><code>--retweets</code></td>
<td>Include user's Retweets (Warning: limited).</td>
</tr>
<tr>
<td><code>--format</code></td>
<td>Custom output format (See wiki for details).</td>
</tr>
<tr>
<td><code>--user-full</code></td>
<td>Collect all user information (Use with followers or following only).</td>
</tr>
<tr>
<td><code>--profile-full</code></td>
<td>Slow, but effective method of collecting a user's Tweets and RT.</td>
</tr>
<tr>
<td><code>--store-pandas</code></td>
<td>Save Tweets in a DataFrame (Pandas) file.</td>
</tr>
<tr>
<td><code>--pandas-type</code></td>
<td>Specify HDF5 or Pickle (HDF5 as default).</td>
</tr>
<tr>
<td>
<code>-it</code>, <code>--index-tweets</code>
</td>
<td>Custom Elasticsearch Index name for Tweets.</td>
</tr>
<tr>
<td>
<code>-if</code>, <code>--index-follow</code>
</td>
<td>Custom Elasticsearch Index name for Follows.</td>
</tr>
<tr>
<td>
<code>-iu</code>, <code>--index-users</code>
</td>
<td>Custom Elasticsearch Index name for Users.</td>
</tr>
<tr>
<td>
<code>-dt</code>, <code>--doc-type</code>
</td>
<td>Custom Elasticsearch document type.</td>
</tr>
<tr>
<td><code>--debug</code></td>
<td>Store information in debug logs.</td>
</tr>
<tr>
<td><code>--resume</code></td>
<td>Resume from Tweet ID.</td>
</tr>
<tr>
<td><code>--videos</code></td>
<td>Display only Tweets with videos.</td>
</tr>
<tr>
<td><code>--images</code></td>
<td>Display only Tweets with images.</td>
</tr>
<tr>
<td><code>--media</code></td>
<td>Display Tweets with only images or videos.</td>
</tr>
<tr>
<td><code>--replies</code></td>
<td>Display replies to a subject.</td>
</tr>
<tr>
<td>
<code>-pc</code>, <code>--pandas-clean</code>
</td>
<td>Automatically clean Pandas dataframe at every scrape.</td>
</tr>
<tr>
<td><code>--get-replies</code></td>
<td>All replies to the tweet.</td>
</tr>
<tr>
<td>
<code>-pt</code>, <code>--popular-tweets</code>
</td>
<td>Scrape popular tweets instead of recent ones.</td>
</tr>
<tr>
<td>
<code>-sc</code>, <code>--skip-certs</code>
</td>
<td>Skip certs verification, useful for SSC.</td>
</tr>
<tr>
<td>
<code>-ho</code>, <code>--hide-output</code>
</td>
<td>Hide output, no tweets will be displayed.</td>
</tr>
<tr>
<td>
<code>-nr</code>, <code>--native-retweets</code>
</td>
<td>Filter the results for retweets only (a few tweets will be returned!).</td>
</tr>
<tr>
<td><code>--min-likes</code></td>
<td>Filter the tweets by minimum number of likes.</td>
</tr>
<tr>
<td><code>--min-retweets</code></td>
<td>Filter the tweets by minimum number of retweets.</td>
</tr>
<tr>
<td><code>--min-replies</code></td>
<td>Filter the tweets by minimum number of replies.</td>
</tr>
<tr>
<td><code>--links</code></td>
<td>Include or exclude tweets containing one o more links. If not specified you will get both tweets that might contain links or not.</td>
</tr>
<tr>
<td><code>--source</code></td>
<td>Filter the tweets for specific source client.</td>
</tr>
<tr>
<td><code>--members-list</code></td>
<td>Filter the tweets sent by users in a given list.</td>
</tr>
<tr>
<td>
<code>-fr</code>,<code>--filter-retweets</code>
</td>
<td>Exclude retweets from the results.</td>
</tr>
</tbody>
</table>
<p>If you would like to use Tor proxy, just type <code>--proxy-host tor</code> instead of <code>--proxy-host localhost --proxy-type socks5 --proxy-port 9050</code>.</p>
<p><code>--userlist</code> arg will overwrite <code>--username</code> arg.</p>
<h2>
<a id="user-content-basic-examples-and-combos" class="anchor" href="#basic-examples-and-combos" aria-hidden="true"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Basic Examples and Combos.</h2>
<p>A few simple examples to help you understand the basics:</p>
<ul>
<li>
<code>twint -u username</code> - Scrape all the Tweets from <em>user</em>'s timeline.</li>
<li>
<code>twint -u username -s pineapple</code> - Scrape all Tweets from the <em>user</em>'s timeline containing <em>pineapple</em>.</li>
<li>
<code>twint -s pineapple</code> - Collect every Tweet containing <em>pineapple</em> from everyone's Tweets.</li>
<li>
<code>twint -u username --year 2014</code> - Collect Tweets that were tweeted <strong>before</strong> 2014.</li>
<li>
<code>twint -u username --since 2015-12-20</code> - Collect Tweets that were tweeted since 2015-12-20.</li>
<li>
<code>twint -u username -o file.txt</code> - Scrape Tweets and save to file.txt.</li>
<li>
<code>twint -u username -o file.csv --csv</code> - Scrape Tweets and save as a csv file.</li>
<li>
<code>twint -g="48.880048,2.385939,1km" -o file.csv --csv</code> - Scrape Tweets from a radius of 1km around a place in Paris and export them to a csv file.</li>
<li>
<code>twint -u username -es localhost:9200</code> - Output Tweets to Elasticsearch</li>
<li>
<code>twint -u username -o file.json --json</code> - Scrape Tweets and save as a json file.</li>
<li>
<code>twint -u username --database tweets.db</code> - Save Tweets to a SQLite database.</li>
<li>
<code>twint -u username --followers</code> - Scrape a Twitter user's followers.</li>
<li>
<code>twint -u username --following</code> - Scrape who a Twitter user follows.</li>
<li>
<code>twint -u username --favorites</code> - Collect all the Tweets a user has favorited.</li>
</ul>

# Jupyter notebooks run an event loop when the kernel starts
# the library below helps separate the loops from that of the kernel and that of twint
!pip install nest_asyncio


```python
# remeding the situation
import nest_asyncio
nest_asyncio.apply()
```


```python
import twint
```

## Defining variables

username = "simbatmotsi"
c = twint.Config() # initializing the config class

# Return tweets sent by an user that contain links

c.Username = username
c.Links = "include"

twint.run.Search(c)

# Scrape a person's followers.

twint.run.Followers(c) # returning the list of followers

# Return tweets sent by an user that used the web client

c.Username = username
c.Source = "Twitter Web Client"

twint.run.Search(c)

# Return tweets containing a specific keyword and that have at least 5 likes

c = twint.Config()
c.Username = "simbatmotsi"
c.Search = "Awesome"
c.Min_likes = 5

twint.run.Search(c)

# Filter Tweets before specified year.

c = twint.Config()

username = "simbatmotsi"
c.Username = username
c.Year = 2019
#c.Source = "Twitter Web Client"

twint.run.Search(c)

# Filter Tweets sent since date (Example: 2017-12-27).

import datetime

c = twint.Config()

username = "simbatmotsi"
c.Username = username
# <input type="datetime-local" id="birthdaytime" name="birthdaytime">
date = "2019-01-01 08:15:27"

c.Since = date
#c.Source = "Twitter Web Client"

twint.run.Search(c)

# Filter Tweets sent until date (Example: 2017-12-27).

import datetime

c = twint.Config()

username = "simbatmotsi"
c.Username = username
# <input type="datetime-local" id="birthdaytime" name="birthdaytime">
date = "2019-01-01 08:15:27"

c.Until = date
#c.Source = "Twitter Web Client"

twint.run.Search(c)

 # Filter Tweets that might have email addresses.

c = twint.Config()

username = "simbatmotsi"
c.Username = username

c.Email
#c.Source = "Twitter Web Client"

twint.run.Search(c)

# Filter Tweets that might have phone numbers.

c = twint.Config()

username = "simbatmotsi"
c.Username = username

c.Phone
#c.Source = "Twitter Web Client"

twint.run.Search(c)

# Display Tweets only from verified users (Use with -s).

c = twint.Config()

username = "simbatmotsi"
c.Username = username

c.Verified
#c.Source = "Twitter Web Client"

twint.run.Search(c)


```python
"""
--csv	Write as .csv file.
--json	Write as .json file.
"""
```




    '\n--csv\tWrite as .csv file.\n--json\tWrite as .json file.\n'



# Number of Tweets to pull (Increments of 20).

c = twint.Config()

#username = "simbatmotsi"
#c.Username = username
#c.Source = "Twitter Web Client"
c.Near = "Harare"
c.Limit = 1
#c.Source = "Twitter Web Client"

twint.run.Search(c)

# Search Tweets to a user.

c = twint.Config()

username = "simbatmotsi"
c.Username = username

c.To
twint.run.Search(c)

# Search all Tweets associated with a user.

c = twint.Config()

username = "simbatmotsi"
c.Username = username

c.All
twint.run.Search(c)

# Scrape a person's followers.

c = twint.Config()
c.Count = True
username = "simbatmotsi"
c.Username = username

#c.Followers
twint.run.Followers(c)

# Scrape a person's follows.

import datetime

c = twint.Config()
c.Count = True
username = "simbatmotsi"
c.Username = username

twint.run.Following(c)

# Scrape Tweets a user has liked.

c = twint.Config()

username = "simbatmotsi"
c.Username = username

c.Favorites
twint.run.Search(c)

# Include user's Retweets (Warning: limited).

c = twint.Config()

username = "simbatmotsi"
c.Username = username

c.Retweets
twint.run.Search(c)

# Display only Tweets with videos.

c = twint.Config()


username = "simbatmotsi"
c.Username = username

c.Videos

twint.run.Search(c)

# Display only Tweets with images.

c = twint.Config()


username = "simbatmotsi"
c.Username = username

c.Images

twint.run.Search(c)

# Display Tweets with only images or videos. 


```python
c = twint.Config()

username = "simbatmotsi"
c.Username = username

c.Media

twint.run.Lookup(c)
```

    CRITICAL:root:twint.get:User:'NoneType' object is not subscriptable
    


```python

```

# Display replies to a subject.

c = twint.Config()

username = "simbatmotsi"
c.Username = username

c.Replies

twint.run.Lookup(c)

# All replies to the tweet.

c = twint.Config()

username = "simbatmotsi"
c.Username = username

c.Get_replies = True

twint.run.Lookup(c)


```python
# Scrape popular tweets instead of recent ones.
```


```python
c = twint.Config()

username = "simbatmotsi"
c.Username = username

c.popular_tweets = True

twint.run.Search(c)
```

    CRITICAL:root:twint.get:User:'NoneType' object is not subscriptable
    

    1281203226008793088 2020-07-09 14:27:07 South Africa Standard Time <simbaTmotsi> The f-string  miracle only arrived later on with python 3.6 So l would say backwards compatibility and not spending time reading the docs
    1277307007230455809 2020-06-28 20:24:56 South Africa Standard Time <simbaTmotsi> Sharing is caring 👌🏽 https://twitter.com/PyTorch/status/1277305148197359617 …
    1276773040777560064 2020-06-27 09:03:08 South Africa Standard Time <simbaTmotsi> We are live 😁
    1274650316710043648 2020-06-21 12:28:12 South Africa Standard Time <simbaTmotsi> 😂 @shamu_shingai https://twitter.com/ravinwashere/status/1274590429082681345 …
    1269192962573053953 2020-06-06 11:02:37 South Africa Standard Time <simbaTmotsi> This is priceless 👌🏿 https://twitter.com/mrdbourke/status/1269087741137960961 …
    1266264595775107074 2020-05-29 09:06:20 South Africa Standard Time <simbaTmotsi> @DonC263 l died https://twitter.com/hatiperi_wacho/status/1266088378799448065 …
    1253376609979072514 2020-04-23 19:34:05 South Africa Standard Time <simbaTmotsi> 😂 @wishfulbrooklyn
    1250893194658709504 2020-04-16 23:05:52 South Africa Standard Time <simbaTmotsi> Now that's a sweet deal
    1240615229375033351 2020-03-19 14:24:54 South Africa Standard Time <simbaTmotsi> Thank you @365datascience pic.twitter.com/ysAptFpCfQ
    1220600477978636288 2020-01-24 08:53:26 South Africa Standard Time <simbaTmotsi> I would suggest "It's My Life' by Bon Jovi.
    1213887499401076736 2020-01-05 20:18:27 South Africa Standard Time <simbaTmotsi> Wouldn't applying AI to biotechnology yield faster results?
    1213535358014676994 2020-01-04 20:59:10 South Africa Standard Time <simbaTmotsi> 2020 will be the year many startups will be offering services to Port over code to Python3
    1210209241547649025 2019-12-26 16:42:22 South Africa Standard Time <simbaTmotsi> If ever l get my hands on one again l will ship it directly to you, promise🤞🏼
    1210160636405137408 2019-12-26 13:29:14 South Africa Standard Time <simbaTmotsi> Unfortunately no 😭
    1210025877892980746 2019-12-26 04:33:45 South Africa Standard Time <simbaTmotsi> The experiment didn't kick of because l was expecting more but only had one.
    1209201587371024391 2019-12-23 21:58:18 South Africa Standard Time <simbaTmotsi> Hello world, please assist to help a friend have her surgery. https://www.gofundme.com/f/help-my-sister-yemurai-fight-lupus?utm_source=customer&utm_medium=copy_link-tip&utm_campaign=p_cp+share-sheet …
    1207379344450043905 2019-12-18 21:17:22 South Africa Standard Time <simbaTmotsi> Seems like the government of Finland is taking AI seriously, hope others will follow suit. https://twitter.com/HarareAi/status/1207377702233268231 …
    1205590338682970112 2019-12-13 22:48:30 South Africa Standard Time <simbaTmotsi> This will be interesting, wonder what headlines related to bio-hacking will be trending.
    1205589674892378112 2019-12-13 22:45:51 South Africa Standard Time <simbaTmotsi> Can't believe for the first time l actually have volunteers to give their data for free, we need to get more of these this side
    1205512456707149825 2019-12-13 17:39:01 South Africa Standard Time <simbaTmotsi> My sister brings me this PillCam and she was like you are the Comp Vision guy what can you do with it? Immediately thought of @berilsirmacek pic.twitter.com/hp51rqvBns
    1205235505450889216 2019-12-12 23:18:31 South Africa Standard Time <simbaTmotsi> For those who would like to get in touch with @alliance4ai  here are some useful links. pic.twitter.com/VMGt5KBP9J
    1195774971106250753 2019-11-16 20:45:44 South Africa Standard Time <simbaTmotsi> Wow congratulations
    1195764979376496641 2019-11-16 20:06:01 South Africa Standard Time <simbaTmotsi> A shift from #tech to celebrating Sensei Knowledge Chikondowa @Dr_Logos , this young man has been lifting the Zimbabwean flag high.   https://www.facebook.com/talkversations/videos/2530811480533735/ … pic.twitter.com/Xc0ln5PsVP
    1192876592818769920 2019-11-08 20:48:36 South Africa Standard Time <simbaTmotsi> That's true, that helps maintain the viability of the industry.
    1192198320854355968 2019-11-06 23:53:24 South Africa Standard Time <simbaTmotsi> Thank you for that, the team tried to meaningful work around the continent.
    1192035945094287360 2019-11-06 13:08:10 South Africa Standard Time <simbaTmotsi> Hello world, for those who have time to spare and are willing to help teach a child to code, this is the event for you.  Sign up link:  http://africacodeweek2k19.splashthat.com  pic.twitter.com/a35IBkoLle
    1185632775514271750 2019-10-19 21:04:16 South Africa Standard Time <simbaTmotsi> 😂 there is no shame in acknowledging greatness
    1184588770366119936 2019-10-16 23:55:46 South Africa Standard Time <simbaTmotsi> This can significantly lower movie production costs
    1183029284975337473 2019-10-12 16:38:55 South Africa Standard Time <simbaTmotsi> Coz he took time to know we exist and mention it 😅. All in French
    1181981806222069760 2019-10-09 19:16:37 South Africa Standard Time <simbaTmotsi> This is the ultimate guide to go from zero to hero in computer vision thank you and a job well done 👏🏿👏🏿👏🏿
    1179448265315631104 2019-10-02 19:29:14 South Africa Standard Time <simbaTmotsi> It's on again. @lassie034 @HarareAi @SchoolOfAIOffic pic.twitter.com/nQuKbYS518
    1179331059386929153 2019-10-02 11:43:30 South Africa Standard Time <simbaTmotsi> pip install tensorflow The command above is the non GPU version install command.
    1179330427124887552 2019-10-02 11:40:59 South Africa Standard Time <simbaTmotsi> pip install tensorflow That's the non GPU version. Recently installed the GPU version on my workstationrunning ubuntu
    1179091121026342914 2019-10-01 19:50:04 South Africa Standard Time <simbaTmotsi> #TF2.0 pic.twitter.com/B0J4BaBwpm
    1172377767544946690 2019-09-13 07:13:36 South Africa Standard Time <simbaTmotsi> Awesome stuff @tahtshuma looking forward to working will you. https://twitter.com/HarareAi/status/1172377319517741056 …
    1172193500768722944 2019-09-12 19:01:23 South Africa Standard Time <simbaTmotsi> So keras is still our savior ✍️
    1168198904288034821 2019-09-01 18:28:17 South Africa Standard Time <simbaTmotsi> Haha... So l am not the only one who suffers from imposter syndrome, nice to meet you fellow patient.
    1167506464119959552 2019-08-30 20:36:46 South Africa Standard Time <simbaTmotsi> Another library to add to the arsenal 👏🏼
    1167087041127112704 2019-08-29 16:50:08 South Africa Standard Time <simbaTmotsi> Mainly geopandas and mplleaflet, will tag you when the resources are uploaded to GitHub
    1167015742824419329 2019-08-29 12:06:49 South Africa Standard Time <simbaTmotsi> We all learn new things everyday 😅
    1165637603758170112 2019-08-25 16:50:35 South Africa Standard Time <simbaTmotsi> Well done Marly 🇿🇼
    1161696209343586304 2019-08-14 19:48:54 South Africa Standard Time <simbaTmotsi> Life keeps getting better https://twitter.com/suzatweet/status/1161474539278258178 …
    1151090210236710914 2019-07-16 13:24:26 South Africa Standard Time <simbaTmotsi> To think that around all this chaos we still have those that work towards making the next persons life a little bit easier
    1141104926430584834 2019-06-19 00:06:29 South Africa Standard Time <simbaTmotsi> Congratulations @marlene_zw
    1139657933581639680 2019-06-15 00:16:39 South Africa Standard Time <simbaTmotsi> Good to know that they keep optimizing tf.keras
    1138422429729132544 2019-06-11 14:27:12 South Africa Standard Time <simbaTmotsi> Hi Nigel. @yattishr is your Dean and he hosted his first meetup today.
    1138237569068670976 2019-06-11 02:12:38 South Africa Standard Time <simbaTmotsi> Hello @Mbongen13986503 your local Dean is Yattish Ramhorry. Will forward you his Twitter handle as soon as he forwards it.
    1123635626719498241 2019-05-01 19:09:44 South Africa Standard Time <simbaTmotsi> Please subscribe to our fellow School of AI Dean @berilsirmacek YouTube channel to know about all the cool things in AI. Link: https://www.youtube.com/drsirmacek/videos … #womenintech
    1123558269795086336 2019-05-01 14:02:20 South Africa Standard Time <simbaTmotsi> I just signed the #GlobalDealForNature calling on world leaders to protect half of our lands and seas. Please join me! Sign the petition at  http://globaldealfornature.org/  pic.twitter.com/oLdepKQeep
    1121389621668122624 2019-04-25 14:24:54 South Africa Standard Time <simbaTmotsi>  https://welovetheearth.org/act-now/ 
    1120458698881630209 2019-04-23 00:45:45 South Africa Standard Time <simbaTmotsi> Python And web assembly, this is an awesome read.👌🏾  https://almarklein.org/python_and_webassembly.html …
    1102075553669136385 2019-03-03 07:17:42 South Africa Standard Time <simbaTmotsi> Welcome @lbleal1
    1101851454581735426 2019-03-02 16:27:12 South Africa Standard Time <simbaTmotsi> There is a Data analysis course offered by IBM on their cognitive AI platform, which is a great start.  http://bit.ly/dataPath  Then this  http://bit.ly/DataPathGuide  complete guide if you wanna take it up to the next level. Tried shortening the links for convenience.
    1101844427969044485 2019-03-02 15:59:17 South Africa Standard Time <simbaTmotsi> Python is the way😎
    1097944147003084800 2019-02-19 21:40:58 South Africa Standard Time <simbaTmotsi>  https://www.hackerearth.com/challenges/hiring/esri-data-science-challenge-2019/ …
    1096755568952397830 2019-02-16 14:57:59 South Africa Standard Time <simbaTmotsi> Wow we are truly the age that will transform humanity, the world need check out singularitynet l know @sirajraval likes DApps and @berilsirmacek wants to help the human race. @SchoolOfAIOffic & @motor_ai  what do you think of this concept? link:  http://beta.singularitynet.io/ 
    1095775953157083143 2019-02-13 22:05:20 South Africa Standard Time <simbaTmotsi> Thank you very much @berilsirmacek it is always a delight working with trail blazers of our time such as you. https://twitter.com/berilsirmacek/status/1095774118958514177 …
    1095462975924813824 2019-02-13 01:21:40 South Africa Standard Time <simbaTmotsi> This is a great read. Capsule Networks: The New Deep Learning Network by Aryan Misra  https://medium.com/p/capsule-networks-the-new-deep-learning-network-bd917e6818e8 …
    1092821170041356289 2019-02-05 18:24:05 South Africa Standard Time <simbaTmotsi>  https://www.credential.net/12506518   Thank you @sirajraval and @SchoolOfAIOffic @HarareAi
    1087818984580362240 2019-01-22 23:07:11 South Africa Standard Time <simbaTmotsi> I would recommend splitting the problem into two; diagnosis and detection. Then the diagnosis data along with historic data will aid in the cholera prediction
    1082699088142000129 2019-01-08 20:02:32 South Africa Standard Time <simbaTmotsi> Generally GPUs accelerate computation resulting in smaller training speeds. TPUs are more optimized for Tensorflow
    1082696431939584001 2019-01-08 19:51:59 South Africa Standard Time <simbaTmotsi> The iris dataset is good were you training with the GPU or TPU feature on, that might also affect performance
    1082692972951556096 2019-01-08 19:38:14 South Africa Standard Time <simbaTmotsi> The images are of imagenet and was using the Resnet50 architecture
    1082692479030382592 2019-01-08 19:36:17 South Africa Standard Time <simbaTmotsi> No l was benchmarking our workstation against that of @LambdaAPI
    1082690829192441856 2019-01-08 19:29:43 South Africa Standard Time <simbaTmotsi> Ubuntu 18.04 32GB RAM Cuda: 10.0 Nvidia driver: 415.25 GTX 1080ti x3  tf_cnn_benchmarks batch_size=64 Model=resnet50 @LambaAPI 757.95 images per second @HarareAi @sirajraval @wishfulbrooklyn pic.twitter.com/GTFNS29oU7
    1081638106514841600 2019-01-05 21:46:35 South Africa Standard Time <simbaTmotsi> Deep Learning is a superpower. With it you can make a computer see, synthesize novel art, translate languages, render a medical diagnosis, or build pieces of a car that can drive itself. If that isn’t a superpower, I don’t know what is. — @AndrewYNg
    1081636335159574528 2019-01-05 21:39:32 South Africa Standard Time <simbaTmotsi> Get ready for an interesting journey
    1076199070488842251 2018-12-21 21:33:47 South Africa Standard Time <simbaTmotsi> Awesome, making the right moves towards providing AI for all  @HarareAi @zimbopy @marlene_zw @zimbopy @marlene_zw @tchagwiza @yollandag @shamu_shingai @sirajraval @berilsirmacek @SchoolOfAIOffic @motor_ai @ai https://twitter.com/HarareAi/status/1076197748469387264 …
    1069151852338524160 2018-12-02 10:50:40 South Africa Standard Time <simbaTmotsi> AI is being open sourced daily https://twitter.com/HarareAi/status/1069150863019687936 …
    1068573427777314818 2018-11-30 20:32:12 South Africa Standard Time <simbaTmotsi> So true, l always give ladies the example of @berilsirmacek that’s one lady who has gone above and beyond with tech. https://twitter.com/DigitalBaeZWE/status/1068503642842562567 …
    1067529937459007490 2018-11-27 23:25:45 South Africa Standard Time <simbaTmotsi> Yeay to open source https://twitter.com/darrinpjohnson/status/1067504581519667200 …
    1066218772254662656 2018-11-24 08:35:39 South Africa Standard Time <simbaTmotsi> AI has no age limit https://twitter.com/DigitalBaeZWE/status/1066217859188183040 …
    1060433954006798336 2018-11-08 09:28:51 South Africa Standard Time <simbaTmotsi> So true we need to take action to protect Africa’s digital future.
    1060198531036835846 2018-11-07 17:53:21 South Africa Standard Time <simbaTmotsi> Often we use free material and take little or no time to acknowledge the great work.
    1055785175827841024 2018-10-26 13:36:16 South Africa Standard Time <simbaTmotsi> Great talk with various @UN representatives in #Harare definitely looking forward to partnering in future. #HarareSchoolOfAi @SchoolOfAIOffic @tchagwiza @sirajraval pic.twitter.com/vKQ5t3g2sK
    1055723105526734848 2018-10-26 09:29:37 South Africa Standard Time <simbaTmotsi> UN is Harare, perfect opportunity to see how we can have @SchoolOfAIOffic can help out. @sirajraval @lassie034 @shamu_shingai @tchagwiza @yollandag #HarareSchoolOfAi pic.twitter.com/MUo1oSZ3xt
    1055361483763269632 2018-10-25 09:32:40 South Africa Standard Time <simbaTmotsi> Would have loved to be part of that lecture 😊
    1053338575411052545 2018-10-19 19:34:21 South Africa Standard Time <simbaTmotsi> @sirajraval #HarareSchoolOfAi @pycon_zim  thank you for inviting us. https://twitter.com/DigitalBaeZWE/status/1053294806867288064 …
    1052488673726480385 2018-10-17 11:17:08 South Africa Standard Time <simbaTmotsi> Congratulations @tchagwiza  you are now officially a research fellow for the @SchoolOfAIOffic .   @sirajraval Thank you for for offering a member of #HarareSchoolOfAi such a splendid opportunity. #SchoolOfAi pic.twitter.com/e9Fkwhh9BD
    1052292157741129728 2018-10-16 22:16:15 South Africa Standard Time <simbaTmotsi> Apologies for the late response, l haven’t yet mainly coz the thought had never crossed my mind before. But definitely looking forward to trying it out.
    1051923313470128128 2018-10-15 21:50:36 South Africa Standard Time <simbaTmotsi> AMAZING... https://twitter.com/sirajraval/status/1051843975160549376 …
    1049600633379192832 2018-10-09 12:01:06 South Africa Standard Time <simbaTmotsi> Well done, taking the first step is always the hardest. So proud to have you representing #HarareSchoolOfAi #SchoolOfAi
    1047093781219151874 2018-10-02 13:59:46 South Africa Standard Time <simbaTmotsi> Well done young wizard @sirajraval https://twitter.com/lassie034/status/1047001931376447488 …
    1043163188018196486 2018-09-21 17:40:59 South Africa Standard Time <simbaTmotsi> Our young AI wizards tinkering with their arduino board... light is blinking good start guys; these kids have a lot of potential. #SchoolOfAI #HarareSchoolOfAI pic.twitter.com/bEiyT2nbVs
    1040230024174088192 2018-09-13 15:25:38 South Africa Standard Time <simbaTmotsi>  https://www.un.org/sustainabledevelopment/sustainable-development-goals/ … Let’s all play our part in making the world a better place for all #HarareSchoolOfAI #SchoolOfAI
    1038525886172225536 2018-09-08 22:34:00 South Africa Standard Time <simbaTmotsi> Chatting with a fellow Dean is amazing but getting a visit ...  #HarareSchoolOfAI would be honored to have you @sirajraval thank you @berilsirmacek #schoolofai pic.twitter.com/2okDnxJKxi
    1038094581995384832 2018-09-07 18:00:09 South Africa Standard Time <simbaTmotsi> Thank you for the chat it’s always interesting meeting incredible people  https://youtu.be/5K0WPTFbdgM  @berilsirmacek @sirajraval #SchoolOfAI #HarareSchoolOfAI
    1037812097915281409 2018-09-06 23:17:40 South Africa Standard Time <simbaTmotsi> Don’t worry we never leave anyone behind
    1037368083709616128 2018-09-05 17:53:19 South Africa Standard Time <simbaTmotsi> Start making your own Siri, lets go step-by-step  https://harareschoolofai.github.io/Word_based_NLP/  #HarareSchoolOfAI #SchoolOfAI
    1036357763671236608 2018-09-02 22:58:40 South Africa Standard Time <simbaTmotsi> In your opinion is it worth specializing in computer vision only rather than other AI fields? #100DaysofMLCode
    1035046143787520000 2018-08-30 08:06:45 South Africa Standard Time <simbaTmotsi> @wishfulbrooklyn
    1035045870721544192 2018-08-30 08:05:40 South Africa Standard Time <simbaTmotsi> @wishfulbrooklyn honawo
    1032292141777739778 2018-08-22 17:43:20 South Africa Standard Time <simbaTmotsi>  https://www.youtube.com/watch?v=_7TvMA_w8xw … AI wizards 🧙🏾‍♂️ lets help each other make the world a greater place #SchoolOfAI #HarareSchoolOfAI @sirajraval pic.twitter.com/U8NbkNgbp4
    1031968860952584193 2018-08-21 20:18:44 South Africa Standard Time <simbaTmotsi> I am always moved with the way you empower the girl child to disrupt the tech landscape 👍🏾
    1031185029244833797 2018-08-19 16:24:04 South Africa Standard Time <simbaTmotsi> You are always welcome
    1031073109045141504 2018-08-19 08:59:20 South Africa Standard Time <simbaTmotsi> Yes with Doc Panashe he will be there
    1031062993021358080 2018-08-19 08:19:08 South Africa Standard Time <simbaTmotsi> We are a learning community that teaches AI for free, we have regular meetings on Wednesday and Friday at the ZCHPC from 1530hrs
    1030489132966006784 2018-08-17 18:18:49 South Africa Standard Time <simbaTmotsi>  https://github.com/HarareSchoolOfAI/California-House-Data … GitHub link to our lecture today, "Playing with California housing data (1990)". That will be your source for more code as well @lassie034 @sirajraval #SchoolOfAI #HarareSchoolOfAI shout out to our sponsor  http://DeepAnalytics.ai 
    1030485122003476480 2018-08-17 18:02:53 South Africa Standard Time <simbaTmotsi> We had a WordPress representative @tchagwiza visit us today, and these guys don’t wanna leave though we finished a while ago 😂 @Rabchit @sirajraval #SchoolOfAI #HarareSchoolOfAI pic.twitter.com/IVpdlfJIAE
    1030484817043959808 2018-08-17 18:01:40 South Africa Standard Time <simbaTmotsi>  pic.twitter.com/R9H0EKNbwc
    1030094643210461186 2018-08-16 16:11:15 South Africa Standard Time <simbaTmotsi>  pic.twitter.com/PXx5RFnXkI
    1030091609835286529 2018-08-16 15:59:12 South Africa Standard Time <simbaTmotsi> 😂 that screen 📺 is to be upgraded to support support medical imaging.
    1029781843623768067 2018-08-15 19:28:18 South Africa Standard Time <simbaTmotsi> Thank you 😊 for the opportunity
    1029766130536202241 2018-08-15 18:25:52 South Africa Standard Time <simbaTmotsi>  https://drive.google.com/open?id=1bcntnoS4eNQ6KTUplP9ApXf4elZg-LZx … link to our first #HarareSchoolOfAI  lecture thanks to our sponsor  http://DeepAnalytics.ai  #SchoolOfAI @sirajraval
    1029760371505197056 2018-08-15 18:02:59 South Africa Standard Time <simbaTmotsi> First day as the Dean of #HarareSchoolOfAI we did an introduction to Keras and thank you to our official sponsor  http://DeepAnalytic.ai  @sirajraval #schoolofai @lassie034 pic.twitter.com/Bo9sATUxAP
    1029520874154680321 2018-08-15 02:11:18 South Africa Standard Time <simbaTmotsi> Wow thank you for the support #HarareSchoolOfAI already over 200 members since it started just about 48 hours ago, we are even negotiating with a potential sponsor Thank you 🙏 #SchoolOfAI @marlene_zw @sirajraval @shamu_shingai
    1029317676571742208 2018-08-14 12:43:52 South Africa Standard Time <simbaTmotsi> Harare school of AI  https://m.facebook.com/groups/228980571291404 … @sirajraval #SchoolOfAI #HarareSchoolOfAI
    1029031771801829376 2018-08-13 17:47:47 South Africa Standard Time <simbaTmotsi> Honored to be selected to be a Dean of AI @sirajraval  thank you, #HarareSchoolOfAI #SchoolOfAI
    1026176757332934659 2018-08-05 20:42:59 South Africa Standard Time <simbaTmotsi> Just because you can make a CNN doesn’t mean you always apply it, at times open cv has got your back🧙🏾‍♂️ pic.twitter.com/OMFKzauPGU
    1026161814864887809 2018-08-05 19:43:36 South Africa Standard Time <simbaTmotsi> #schoolofai Applied to represent Harare, Zimbabwe is represented to be part of the community
    961206083820941313 2018-02-07 13:52:43 South Africa Standard Time <simbaTmotsi> Mr Musk, now that you exported another car to Mars are you paying the Martians import duty...lol
    956900555561029633 2018-01-26 16:44:05 South Africa Standard Time <simbaTmotsi> Natural language processing
    946324438940823552 2017-12-28 12:18:22 South Africa Standard Time <simbaTmotsi> All in captain
    945674116312518657 2017-12-26 17:14:13 South Africa Standard Time <simbaTmotsi> In my opinion it is as a result of the material(data) we are exposed as we grow, the same way many systems are flawed, so are our minds
    929370318166208513 2017-11-11 17:28:45 South Africa Standard Time <simbaTmotsi> I was double charged for a transaction, now trying to call ecocash but can't get through
    916882345596203008 2017-10-08 06:26:00 South Africa Standard Time <simbaTmotsi> Hello, Darwendale has been in the dark for about a fortnight now. We were tolf the electric fault wil be rectified promptly but nothing.....
    710453866777747457 2016-03-17 15:12:56 South Africa Standard Time <simbaTmotsi> @HealthTips25 welcome< fitness is the way to go!
    695130715785142272 2016-02-04 08:24:12 South Africa Standard Time <simbaTmotsi> @sparkay_17 Lol.... That is undebateable but for number 2 spot which would you pick?
    694904871074586624 2016-02-03 17:26:46 South Africa Standard Time <simbaTmotsi> @sparkay_17 @econet_support The bigger you are the harder it is to admit defeat, any excuse given may ruin their reputation
    694841680969797632 2016-02-03 13:15:40 South Africa Standard Time <simbaTmotsi> @sparkay_17 Agreed... But then we know they aren't going to fill us in
    694840847045623808 2016-02-03 13:12:22 South Africa Standard Time <simbaTmotsi> @sparkay_17 *like
    694840657236639744 2016-02-03 13:11:36 South Africa Standard Time <simbaTmotsi> @sparkay_17 lol... it's not lie they can tweet the error code
    694839800285810688 2016-02-03 13:08:12 South Africa Standard Time <simbaTmotsi> @sparkay_17 https://twitter.com/econetzimbabwe/status/694788077886242816 …
    694839800277372928 2016-02-03 13:08:12 South Africa Standard Time <simbaTmotsi> @sparkay_17 tech prob, services will be up soon
    694832259069800448 2016-02-03 12:38:14 South Africa Standard Time <simbaTmotsi> @sparkay_17 lol... Atleast they gave an explanation
    503491270917259264 2014-08-24 12:37:28 South Africa Standard Time <simbaTmotsi> Go slow, Get BIG!!! #mostie
    


```python

```

c = twint.Config()

username = "simbatmotsi"
c.Username = username

c.Native_retweets = True

twint.run.Search(c)

# Exclude retweets from the results.

c = twint.Config()

username = "simbatmotsi"
c.Username = username

c.filter_retweets = True

twint.run.Search(c)


```python

```

<p>Basically we can get users (and their information) and tweets. But there are various ways to get tweet and user objects.</p>

<h1>Tweets</h1>

<p>We can get tweets in three ways:</p>

<ul>
<li>searching for them, <code>twint.run.Search</code>
</li>
<li>scraping the user's timeline, <code>twint.run.Profile</code>
</li>
<li>scraping the favorite tweets of an user, <code>twint.run.Favorites</code>
</li>
</ul>

<h1>Users</h1>

<p>We can get only the usernames about the followers/following of a specific user:</p>

<ul>
<li>followers: <code>twint.run.Followers</code>
</li>
<li>following: <code>twint.run.Following</code>
</li>
</ul>

<p>We can also get the information about the followers/following of a specific user, or even just the user itself:</p>

<ul>
<li>followers/following, just add <code>config.User_full = True</code>
</li>
<li>single user: <code>twint.run.Lookup</code>
</li>
</ul>




```python

```


```python

```


```python

```
