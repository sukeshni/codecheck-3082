# Create GitHub Account

## Step 1: Join [GitHub](https://github.com)!
If you already have your GitHub account, skip this step.  

If you don't have a GitHub account, access [GitHub](https://github.com/join) and create an account.

## Step 2: Edit [account.json](./account.json).
Open [account.json](./account.json) and edit the value for key `github_username`.

```json
{
  "github_username": "<Write your GitHub username here>"
}
```

## Step 3: Test it!
Tests which you need to pass are specified in [specifications](./specifications) directory. Each files that ends with `.spec.js` contains test to run.

### Challenge by GitHub Fork
To run the test you will need to install modules and execute. Run commands below in your terminal.

```bash
$ npm install                      # Install modules
$ $(npm bin)/mocha specifications  # Run test
```

Output for success will be like below.

```
Verify GitHub Account
  ✓ should get right user (863ms)


1 passing (871ms)
```

### Challenge from Web Editor
Press the button `RUN`, and it will run the test.

When you pass this test, you will see result output like below.

```
1..1
ok 1 Verify GitHub Account should get right user
# tests 1
# pass 1
# fail 0
```
