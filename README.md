# Student Directory (JavaFX)

Small JavaFX app to manage a list of students in a table. Coursework lab.

- Add a student (ID, name, major) from a form
- Delete the selected student
- Shows an alert when input is missing

## Tech stack

Java, JavaFX with an FXML view (`hello-view.fxml`) and a controller (`StudentController.java`).

## Files

| File | Purpose |
|---|---|
| `Main.java` | Application entry point |
| `StudentController.java` | Table setup, add/delete actions, validation alerts |
| `Student.java` | Student model |
| `hello-view.fxml` | Layout |

Data is kept in memory while the app runs. Source files belong to package `com.example.lab2`.
