# Recap of statistics

Use of [built-in std functions](https://github.com/clean-code-craft-p-1/spring-in-cpp-art-pogorelov/blob/fc5a656ed2a90d4b160f491865e40222a817a7eb/stats.cpp) for statistics

Mistake-proofing [with spans and non-discardable return values](https://github.com/clean-code-craft-p-1/spring-in-cpp-art-pogorelov/blob/fc5a656ed2a90d4b160f491865e40222a817a7eb/stats.h#L15)


[Discussion](https://github.com/clean-code-craft-p-1/spring-in-cpp-art-pogorelov/blob/fc5a656ed2a90d4b160f491865e40222a817a7eb/stats-test.cpp#L16C5-L16C21): Is `EXPECT_DOUBLE_EQ` too accurate for us? What information do we need to answer that question?

Use of [JavaScript `reduce` for statistics](https://github.com/clean-code-craft-p-1/spring-in-js-priyansudash-03/blob/92fdd9e3d0fc8bba70e1f12363d71266938c479a/statistics.mjs#L13)

Use of python [built-in functions](https://github.com/clean-code-craft-p-1/spring-in-py-rishabhpandey04/blob/253355f10d00d240b09f519d13e7f8c5089f2bb4/src/stats_calculator.py)

## Take-aways

- Use built-in functions when possible - reduces the amount of code to read and prove
- Use language features and unit-tests for mistake-proofing (dis-ambiguation)
- Always ask: If I were to do it for the same use, _what_ would I do?
