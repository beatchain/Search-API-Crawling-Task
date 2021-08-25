## Search-API-Crawling-Task

Write a Python function that will search the following platforms for musical artists by name:

1. [Bandsintown](https://www.bandsintown.com/)
2. [DICE.fm](https://dice.fm/)
3. [SoundCloud](https://soundcloud.com/)
4. [Twitch](https://www.twitch.tv)

The first two should be reasonably straightforward, the last two might be
rather challenging. Do not worry if you don't complete them all.

For each platform, your function should return, if applicable:

- A profile ID used to populate a URL, eg: "causticmf" from "https://www.twitch.tv/causticmf".
- A URL for the artist's profile on the platform.
- The name given to the artist's profile.
- A URL for a profile image or thumbnail.

The preferred approach is to use underlying JSON APIs, rather than parsing HTML,
but a less elegant solution is better than no solution at all. You might refer
to the network traffic tabs for
[Firefox](https://developer.mozilla.org/en-US/docs/Tools/Network_Monitor) and
[Chrome](https://developer.chrome.com/docs/devtools/network/) for inspiration.
Use any Python libraries, including [Scrapy](https://scrapy.org/),
[Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) and
[Requests](https://docs.python-requests.org/en/master/) as you see fit.

You might think about:
- How easy it will be to add additional platforms to your function.
- How easily API changes could be accomodated.
- How efficient your function is.
