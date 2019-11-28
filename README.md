# TDD utilities

## tdd

```
    ./tdd "commit message"
```

Please modify this script to use your testing tool.

If the test pass, it executes `git add . && git commit -m message`

## tcr

```
    ./tcr "commit message"
```

Please modify this script to use your testing tool.

If the test pass, it executes `git add . && git commit -m message`
If the test fail, it executes `git reset --hard`

## Use your own testing framework
This scripts are configured for some languages, but you can modify them easily.

Just edit the file and change the `test_code` function, like this:

```
test_code() {
    npm test
}
```
