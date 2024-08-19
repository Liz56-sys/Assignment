This is a simple JavaScript-based Task Manager that allows users to add tasks to a list. The project uses JavaScript to handle form submissions and dynamically update the DOM.

Features
Input Validation: The submit button is disabled by default and is only enabled when the input field has text.
Dynamic Task Addition: When a task is submitted, it is added to a list displayed on the page without reloading the page.
Automatic Reset: After submitting a task, the input field is cleared, and the submit button is disabled again until new input is detected.

How It Works
DOMContentLoaded Event:

The script waits for the DOM to fully load before executing to ensure all elements are accessible.
Query DOM Elements:

The submit button and task input field are selected once at the start of the script for efficient use.
Input Field Monitoring:

An event listener is attached to the input field to monitor changes. The submit button is enabled only when the input field is not empty.
Form Submission:

The default form submission is prevented, and the new task is added to the list if the input is not empty.
The input field is cleared, and the submit button is disabled after a task is adde
