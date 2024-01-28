# gitworkflow
rebase-test

This is a simple tests to check for candidates if they are familiar with typical git workflows, esp. rebasing and rewriting existing histories during the development of a new feature.

Eventually you notice that this didn't make sense, so you change your mind and remove it from history.
Eventually you add a new idea. But you add some typos, which of course you'd never do, so it never happened.

Finally, you would end up with your final result - and your commit history should not look too bloated with all back and forward, but provide a proper and concise step-by-step development.
In this case, I'd expect that you would have a history with not 10 commits, but only 6:

* The initial commit
* Adding a relevant idea
* Adding a relevant feature with all essential notes
* Adding another relevant feature
* Adding not so relevant notes
* This final sentence about the exercise and its expectations

Please add a pull request with a rewritten and streamlined history - and a description, which commands you used for that (instead of writing everything from scratch).
