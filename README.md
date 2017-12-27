# Angular2

Angular is component based. 
A component is a class with a view template and a decorator. A component consists of three main things Template, Class and Decorator.

The view template defines the user interface. The template contains the HTML, directives and data bindings.

The class contains the code required for the view template. A class in Angular contains properties and methods. Properties contain the data for the view template and methods contain the logic for the view.
Typescript is used to implement classes in Angular. 

The decorator component is provided by Angular which adds metadata to the class. Once we decorate a component class with a decorator it becomes an Angular component.

The AppModule is the root module that bootstraps and launches the application. The components must be imported and declared here.
The component must be imported and declared in the module in order to be registered. The selector can then be used as a directive in a view template.

Styles and stylesheets in Angular.<br/>
How do we implement styles for components in Angular?<br/>
Styles can be specified using the external style sheet referenced by index.html called styles.css<br/>
The second option is to use a <style> tag in the view template of the component.<br/>
The third option is to use the @Component decorator styles or stylesUrls property of the component.<br/>
With the styles attribute you specify an array of styles.<br/>
The stylesUrls property which uses an array of urls, allows us to reference an external style sheets for the component view template.<br/>
<p>
Interpolation vs. Property Binding<br/>
 src={{imagePath}} /> <-- interpolation<br/> 
 [src] = ‘imagePath’ /> <-- property binding double/single quotes<br/>




