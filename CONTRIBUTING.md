# Contributing

I would really appreciate people adding podcasts that I've not heard of to the list. It's really easy so follow this page and open a pull request.

# "Rules"

If somebody feels stongly againts any of thease rules I'd happly change them, just open an issue or pull request.
- Currently I'm only listing ongoing podcasts.
- Foreign language podcasts should be seperated into a seperate feeds.opml (feeds-es.opml for Spanish)
- The main page (README.md) should be also be updated when adding an English podcast. Feel free to use [opml2html](https://github.com/Cj-Malone/opml2html) with Markdown and Unordered list selected.
- If the podcast has multiple feeds, audio > video, ogg > mp3, 	Atom > RSS when selectng one.

# How to

Simply `<outline title="{{ Podcast name }}" type="{{ Feed type (rss) }}" xmlUrl="{{ Feed URL }}" htmlUrl="{{ Website }}"/>` substitute the information and append it to the correct feeds file, if 
the Podcast is English also add to the README with `- [[{{ Feed type (RSS) }}]({{ Feed URL }})] [{{ Podcast name }}]({{ Website }})`.
