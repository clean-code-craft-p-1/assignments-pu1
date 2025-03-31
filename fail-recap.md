# Strong tests - recap

[Easy stubs with duck-typed languages](https://github.com/clean-code-craft-p-1/test-failer-in-js-priyansudash-03/blob/3ac2b726baeeef86a5431fc907c7f3db2ebfd5fa/weatherreport.mjs)

[Separating the forming of the color pairs from their printing](https://github.com/clean-code-craft-p-1/test-failer-in-java-rishabhpandey04/blob/42612cf51ce656ed2d5fc9f82ce776f55d3a1840/misaligned/misaligned.java)

[Separation of production-library and test-code](https://github.com/clean-code-craft-p-1/test-failer-in-cpp-art-pogorelov/pull/1)

Misaligned: [Tests for alignment can get complex](https://github.com/clean-code-craft-p-1/test-failer-in-cpp-art-pogorelov/blob/13e87fe8de05f5e44167a789ab349a16aeaf092a/lib/test/src/ColorCodesTest.cpp#L27).

## Complex tests = consider single-responsibility

Tests can get complex when the code combines functionalities. E.g., computation and formatting. What are the ways we can simplify the code?

- Separate the computation from the formatting. E.g., the number can be tested separately from the separators, etc.
- Use industry-standard formats for rendering the table: E.g., comma-separated (csv)
- Use single-responsibility while evaluating third-party libraries: "is there one level of abstraction"?

## Property based tests for the weather

Express properties. Form relationships between the input and output.

What are the properties of the weather?
- High precipitation = predict rain
- Rain with high wind = storm

## Take away

When tests get complex:
- simplify the code
- Or use off-the-shelf functionality
- Or negotiate based on the user-story

Use property-based tests to expect specific outputs for a bunch of inputs.
Capture the "property" that a user would expect. Use representative input-output examples to test.
