1. `git checkout 5ef0fa5` to get to the first commit
1. `npm it`
1. Observe a "patching fs" log for jest itself, and one per test afterwards
1. `git checkout master` to get back to the tip
1. `npm it`
1. Observing only the first "patching fs" log message, while none from the tests
