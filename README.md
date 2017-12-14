# tasker-toggl
A port of the Toggl API for Tasker. Each API action is a separate task.

## Setup
There are two ways to use tasker-toggl. Most actions use an API token (saved in the `%TOGGL_TOKEN` [global variable](http://tasker.dinglisch.net/userguide/en/variables.html)) as an authentication method, but that can be swapped out for using email and password (set as `%TOGGL_EMAIL` and `%TOGGL_PW`). The example action using email/password authentication is [this one](https://github.com/HHErebus/tasker-toggl/blob/v8/single%20actions/me/me%20-%20email%20and%20password.tsk.xml).

## Usage
Each task is a simple port of the Toggl API ([documentation](https://github.com/toggl/toggl_api_docs/blob/master/toggl_api.md)): tasks that require an input have `Variable Set` actions that you can fill in, tasks that return data assign that data to some variable, and as a general they check for `200` return codes or flash the error message to the screen.

To import tasks, tap at the Tasks tab. After selecting "Import", goto the folder where you have downloaded the Tasker XML files, and select any of them. Keep in mind that tasks must have the `.tsk.xml` extentions to be considered as such by Tasker.

That's it! You can now use the tasks you imported as you please.

## Contributing
If you'd like to update an action or modify it sligthly, you can just [open an issue](https://github.com/HHErebus/tasker-toggl/issues/new) or submit a pull request. The only thing I ask is that you make it as friendly as possible for end-users.

Cheers!

Christian

[![forthebadge](http://forthebadge.com/images/badges/built-for-android.svg)](http://forthebadge.com)[![forthebadge](http://forthebadge.com/images/badges/makes-people-smile.svg)](http://forthebadge.com)[![forthebadge](http://forthebadge.com/images/badges/you-didnt-ask-for-this.svg)](http://forthebadge.com)