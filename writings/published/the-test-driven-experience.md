When considering the type of developer experience that you want to have, you must consider three main things.

- Who you work with.
- What language/project you work on.
- How you perform testing.

I want to mainly focus on the third item - it has the most profound impact.

There are only two forms of testing, automatic and manual - period, that's it, only two - you either run tests via a testing framework or you run tests in the browser/console by hand. One is repeatable and the other is based on feature context.

In the case that you verify manually you are leaving the guarantee of functionality (present/future) in the hands of the people who know what the application should be able to do. Enter the QA team (or the developer) - who are charged with making sure that the application functionality is still available. They are the gate-keepers of the release.

In the case that your verification is automatic the guarantee of functionality and documentation lies within the tests and in turn the code. Others can make changes simplify, refactor, and extend knowing that if you break things a test will fail. You are the gate-keeper of the release.

The freedom this gives you as a developer is phenomenal. This is what you stand to gain.
