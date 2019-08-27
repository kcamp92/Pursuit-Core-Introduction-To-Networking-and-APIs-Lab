# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200
1. 301
1. 400
1. 401
1. 403
1. 404
1. 418
1. 500

Codes 

1. 200
-www.instagram.com
-OK
- No need to do anything.

2. 301
-
- Moved Permanently
-

3. 400
-
- Bad Request
-

4. 401
-
-
-

5. 403
-
-
-

6. 404
- https://www.facebook.com/krystal.campbell
- Not found
-

7. 418
-
-
-

8. 500
-
-
-

For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
- https://catfact.ninja/facts
```
-   "total": 308,
"per_page": 1,
"current_page": 1,
"last_page": 308,
"next_page_url": "https://catfact.ninja/facts?page=2",
"prev_page_url": null,
"from": 1,
"to": 1,
"data": [
{
"fact": "Cat families usually play best in even numbers. Cats and kittens should be acquired in pairs whenever possible.",
"length": 111
}
]
}
```

1. A list of 150 random users in English.



1. The current stock price of Microsoft. (IEX API)
1. The 5 year history of Apple stock prices (IEX API)
1. All the Swift language repos on Github with Pursuit in their name

1. A list of all Pokemon

https://pokemondb.net/pokedex/national --only posted a portion of the list
```
<span class="infocard-lg-img"><a href="/pokedex/bulbasaur"><span class="img-fixed img-sprite" data-src="https://img.pokemondb.net/sprites/omega-ruby-alpha-sapphire/dex/normal/bulbasaur.png" data-alt="Bulbasaur icon"></span></a></span><span class="infocard-lg-data text-muted"><small>#001</small><br><a class="ent-name" href="/pokedex/bulbasaur">Bulbasaur</a><br><small><a href="/type/grass" class="itype grass">Grass</a> &middot; <a href="/type/poison" class="itype poison">Poison</a></small></span>
</div>
<div class="infocard ">
<span class="infocard-lg-img"><a href="/pokedex/ivysaur"><span class="img-fixed img-sprite" data-src="https://img.pokemondb.net/sprites/omega-ruby-alpha-sapphire/dex/normal/ivysaur.png" data-alt="Ivysaur icon"></span></a></span><span class="infocard-lg-data text-muted"><small>#002</small><br><a class="ent-name" href="/pokedex/ivysaur">Ivysaur</a><br><small><a href="/type/grass" class="itype grass">Grass</a> &middot; <a href="/type/poison" class="itype poison">Poison</a></small></span>
</div>
<div class="infocard ">
<span class="infocard-lg-img"><a href="/pokedex/venusaur"><span class="img-fixed img-sprite" data-src="https://img.pokemondb.net/sprites/omega-ruby-alpha-sapphire/dex/normal/venusaur.png" data-alt="Venusaur icon"></span></a></span><span class="infocard-lg-data text-muted"><small>#003</small><br><a class="ent-name" href="/pokedex/venusaur">Venusaur</a><br><small><a href="/type/grass" class="itype grass">Grass</a> &middot; <a href="/type/poison" class="itype poison">Poison</a></small></span>
</div>
<div class="infocard ">
<span class="infocard-lg-img"><a href="/pokedex/charmander"><span class="img-fixed img-sprite" data-src="https://img.pokemondb.net/sprites/omega-ruby-alpha-sapphire/dex/normal/charmander.png" data-alt="Charmander icon"></span></a></span><span class="infocard-lg-data text-muted"><small>#004</small><br><a class="ent-name" href="/pokedex/charmander">Charmander</a><br><small><a href="/type/fire" class="itype fire">Fire</a></small></span>
</div>
<div class="infocard ">
<span class="infocard-lg-img"><a href="/pokedex/charmeleon"><span class="img-fixed img-sprite" data-src="https://img.pokemondb.net/sprites/omega-ruby-alpha-sapphire/dex/normal/charmeleon.png" data-alt="Charmeleon icon"></span></a></span><span class="infocard-lg-data text-muted"><small>#005</small><br><a class="ent-name" href="/pokedex/charmeleon">Charmeleon</a><br><small><a href="/type/fire" class="itype fire">Fire</a></small></span>
</div>
```
1. A list of all items in Fortnite
1. A list of all Game of Thrones Episodes.

