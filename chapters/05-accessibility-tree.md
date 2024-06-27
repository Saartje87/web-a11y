# Accessibility Tree

## What is the Accessibility Tree?

The Accessibility Tree is a hierarchical representation of the accessible objects in a web page. It is used by assistive technologies, such as screen readers, to provide information about the structure and content of a web page to users with disabilities.

The Accessibility Tree is similar to the DOM (Document Object Model) in that it represents the structure of the web page, but it includes additional information that is needed to make the page accessible to users with disabilities.

## How is the Accessibility Tree Created?

The Accessibility Tree is created by the browser when a web page is loaded. The browser uses the DOM to create the initial structure of the page, and then it generates the Accessibility Tree by analyzing the DOM and adding accessibility information to it.

The Accessibility Tree includes information about the role, state, and properties of each accessible object on the page. This information is used by assistive technologies to provide users with disabilities with a more meaningful and usable experience.

## Why is the Accessibility Tree Important?

The Accessibility Tree is important because it provides a way for assistive technologies to access and interact with the content of a web page. Without the Accessibility Tree, users with disabilities would not be able to navigate, interact with, or understand the content of the page.

By ensuring that the Accessibility Tree is properly created and maintained, web developers can help ensure that their content is accessible to users with disabilities. This can help make the web a more inclusive and usable place for everyone.

## Parts

"role, name, description, state, properties, relationships, "

The Accessibility Tree is made up of several parts, including:

- **Accessible Objects**: These are the elements on the page that are accessible to users with disabilities. Each accessible object has a role, state, and properties that describe its purpose and behavior.
- **Relations**: These are the relationships between accessible objects on the page. For example, a button may be related to a form field that it controls.
- **States and Properties**: These are the attributes of an accessible object that describe its current state and behavior. For example, a button may have a "pressed" state that indicates whether it is currently pressed.
- **Actions**: These are the interactions that users can perform on accessible objects. For example, a button may have a "click" action that is triggered when the user clicks on it.

role:

- from html semantics (implicit role)
- from ARIA attributes (explicit role)

## Demo in Chrome and explain the Accessibility Tree by example
