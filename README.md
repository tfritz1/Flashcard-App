<h1> Flashcard App </h1>

<h2> Purpose </h2>

The purpose of this project was to build an app to create, edit, and study flashcards. 

The project was completed with the following skills: 

* Working with rendering and state management in React.

* Creating routes, including nested routes, using React Router.

* Using hooks like useState(), useParams(), and useHistory().

<h3> Project Requirements </h3>

* All the props are treated as read-only.

* State is never directly mutated; it's only updated via setState().

* The Edit Card and Create Card screens share the same form component.

* The useEffect() hooks have the appropriate dependencies listed in the dependency array.

* State is "lifted up" to the parent component where appropriate.

* All inputs are controlled. Generally, there is a warning on the console when you type into the input box and it changes from uncontrolled to controlled. The warning looks like this: "Warning: Input is changing an uncontrolled input of type <text|number|etc.> to be controlled." This is often the result of initializing the state to null or undefined.
