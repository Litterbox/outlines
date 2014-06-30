# More DOM Events


| Objectives |
| :-----    |
| Describe DOM LEVEL II and form submisssion concerns by developing events handlers for them |
| Develop methods for adding elements to the DOM by creating an append event |
| Apply event handlers to detect event bubling from inside elements by creating a delegate function |

## Goal

By the end of the day students should build a naive implementation of common DOM event handlers and manipulation.

## Morning
### Form Events and More DOM Manipulation

* Form Events
  * onSubmit
    * using `this`
  * onFocus
* Node Creation
  * createElement
    * innerHTML
  * appendChild
  * createTextNode

## Afternoon
### DOM LEVEL II
 
* Event Bubbling
  * event.target and currentTarget
  * addEventListener
    * Adding many events?
  * create a delegate
    * write a `withinElement` function to find matching elements along the path of the bubbling event
* Event Capturing?


## LAB

### Goal 
* Utilize new methods built in class
  * `append`
  * `delegate`

## Review Lab

Use `append` and `delegate` to practice event delegation and DOM manipulation via a series of small exercises.

## LAB

Create a TODO-style application.

* use form to submit new data
* collect that data and append it to a container.
  * Watch each element in the container for specific events
    * `remove`
    * `finished`


