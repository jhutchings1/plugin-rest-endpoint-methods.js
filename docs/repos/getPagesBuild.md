---
name: Get a specific Pages build
example: octokit.repos.getPagesBuild({ owner, repo, build_id })
route: GET /repos/{owner}/{repo}/pages/builds/{build_id}
scope: repos
type: API method
---

# Get a specific Pages build

```js
octokit.repos.getPagesBuild({
  owner,
  repo,
  build_id,
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
<tr><td>build_id</td><td>yes</td><td>

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://developer.github.com/v3/repos/pages/#get-a-specific-pages-build).
