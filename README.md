# Demo Integrating PHPStan With GitHub

## Description

This uses the [phpstan-sarif-formatter][1] to integrate [PHPStan][2] with [GitHub][3].
PHPStan is a statical analyzer for PHP, which provides you a list of issues in your code.
The phpstan-sarif-formatter project allows writing out that list in [SARIF][4] format.
SARIF is a standardized format for representation of such code issues.
Overall, this integrates PHPStan as a third-party tool into GitHub's [CodeQL][5] facilities.
GitLab uses the found issues to present them to reviewers in pull requests.

## Pull Requests

There is a [permanently open pull request](https://github.com/UlrichEckhardt/phpstan-sarif-formatter-demo/pull/1),
which adds some flawed code. You can look at that merge request to see how GitHub
displays the found flaws in its web frontend.

[1]: https://github.com/jbelien/phpstan-sarif-formatter
[2]: https://phpstan.org
[3]: https://github.com
[4]: https://docs.oasis-open.org/sarif/sarif/v2.0/sarif-v2.0.html
[5]: https://codeql.github.com
