[![Build Status](https://travis-ci.org/MariadeAnton/pip-cache.svg)](https://travis-ci.org/MariadeAnton/pip-cache)

# pip-cache


More tests

- Let's create a new branch to PR branch/1.11
-----

A trial using Travis CI cache for pip 

- let's trigger a new build and see if it was sucesfully cached

Results: https://travis-ci.org/MariadeAnton/pip-cache/builds 
- #1 build caches - $HOME/.cache/pip directory - 5 min 12 sec
- #2 build using that cache - 1 min 12 sec
- #3 build caching more things - 1 min 27 sec
- #9 let's roll the 9th
