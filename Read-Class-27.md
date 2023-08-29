# MVC Forms
## View Models
MVC Forms and View Models in the Model-View-Controller (MVC) architectural pattern play crucial roles in managing data presentation and user interaction.
The view, constructed as an HTML template with embedded Razor markup, generates webpages for the client.

Benefits of utilizing views include organized grouping by app feature, promoting loose coupling between app components, 
facilitating separate testing of user interface elements, and minimizing redundant UI sections.

## 4 Ways To Create Form In ASP.NET MVC
### Weakly Typed: 
The simplest and quickest method for form creation in MVC. Pros include easy form creation for one or two inputs. 
However, drawbacks encompass a higher likelihood of exceptions, especially for complex forms.

### Strongly Typed: 
Involves sending objects (models) rather than individual parameters, enhancing maintenance by leveraging auto-suggested inputs via IntelliSense. 
This approach is easier to manage than weakly typed, especially for larger forms.

### Strongly Typed AJAX (Asynchronous): 
Offers a clever way to submit data to the controller without reloading the entire page. Through asynchronous AJAX, 
data is posted to the controller, updating only the specific page section that requires output. 
The jQuery Unobtrusive AJAX package is commonly used for this.

### Pure HTML Forms with AJAX and jQuery: 
This method involves sending data from input controls and using HTML elements like <p> and <span> to transmit data to controllers.
This approach employs pure jQuery and AJAX techniques.
