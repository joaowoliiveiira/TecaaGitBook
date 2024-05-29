---
description: >-
  This page is dedicated to illustrating both positive and negative examples of
  the Excess Structural Information Smell.
---

# Positive and Negative Examples

Positive example of a "Excess Structural Information", or, in other words, the expected structural information:

```
{
  "count": 123,
  "next": "http://api.example.org/accounts/?offset=400&limit=100",
  "previous": "http://api.example.org/accounts/?offset=200&limit=100",
  "results": [
    {
      "name": "string",
      "url": "https://example.com/"
    }
  ]
}
```

By turning this into a bad example, or in other words, turning this into a "Excess Structural Information" documentation smell, we would have the following:

```
{
  "count": 1036,
  "next": "https://pokeapi.co/api/v2/location?offset=20&limit=20",
  "previous": null,
  "results": [
    {
      "name": "canalave-city",
      "url": "https://pokeapi.co/api/v2/location/1/"
    },
    {
      "name": "eterna-city",
      "url": "https://pokeapi.co/api/v2/location/2/"
    },
    {
      "name": "pastoria-city",
      "url": "https://pokeapi.co/api/v2/location/3/"
    },
    {
      "name": "sunyshore-city",
      "url": "https://pokeapi.co/api/v2/location/4/"
    },
    {
      "name": "sinnoh-pokemon-league",
      "url": "https://pokeapi.co/api/v2/location/5/"
    },
    {
      "name": "oreburgh-mine",
      "url": "https://pokeapi.co/api/v2/location/6/"
    },
    {
      "name": "valley-windworks",
      "url": "https://pokeapi.co/api/v2/location/7/"
    },
    {
      "name": "eterna-forest",
      "url": "https://pokeapi.co/api/v2/location/8/"
    },
    {
      "name": "fuego-ironworks",
      "url": "https://pokeapi.co/api/v2/location/9/"
    },
    {
      "name": "mt-coronet",
      "url": "https://pokeapi.co/api/v2/location/10/"
    },
    {
      "name": "great-marsh",
      "url": "https://pokeapi.co/api/v2/location/11/"
    },
    {
      "name": "solaceon-ruins",
      "url": "https://pokeapi.co/api/v2/location/12/"
    },
    {
      "name": "sinnoh-victory-road",
      "url": "https://pokeapi.co/api/v2/location/13/"
    },
    {
      "name": "ravaged-path",
      "url": "https://pokeapi.co/api/v2/location/14/"
    },
    {
      "name": "oreburgh-gate",
      "url": "https://pokeapi.co/api/v2/location/15/"
    },
    {
      "name": "stark-mountain",
      "url": "https://pokeapi.co/api/v2/location/16/"
    },
    {
      "name": "spring-path",
      "url": "https://pokeapi.co/api/v2/location/17/"
    },
    {
      "name": "turnback-cave",
      "url": "https://pokeapi.co/api/v2/location/18/"
    },
    {
      "name": "snowpoint-temple",
      "url": "https://pokeapi.co/api/v2/location/19/"
    },
    {
      "name": "wayward-cave",
      "url": "https://pokeapi.co/api/v2/location/20/"
    }
  ]
}
```
