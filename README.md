# UML-Use-Case-Diagram-Drawer

## Description

This project is a web-based tool for creating UML Use Case diagrams. It allows users to draw actors, use cases, system boundaries, and relationships using a graphical interface. The diagrams can be saved and loaded from local storage.

## Features

*   **Interactive Canvas:** Draw UML Use Case diagrams directly in the browser using Fabric.js.
*   **Add Elements:** Easily add actors, use cases, system boundaries, and relationships using buttons in the control panel.
*   **Customizable Elements:** Add new use cases and new actors directly on the canvas.
*   **Relationships:** Draw association, include, extend, and generalization relationships between actors and use cases.
*   **Local Storage:** Save and load diagrams directly from your browser's local storage.
*   **Responsive Design:** The application adapts to different screen sizes, providing a usable interface on various devices.
*   **Theme Toggle:** Switch between light and dark themes.
*   **Clear and Clean UI:** The application provides a simple UI for all its features.
* **Multi Tool Navigation:** Navigate from one drawing tool to other from the navigation bar.

## Technologies Used

*   **HTML:** For the structure of the web page.
*   **CSS:** For styling and layout.
*   **JavaScript:** For the interactive drawing and database logic.
*   **Fabric.js:** For the interactive canvas and drawing.
*   **sql.js:** For the in-browser SQLite database.
*   **Font Awesome:** For the icons used.

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/fmmido/UML-Use-case-Diagram-Drawer.git
    ```

2.  **Open the `index.html` file** in your web browser.
    *  You can also open the html files in `/uml_class.html`, `/class_diagram_tool.html` for Class Diagram Tool and `/uml_use_case.html` for use case diagram tutorial.

## Usage

1.  **Navbar:** Use the Navbar at the top to navigate through the website, and to select theme.
2.  **Control Panel:** The control panel at the top will help you add different shapes to your UML diagram.
3.  **Canvas:** The white space is your canvas where you can interact and create your diagram.
4.  **Adding elements:** Click the different buttons to add different shapes onto the canvas.
5.   **Adding new Use cases:** Add a new use case name, by clicking the "new use case" button, and writing its name in the text area and clicking "Add".
6.  **Relationships:** Select two objects and draw relationship between them.
7.  **Moving objects:** Click the objects, and drag them to move them.
8.  **Saving and Loading:** Save the diagrams using the save button, and use the load button to see them in a list to select.

## Project Structure

*   `index.html`: The main HTML file of the application.
*   `style.css`: Contains all the CSS styles for the application.
*   `script.js`: The JavaScript file with the application logic.
*   `class_diagram_tool.html`: The HTML file for the class diagram drawer tool
*    `uml_use_case.html`: The HTML file for uml use case diagram tutorial.
*   `uml_class.html`: The HTML file for the uml class diagram tutorial.
*   `src/`: Contains all project images.

## How to Contribute

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature`).
3.  Commit your changes (`git commit -am 'Add some feature'`).
4.  Push to the branch (`git push origin feature/your-feature`).
5.  Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
