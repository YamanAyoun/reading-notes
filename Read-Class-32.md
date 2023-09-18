# View components
View components in web development are a way to render reusable and self-contained chunks of UI logic and content within a web application. 
They provide a separation of concerns, reusability, and testability similar to the relationship between controllers and views. 

## Summary of view components:

* Purpose: View components are used to render specific parts of a web page, rather than the entire page. They are ideal for rendering dynamic and reusable content.

* Model Binding: Unlike controllers, view components do not use model binding to receive data. Instead, they rely on data passed to them when they are invoked.

## Use Cases:

- Dynamic Navigation Menus.

- Tag Clouds.

- Sign-In Panels.

- Shopping Carts.

- Recently Published Articles.

- Sidebar Content.

- Adaptive Sign-In Panels.

## Create a view component class in several ways:

- Deriving from the ViewComponent base class.
- Decorating a class with the [ViewComponent] attribute.
- Naming a class with a suffix "ViewComponent."
