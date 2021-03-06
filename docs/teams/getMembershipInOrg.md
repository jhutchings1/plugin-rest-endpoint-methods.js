---
name: Get team membership for a user
example: octokit.teams.getMembershipInOrg({ org, team_slug, username })
route: GET /orgs/{org}/teams/{team_slug}/memberships/{username}
scope: teams
type: API method
---

# Get team membership for a user

**Deprecated:** This method has been renamed to teams.getMembershipForUserInOrg

Team members will include the members of child teams.

To get a user's membership with a team, the team must be visible to the authenticated user.

**Note:** You can also specify a team by `org_id` and `team_id` using the route `GET /organizations/:org_id/team/:team_id/memberships/:username`.

**Note:** The `role` for organization owners returns as `maintainer`. For more information about `maintainer` roles, see [Create a team](https://developer.github.com/v3/teams/#create-a-team).

```js
octokit.teams.getMembershipInOrg({
  org,
  team_slug,
  username,
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
    <tr><td>org</td><td>yes</td><td>

</td></tr>
<tr><td>team_slug</td><td>yes</td><td>

</td></tr>
<tr><td>username</td><td>yes</td><td>

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://developer.github.com/v3/teams/members/#get-team-membership-for-a-user).
