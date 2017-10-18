# Spawner


## void Start()
  Entry point of all Unity's objects


## void Update() 
 > Spawn all items at the same time.

```csharp
  SpawnEnemies(x);  SpawnFlyers(x);  SpawnCoins(x);
```


  Runs once a frame.


## void SpawnFlyers(float x)
  Spawns flying Mob

Parameter | Description 
 --------|--------
x |  The X coordinate of their spawn location. 

## void SpawnEnemies(float x)
  Spawns regular Obstacles and Enemies

Parameter | Description 
 --------|--------
x |  The X coordinate of their spawn location. 

## void SpawnCoins(float x)
  Spawns coins, and interactables.

Parameter | Description 
 --------|--------
x |  The X coordinate of their spawn location. 

## void ChangeTheme()
  Changes the Theme
