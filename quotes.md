Quotes
-------

1. https://www.reddit.com/r/IAmA/comments/tyfshm/comment/i3s03n0/?utm_source=share&utm_medium=web2x&context=3

> Can you explain what true TDD is, especially with frameworks like mockito. I am always seeing unit tests are geared directly to the implementation due to mocking, it is clear the implementation came first and is not TDD. How does one practice real TDD and still have a useful unit test that can also pass mutation testing?


> Thank you for the question. I have faced similar issues in the past and I have to admit I had similar experiences when I started to do TDD. Over the time I have leaned to focus on behavior rather than state when writing tests. I often remind myself that the more stubs and mocks we use is a sign of poor design. With practice we can learn to design our code in such a way that we keep the dependency on the internal details to a minimum. With unit testing we can't totally avoid some knowledge of the internals, however, we can drive those internals based on the design influence of the tests rather than throw something together and write a test around it. I also try to know out a dependency before I consider mocking out a dependency. This helps, by moving dependencies around, where it is not possible to eliminate, we can reduce the extent to which we stub or mock.
