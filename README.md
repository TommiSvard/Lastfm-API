# Latfm-API
Retrieving data from my last-fm account, had an idea to include it on my personal website but ended up scrapping that because it slowed down my flask-server to much. I never figured out why but i suspect that it was initialized so that the server had to wait for the request to last.fm to complete before doing anything else (highjacking the mainthread), that included getting the index page. . 

It was created using the library pylast, very easy to use and combined with last.fm's own documentation it was really smooth to implement diffrent ideas. The library is still maintained and i'll link to it below.


https://github.com/pylast/pylast

And if you aren't familiar with the music service last.fm;

https://last.fm

And the documentation on the api

https://www.last.fm/api

