# Test

## Connects to the database and attempts to apply all adds,  updates and deletes

Parameter | Description 
 --------|--------
"data"|a dataset, passed by reference,  that contains all the  data for updating
"data"|a dataset, passed by reference,  that contains all the  data for updating
> This sample shows how to call the SaveData  method from a wireless device.

```csharp
 
AccidentCRUD accCRUD = new Adjuster.BusinessServices.AccidentCRUD();
accCRUD.SaveData(ref ds);

```

