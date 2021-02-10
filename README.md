# DRPG Coding Test

This is the Laravel coding test to access your skills and thought process when coming to build features
in an application.

You will be on call with one of our engineers to pair program a solution to the task below. Here you can
ask questions about the task as well as any other expectations from us.

In the call you will have 5 minutes to read through the below and ask any initial questions before having
30 minutes to complete the task. After that there will be 10 minutes of discussion to talk through your
implementation and provide any feedback.

## Our Expectation

Using the project provided we want to integrate with a 3rd party API to pull in user data.

We want this to be maintainable and flexible to potentially add other API calls to the future.
This code might also be used in other parts of the application to get a fresh set of the data from the API.

There's a few pointers we would suggest to think about when coming up with your solutions:

- How we would be able to test this using PHPUnit in the future if we needed to?
- Don't always write everything yourself you can pull in other packages if you feel they are needed.

We don't want to worry about any sort of error handling of the API, so assume that the API will always
exist and we always return you the expected data.

## Task

Build a command that pulls data from an API and stores it against the User model.

- Call the [https://reqres.in/] API to pull in the first page of users only.

We could potentially use this command in a schedule to repeatedly update the users from the API.
