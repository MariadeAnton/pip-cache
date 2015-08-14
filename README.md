# pip-cache
A trial using Travis CI cache for pip 

- let's trigger a new build and see if it was sucesfully cached

Results: https://travis-ci.org/MariadeAnton/pip-cache/builds 
- #1 build caches - $HOME/.cache/pip directory - 5 min 12 sec
- #2 build using that cache - 1 min 12 sec
