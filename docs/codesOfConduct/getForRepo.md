---
name: Get the contents of a repository's code of conduct
example: octokit.codesOfConduct.getForRepo({ owner, repo })
route: GET /repos/{owner}/{repo}/community/code_of_conduct
scope: codesOfConduct
type: API method
---

# Get the contents of a repository's code of conduct

This method returns the contents of the repository's code of conduct file, if one is detected.

```js
octokit.codesOfConduct.getForRepo({
  owner,
  repo,
});
```

## Parameters

<table>
  <thead>
    <tr>
      <th>name</th>
      <th>required</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>owner</td><td>yes</td><td>

</td></tr>
<tr><td>repo</td><td>yes</td><td>

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://developer.github.com/v3/codes_of_conduct/#get-the-contents-of-a-repositorys-code-of-conduct).
