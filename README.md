# Is the Ukraine goverment still up?

Using Elixir Livebook to monitor if Ukranian government websites are still up and running.

Source urls & idea: https://github.com/edsu/gov-ua

Wikipedia query: https://query.wikidata.org/#SELECT%20DISTINCT%20%3Furl%20WHERE%20%7B%0A%20%20%3Fitem%20wdt%3AP856%20%3Furl%20.%0A%20%20FILTER%28CONTAINS%28LCASE%28STR%28%3Furl%29%29%2C%20%27.gov.ua%27%29%29%0A%7D
