---
name: Remove a deploy key
example: octokit.repos.removeDeployKey({ owner, repo, key_id })
route: DELETE /repos/{owner}/{repo}/keys/{key_id}
scope: repos
type: API method
---

# Remove a deploy key

```js
octokit.repos.removeDeployKey({
  owner,
  repo,
  key_id,
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
<tr><td>key_id</td><td>yes</td><td>

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://developer.github.com/v3/repos/keys/#remove-a-deploy-key).
