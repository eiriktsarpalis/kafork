# Kafork

An thin, F# friendly wrapper for Confluent.Kafka, designed for compatibility with the Kafunk API. This is a work in progress.

## Using the wrapper

To incorporate the wrapper in your project place the following line in your paket.dependencies file:
```
github eiriktsarpalis/kafork:<commit hash> src/Kafork/Kafork.fs
```
and in paket.references:
```
File: Kafork.fs
```
Your project would need to additionally reference the following nuget dependencies:
```
Confluent.Kafka
```

## Running Tests

Make sure you set the `KAFORK_TEST_BROKER` environment variable to an appropriate kafka broker before running the tests.