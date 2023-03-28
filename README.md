### Mastodon Toots
A simple app to gather public toots from a single account on a Mastodon server. The toots / retoots are lightly cleaned using Beautiful Soup and styled using Bootstrap. The app is intended as a base app, for implementation in a web framework. It was created with help from Bing Chat, and unknown contributors to Bing's training data.

### Requirements
- beautifulsoup4

### Instructions
- Add the server base_url and account_id you want to collect Toots from to mastodon.py.
- Optionally, change the 'limit' parameter in mastodon.py from the default of 5.
- Run 'Python3 mastodon.py'. Output will be printed to output.html.
