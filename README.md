# Python Actions Unittest

This is a simple GitHub repository that shows how you can use GitHub Actions to run unittests on Python code.

To see the failing test results, visit the [results of this job]( https://github.com/tblanarik/actions-ci-unittest/actions/runs/3380402115/jobs/5613143309).

You'll notice that the test failed and the reason given is:

```python
AssertionError: 4 != 5
```

![CleanShot 2022-11-02 at 12 09 50](https://user-images.githubusercontent.com/1554630/199580169-3d155f87-6492-4f70-afd1-3147f10384c7.png)

# Fix the failing test

You can easily fix the failing test with this [Pull Request- "Fix Failing Unittest"](https://github.com/tblanarik/actions-ci-unittest/pull/1)

And sure enough, the tests pass and the GitHub Actions workflow shows ✔️ : https://github.com/tblanarik/actions-ci-unittest/actions/runs/3380427284/jobs/5613197169

![CleanShot 2022-11-02 at 12 14 40](https://user-images.githubusercontent.com/1554630/199580889-96618524-3b56-439e-80c6-9c084982dc75.png)

As well as when looking at the Pull Request itself:

![CleanShot 2022-11-02 at 12 14 52](https://user-images.githubusercontent.com/1554630/199580966-4a3dd6f3-c969-49c3-8615-11424487dd87.png)
