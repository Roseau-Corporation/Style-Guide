# Pull requests
## Update pull request
An update pull request includes multiple features. It should look like the following:
```md
This pull request includes the following:
1. First feature name
2. Second feature name
3. Third feature name
4. etc.
```
It should be merging into the ``stable`` branch, and merged from ``staging``.

## Feature pull request
A feature pull request should include one feature and include the required modules to implement said feature. The name should be the feature name, and the description should look like the following:
```md
This pull request includes the following:
1. Feature name
2. First module name
3. Second module name
4. etc.

This pull request does not include the following:
1. Feature to be implemented with a future pr.
2. Other feature to be implemented with a future pr.
```
The does not include should only include planned features (to the main feature) that are going to be added with a future pull request.
This pull request should be merging into the ``staging`` branch, and merged from the feature branch.
