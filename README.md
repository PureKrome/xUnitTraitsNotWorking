

### A .NET Core 2.0 app + Xunit Traits don't seem to work with Resharper

The following repo is a sample app that highlights that Traits aren't working with Resharper.

I [first asked this question on StackOverflow](https://stackoverflow.com/questions/46470026/xunit-traits-are-not-being-skipped-in-resharper-in-my-net-core-app-2-0).

- JetBrains ReSharper Ultimate 2017.2 Build 109.0.20170824.131346
- xunit.core 2.2.0
- xunit.runner.visualstudio 2.2.0
- Tests project: netcoreapp2.0


What did I do?

- I added some traits to the sample classes
- The runner fails to read them all and only lists them all as `Uncategorized`.

Proof:

![](https://i.imgur.com/y0nnulm.png)

-end of readme-