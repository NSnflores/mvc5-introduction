# Creating our Entity Framework model

This class will be our model, EF will create a table, based on this model.

**Add a new class, Cerveza.cs**

1. On the Models folder, rigth click *Add > Class...*
![alt text][add]

[add]:https://github.com/yeseniamolinab/mvc5-introduction/blob/master/add-class.png

2. Add the following properties to the newly created Cerveza class

![alt text][logo]

[logo]:https://github.com/yeseniamolinab/mvc5-introduction/blob/master/cerveza-class.png

3. Save de changes (press Ctrl+S)


**Adding data annotations**

1. Make the field *Nombre* required and indicate a max length of 50 by adding the followings attributes:
```csharp
  [Required]
  [MaxLength]
  public string Nombre { get; set; }

```
2. Indicate that the *Calificacion* field be on a range between 1 and 5:
```csharp
  [Range(1,5,ErrorMessage = "La calificacion debe tener un valor minimo de 1 y un maximo de 5")]
  public string Calificacion { get; set; }

```
3. Save de changes (press Ctrl+S)
