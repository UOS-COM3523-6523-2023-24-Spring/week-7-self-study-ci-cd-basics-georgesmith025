## Mocking
When the non-deterministic behaviour depends on external factors, 'mocks' can be used to simulate their functionality in a controlled manner.
This will isolate the desired behaviour for testing.

## Seed control
In this specific case which relies on random.random() function, you can use a 'seed' to ensure the sequence of numbers generated will be the same each time.
ie. np.random.seed(123)

## Property-based Testing
Instead of specifying inputs and corresponding outputs, you could define general properties that the function will satisfy.