https://github.com/kcamp92/AC-iOS-GOT/blob/master/GOT-StudentVersion/GOT-StudentVersion/GOTEpisdoe.swift
```
<span class="pl-s"><span class="pl-pds">&quot;</span>Winter is
Coming<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">number</span>: <span class="pl-c1">1</span>,
<span class="pl-c1">season</span>: <span class="pl-c1">1</span>,
<span class="pl-c1">runtime</span>: <span class="pl-c1">60</span>,
<span class="pl-c1">summary</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>Lord Eddard Stark,
ruler of the North, is summoned to court by his old friend, King Robert
Baratheon, to serve as the King&#39;s Hand. Eddard reluctantly agrees after
learning of a possible threat to the King&#39;s life. Eddard&#39;s bastard
son Jon Snow must make a painful decision about his own future, while in the
distant east Viserys Targaryen plots to reclaim his father&#39;s throne,
usurped by Robert, by selling his sister in
marriage.<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">mediumImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2668<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">originalImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2668<span class="pl-pds">&quot;</span></span>),
</td>
</tr>
<tr>
<td id="L34" class="blob-num js-line-number" data-line-number="34"></td>
<td id="LC34" class="blob-code blob-code-inner js-file-line">
<span class="pl-c1">GOTEpisode</span>(<span class="pl-c1">airdate</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2011-04-24<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">id</span>: <span class="pl-c1">4953</span>,
<span class="pl-c1">name</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>The
Kingsroad<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">number</span>: <span class="pl-c1">2</span>,
<span class="pl-c1">season</span>: <span class="pl-c1">1</span>,
<span class="pl-c1">runtime</span>: <span class="pl-c1">60</span>,
<span class="pl-c1">summary</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>An incident on the
Kingsroad threatens Eddard and Robert&#39;s friendship. Jon and Tyrion
travel to the Wall, where they discover that the reality of the Night&#39;s
Watch may not match the heroic image of
it.<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">mediumImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2669<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">originalImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2669<span class="pl-pds">&quot;</span></span>),
</td>
</tr>
<tr>
<td id="L35" class="blob-num js-line-number" data-line-number="35"></td>
<td id="LC35" class="blob-code blob-code-inner js-file-line">
<span class="pl-c1">GOTEpisode</span>(<span class="pl-c1">airdate</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2011-05-01<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">id</span>: <span class="pl-c1">4954</span>,
<span class="pl-c1">name</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>Lord
Snow<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">number</span>: <span class="pl-c1">3</span>,
<span class="pl-c1">season</span>: <span class="pl-c1">1</span>,
<span class="pl-c1">runtime</span>: <span class="pl-c1">60</span>,
<span class="pl-c1">summary</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>Jon Snow attempts to
find his place amongst the Night&#39;s Watch. Eddard and his daughters
arrive at King&#39;s Landing.<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">mediumImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2671<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">originalImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2671<span class="pl-pds">&quot;</span></span>),
</td>
</tr>
<tr>
<td id="L36" class="blob-num js-line-number" data-line-number="36"></td>
<td id="LC36" class="blob-code blob-code-inner js-file-line">
<span class="pl-c1">GOTEpisode</span>(<span class="pl-c1">airdate</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2011-05-08<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">id</span>: <span class="pl-c1">4955</span>,
<span class="pl-c1">name</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>Cripples, Bastards, and
Broken Things<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">number</span>: <span class="pl-c1">4</span>,
<span class="pl-c1">season</span>: <span class="pl-c1">1</span>,
<span class="pl-c1">runtime</span>: <span class="pl-c1">60</span>,
<span class="pl-c1">summary</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>Tyrion stops at
Winterfell on his way home and gets a frosty reception from Robb Stark.
Eddard&#39;s investigation into the death of his predecessor gets
underway.<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">mediumImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2673<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">originalImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2673<span class="pl-pds">&quot;</span></span>),
</td>
</tr>
<tr>
<td id="L37" class="blob-num js-line-number" data-line-number="37"></td>
<td id="LC37" class="blob-code blob-code-inner js-file-line">
<span class="pl-c1">GOTEpisode</span>(<span class="pl-c1">airdate</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2011-05-15<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">id</span>: <span class="pl-c1">4956</span>,
<span class="pl-c1">name</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>The Wolf and the
Lion<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">number</span>: <span class="pl-c1">5</span>,
<span class="pl-c1">season</span>: <span class="pl-c1">1</span>,
<span class="pl-c1">runtime</span>: <span class="pl-c1">60</span>,
<span class="pl-c1">summary</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>Catelyn&#39;s actions
on the road have repercussions for Eddard. Tyrion enjoys the dubious
hospitality of the Eyrie.<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">mediumImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2674<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">originalImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2674<span class="pl-pds">&quot;</span></span>),
</td>
</tr>
<tr>
<td id="L38" class="blob-num js-line-number" data-line-number="38"></td>
<td id="LC38" class="blob-code blob-code-inner js-file-line">
<span class="pl-c1">GOTEpisode</span>(<span class="pl-c1">airdate</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2011-05-22<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">id</span>: <span class="pl-c1">4957</span>,
<span class="pl-c1">name</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>A Golden
Crown<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">number</span>: <span class="pl-c1">6</span>,
<span class="pl-c1">season</span>: <span class="pl-c1">1</span>,
<span class="pl-c1">runtime</span>: <span class="pl-c1">60</span>,
<span class="pl-c1">summary</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>Viserys is increasingly
frustrated by the lack of progress towards gaining his
crown.<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">mediumImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2676<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">originalImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2676<span class="pl-pds">&quot;</span></span>),
</td>
</tr>
<tr>
<td id="L39" class="blob-num js-line-number" data-line-number="39"></td>
<td id="LC39" class="blob-code blob-code-inner js-file-line">
<span class="pl-c1">GOTEpisode</span>(<span class="pl-c1">airdate</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2011-05-29<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">id</span>: <span class="pl-c1">4958</span>,
<span class="pl-c1">name</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>You Win or You
Die<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">number</span>: <span class="pl-c1">7</span>,
<span class="pl-c1">season</span>: <span class="pl-c1">1</span>,
<span class="pl-c1">runtime</span>: <span class="pl-c1">60</span>,
<span class="pl-c1">summary</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>Eddard&#39;s
investigations in King&#39;s Landing reach a climax and a dark secret is
revealed.<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">mediumImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2677<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">originalImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2677<span class="pl-pds">&quot;</span></span>),
</td>
</tr>
<tr>
<td id="L40" class="blob-num js-line-number" data-line-number="40"></td>
<td id="LC40" class="blob-code blob-code-inner js-file-line">
<span class="pl-c1">GOTEpisode</span>(<span class="pl-c1">airdate</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2011-06-05<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">id</span>: <span class="pl-c1">4959</span>,
<span class="pl-c1">name</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>The Pointy
End<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">number</span>: <span class="pl-c1">8</span>,
<span class="pl-c1">season</span>: <span class="pl-c1">1</span>,
<span class="pl-c1">runtime</span>: <span class="pl-c1">60</span>,
<span class="pl-c1">summary</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>Tyrion joins his
father&#39;s army with unexpected allies. Events in King&#39;s Landing take
a turn for the worse as Arya&#39;s lessons are put to the
test.<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">mediumImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2678<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">originalImageID</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>2678<span class="pl-pds">&quot;</span></span>),
</td>
</tr>
<tr>
```
1. A list of all songs with "Love" in the title.

