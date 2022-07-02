# Hey, Yo!

An action that says "Hey, Yo!".

Here is a sample of workflow file.

```yml
name: yo
on: [pull_request]
jobs:
  yo:
    name: runner / yo
    runs-on: ubuntu-latest
    steps:
      - uses: okuzawats/hey-yo-action@v0.3
```
