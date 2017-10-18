# Movement


## void Start ()
  Entry point for all Unity objects


## void Update()
  Called once a frame.


## void FixedUpdate ()
  Every fixed frame, used for physics updates.


## public void LoadNext()
  Load the HighScore scene.


## public void NewGame()
  Reset the variables, and load the original scene.


## public void MainMenu()
  Load the Intro Scene


## void Reset()
  Sets the game score back to 0.


## void OnCollisionEnter2D(Collision2D other)
  Checks collisions with enemies, and objects

Parameter | Description 
 --------|--------
other | The object that was run into.

## void OnTriggerEnter2D(Collider2D other) 
 > Checks what tag the object has, adds score, and deletes the object.

```csharp
  if(other.gameObject.tag == "Interactable"){      GameManager.Instance.BonusScore(10);      GameManager.Instance.Collected = true;      Destroy(other.gameObject);  }
```


  Adds to the score, when overlapping with an Interactable

Parameter | Description 
 --------|--------
other | The interactable being overlapped