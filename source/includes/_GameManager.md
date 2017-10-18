# GameManager


## void Start () 
  Entry point for all Unity objects


## void Update ()  
 > Keep attempting to update the Speed / Difficulty

```csharp
 if(UpdateSpeed()) { 	gameSpeed += 0.75f; 	speedIncr++; }
```


  Called once a frame


## bool UpdateSpeed() 
  Updates the speed of the character based off of their score.

**Returns**  Boolean depciting

## public int GetScore()
  Removes the decimal from the value

**Returns** 
###
  Adds to the currentScore on collecting of coins / powerups

Parameter | Description 
 --------|--------
bonus | > The value added to the score. 