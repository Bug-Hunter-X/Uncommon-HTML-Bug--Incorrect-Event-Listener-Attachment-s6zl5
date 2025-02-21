# Uncommon HTML Bug: Incorrect Event Listener Attachment

This repository demonstrates a subtle bug in HTML related to attaching event listeners.  The bug showcases an unconventional and less robust way of handling event listeners, potentially leading to unexpected behavior or difficulties in maintaining the code. The solution provides a more standard and reliable approach using the `addEventListener` method.

## Bug Description

The bug involves directly assigning a function to the `onclick` property of an HTML element instead of using the standard `addEventListener` method.  While it might seem to work initially, this can lead to problems when trying to add multiple event listeners to the same element or when dealing with event bubbling and capturing.

## Solution

The solution demonstrates the proper use of `addEventListener` to attach event listeners.  This method provides greater control and flexibility when handling events, allowing for multiple listeners, event delegation and the specification of event capturing or bubbling phases.