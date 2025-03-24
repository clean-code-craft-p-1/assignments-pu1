# Modularity recap

[Separation of production, test, and example documentation](https://github.com/clean-code-craft-p-1/well-named-in-cpp-art-pogorelov/pull/1/files)

[Separating the definition of the colors ('map') from the conversion ('coding')](https://github.com/clean-code-craft-p-1/well-named-in-cs-pranshuphilips/tree/master/TelCo.ColorCoder/Color)

[Fine-grained separation](https://github.com/clean-code-craft-p-1/well-named-in-js-priyansudash-03/tree/main/app)

[Separation of formatting from printing](https://github.com/clean-code-craft-p-1/well-named-in-py-rishabhpandey04/blob/main/color_formatter.py)

## Static analysis

Static = analyze the code without running it.

Look at the results of the 'lint' job in your repository.

## Take away

- Separation of test code means we avoid delivering test code to production. "Don't launch the tester with the satellite".
- Separate pieces of code with different rates of change. Then you don't need to re-test unchanged parts of the code.
- Separate new code from legacy, when you want to set a higher bar for yourself. For reliability and speed of development.