https://github.com/joinpursuit/SongsSearchBar/blob/master/SongsTableViewSearchBar/Song.swift

```
td id="L46" class="blob-num js-line-number" data-line-number="46"></td>
<td id="LC46" class="blob-code blob-code-inner js-file-line">
<span class="pl-c1">Song</span>(<span class="pl-c1">name</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>Strange Are The Ways Of
Love<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">artist</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>Gogi
Grant<span class="pl-pds">&quot;</span></span>),</td>
</tr>
<tr>
<td id="L47" class="blob-num js-line-number" data-line-number="47"></td>
<td id="LC47" class="blob-code blob-code-inner js-file-line">
<span class="pl-c1">Song</span>(<span class="pl-c1">name</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>Treasure Of Your
Love<span class="pl-pds">&quot;</span></span>,
<span class="pl-c1">artist</span>:
<span class="pl-s"><span class="pl-pds">&quot;</span>Eileen
Rodgers<span class="pl-pds">&quot;</span></span>),</td>
</tr>
<tr>
```

1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in

https://en.wikipedia.org/wiki/Leonardo_DiCaprio_filmography

```

</div>
<p><a href="/wiki/Leonardo_DiCaprio" title="Leonardo DiCaprio">Leonardo DiCaprio</a> is an American
actor, producer and writer who started his career performing as a child on television. He
appeared on the shows
<i><a href="/wiki/The_New_Lassie" title="The New Lassie">The New Lassie</a></i> (1989) and
<i><a href="/wiki/Santa_Barbara_(TV_series)" title="Santa Barbara (TV series)">Santa Barbara</a></i>
(1990) and also had long running roles in the <a href="/wiki/Comedy-drama"
title="Comedy-drama">comedy-drama</a>
<i><a href="/wiki/Parenthood_(1990_TV_series)" title="Parenthood (1990 TV series)">Parenthood</a></i>
(1990) and the <a href="/wiki/Sitcom" title="Sitcom">sitcom</a>
<i><a href="/wiki/Growing_Pains" title="Growing Pains">Growing Pains</a></i> (1991).
Two years later, he played <a href="/wiki/Tobias_Wolff" title="Tobias Wolff">Tobias Wolff</a>
opposite <a href="/wiki/Robert_De_Niro" title="Robert De Niro">Robert De Niro</a> in
<i><a href="/wiki/This_Boy%27s_Life_(film)" title="This Boy&#39;s Life (film)">This Boy's Life</a></i>
(1993), marking this film as his cinematic debut. He followed this with a supporting role in
<i><a href="/wiki/What%27s_Eating_Gilbert_Grape" title="What&#39;s Eating Gilbert Grape">What's Eating Gilbert Grape</a></i>
(1993), which earned him a nomination for the <a
href="/wiki/Academy_Award_for_Best_Supporting_Actor"
title="Academy Award for Best Supporting Actor">Academy Award for Best Supporting
Actor</a>.<sup id="cite_ref-1" class="reference"><a href="#cite_note-1">&#91;1&#93;</a></sup>
In 1995, DiCaprio played the American author <a href="/wiki/Jim_Carroll" title="Jim Carroll">Jim
Carroll</a> in
```

