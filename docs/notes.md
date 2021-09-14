### What I have built 

- The graphql fetch status query
- The App status head

### What I did not build

- Deployment Status and Instances Variables which are listed when one type `flyctl status`

### what I'd improve or fix if I had more time

- Have a better layout, i.e the different heads(app, deployment status etc) of each status would be a link fto avoid too much clutter and bombarding the user with all the information at a glance, it might be confusing.

- When one hovers on a variable under the different heads, I would give more information on the variable, especially in cases where variable names are similar e.g status, this adds more clarity for the user.

### How would I determine if this feature is successful

- If the variables used in each segment are clear to the user
- How comfortable is the user with the location of each app status
- If showing ALL the status information on the website was helpful
- Check which status head users are more interested in finding information on
- Have a focus group discussion with a users and get their experience of the current design


### Edge cases
 - In the `client.ex` file, under the fetch_app fn, I did not add any error handling 