search_dash
===========

Older versions of Dash (<1.8.2) apparently don't support Alfred 2 the way that it's used in [Will Farrel's Dash Workflow](https://github.com/willfarrell/alfred-dash-workflow). This is a workflow that should work, at least for Dash v1.8.1.

This is a simple Dash workflow for searching Dash according to a specific docset. This is built for Dash v1.8.1 when the Alfred 2 workflows didn't work so hot, and is meant to mimic the functionality of Dash by Will Farrell.

This allows you to search a specific docset, by using a specific keyword. So far this supports:
* HTML
* CSS
* Javascript
* jQuery
* jQuery UI
* Bootstrap
* WordPress
* Underscore.js

To update this for yourself, create a new Keyword input that takes the keyword you'd like to use and a query. Then connect that to an "Open URL" action that goes to `dash://DOCSET:{query}` where DOCSET is replaced by the docset search keyword listed by Dash.

Using HTML as an example: `dash://html:{query}`
