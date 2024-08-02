# Basic Configuration

## Part A

Given the following JSON snippet (taken from W3C examples), write the .pkl file that produces this JSON:

```json
{
  "name": "Common wood pigeon",
  "lifespan": 8,
  "friends": {
    "bird1": "Parrot",
    "bird2": "Albatross",
    "bird3": "Falcon"
  }
}
```

`pkl eval -f json part_a.pkl`

## Part B

For some reason, we decide we no longer need the birdX names of the different birds; we just need them as an array. Change your solution to the previous question to produce the following JSON result:

```json
{
  "name": "Common wood pigeon",
  "lifespan": 8,
  "birds": ["Parrot", "Barn owl", "Falcon"]
}
```

`pkl eval -f json part_b.pkl`
