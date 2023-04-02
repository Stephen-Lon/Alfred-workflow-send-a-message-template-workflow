# Alfred-workflow-send-a-message-template-workflow

This workflow is designed to send a message (using the `Messages` app) to a selected contact. I have called it a "template workflow" because *you* have to do some work in order to make *it* work.

The `List Filter` is populated with some names and numbers (and I apologise if your name is among them—but don't worry, it's not your number). Note the format of the `Arg` for the name. When you add a name that is the format you should follow: `name,number` (i.e., separarated only by a comma). All you need to do is to substitute details of your contacts for the names given in the `List Filter`. Simply follow the format used in the initial list.

# Usage 

The workflow will prompt you:

- to choose from your pre-populated list of contacts; and then
- for the text of a message to send via the Messages app.

It then sends the message and quits the app.
