# ASP.NET MVC Structure 

**By default, MVC projects include the following folders:**

**App_Data:**
Which is the physical store for data. This folder has the same role as it does in ASP.NET Web sites that use Web Forms pages.

**Content:** 
Which is the recommended location to add content files such as cascading style sheet files, images, and so on. In general, the Content folder is for static files.

**Controllers:** 
Which is the recommended location for controllers. The MVC framework requires the names of all controllers to end with "Controller", such as HomeController, LoginController, or ProductController.

**Models:** 
Which is provided for classes that represent the application model for your MVC Web application. This folder usually includes code that defines objects and that defines the logic for interaction with the data store. Typically, the actual model objects will be in separate class libraries. However, when you create a new application, you might put classes here and then move them into separate class libraries at a later point in the development cycle.

**Scripts:**
Which is the recommended location for script files that support the application. By default, this folder contains ASP.NET AJAX foundation files and the jQuery library.

**Views:**
Which is the recommended location for views. Views use ViewPage (.aspx), ViewUserControl (.ascx), and ViewMasterPage (.master) files, in addition to any other files that are related to rendering views. The Views folder contains a folder for each controller; the folder is named with the controller-name prefix. For example, if you have a controller named HomeController, the Views folder contains a folder named Home. By default, when the ASP.NET MVC framework loads a view, it looks for a ViewPage (.aspx) file that has the requested view name in the Views\controllerName folder. By default, there is also a folder named Shared in the Views folder, which does not correspond to any controller. The Shared folder is used for views that are shared across multiple controllers. For example, you can put the Web application's master page in the Shared folder.
