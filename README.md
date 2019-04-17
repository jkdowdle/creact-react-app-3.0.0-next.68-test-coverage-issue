## Steps to Reproduce
```
git clone https://github.com/jkdowdle/creact-react-app-3.0.0-next.68-test-coverage-issue.git
cd creact-react-app-3.0.0-next.68-test-coverage-issue
yarn
yarn test --coverage
```
or

`npx create-react-app@next --scripts-version=3.0.0-next.68 app-name && cd $_ && yarn test --coverage`

## Error
```
No tests found related to files changed since last commit.
Press `a` to run all tests, or run Jest with `--watchAll`.
----------|----------|----------|----------|----------|-------------------|
File | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s |
----------|----------|----------|----------|----------|-------------------|
All files | 0 | 0 | 0 | 0 | |
----------|----------|----------|----------|----------|-------------------|

Watch Usage
› Press a to run all tests.
› Press f to run only failed tests.
› Press q to quit watch mode.
› Press p to filter by a filename regex pattern.
› Press t to filter by a test name regex pattern.
› Press Enter to trigger a test run.
```
## Expected

Expected it to run the tests with a coverage report and not enter watch mode.
