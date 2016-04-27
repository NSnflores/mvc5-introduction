# Adding the controller with its views using scaffolding feature

Visual Studio has a very cool feature, that allows you to automagically do all the needed work for a CRUD operation, let's see that in action!

**Add a new controller**

1.Rigth click on *Controllers > Add > Controller*

![alt text][add]

[add]: https://github.com/yeseniamolinab/mvc5-introduction/blob/master/add-controller.png


2.Select *MVC 5 Controller with views, usign Entity Framework*

![alt text][pick]

[pick]: https://github.com/yeseniamolinab/mvc5-introduction/blob/master/pick-controller.png


3.For the Model class, select *Cerveza(WorkshopMVC.Models)*, in the Data context class option click on the "+" button on the rigth to add a new one,
you can leave the default name or write your own; leave everything else with the default values.

![alt text][form]

[form]: https://github.com/yeseniamolinab/mvc5-introduction/blob/master/scaffolding-form.png


#Wait a second! I don't see Cerveza(WorkshopMVC.Models) in the options for the Model class!

If this happens to you, it means that once you created the Cerveza model, you forgot to build the solution, you just have to press ctrl+shift+b and repeat the steps.

[Back] (https://github.com/yeseniamolinab/mvc5-introduction/blob/master/README.md)
