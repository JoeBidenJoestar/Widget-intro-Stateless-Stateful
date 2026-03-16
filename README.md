# Widget and Stateless-Stateful
![WidgetTree](https://github.com/user-attachments/assets/bee53d72-8324-413c-b35b-3c4b357b2ffa)


* **`MaterialApp`**: It configures the app's theme (`ThemeData`), navigation routing, and title.
* **`Scaffold`**: Implements the basic layout structure. It builds the structure for the `AppBar` and the main `body`.
* **`AppBar`**: The top navigation bar on the screen to display the page title with a custom background color.
* **`Column`**: Arranges its children in a vertical array and acts as the layout wrapper for the `Scaffold`'s body.
* **`Row`**: Arranges its children in a horizontal array. Used to align the category icons (Food, Scenery, People) and to position the counter text next to the add button.
* **`Container`**: Function as a 'box' (similar to a `<div>` in web development). It is used extensively for `padding`, `margin`, and background `color`.
* **`Center`**: A layout widget that centers its child.
* **`AspectRatio`**: A widget that controls the size of the child to a specific aspect ratio (`1.0` for a perfect square to wrap the image)
* **`Text`**: A text with a single style.
* **`Image.network`**: A widget that displays an image fetched from a given URL.
* **`Icon`**: Displays the default graphic icons from Material Design (Icons.food_bank, Icons.landscape, Icons.add).
* **`IconButton`**: A clickable icon that triggers a callback (`onPressed`) when tapped. Used to increment the counter.
* **`StatelessWidget`**: A widget that does not require mutable state, example `RowColumnPage`.
* **`StatefulWidget`**: A widget that has mutable state. Used by `CounterCard` so the UI can rebuild and update when the counter integer increases via `setState()`.


