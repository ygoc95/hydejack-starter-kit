---
layout: post
title: Weather App with Vue,Axios,Vuex,Bulma and OpenWeatherAPI
permalink: /projects/
sitemap: false
---
Hava-nasil is a simple Vue app to display current weather details and the forecast of next week. The layout is a single responsive page done with Bulma.

The requests to OpenWeatherAPI is done by Axios.

What I have learned:

    - Debounce usage for waiting user inputs
    - Basic Vuex state management for sharing data between components
    - Following the upper step, Eventbus pattern was not useful for me which led me to look into Vuex.
    - Bulma can be a good alternative for Bootstrap.
    - Axios errors should always be handled in 'catch()' blocks (Rookie mistake for me to think otherwise).

Demo (It is currently in Turkish): [here](https://ygoc95.github.io/hava-nasil/)

Check out the Github repo: [here](https://github.com/ygoc95/hava-nasil)
