---
title: "BetterMeower Classic: What we've done so far"
date: 2023-06-03
---

BetterMeower Classic is the latest release of BetterMeower, bringing back features you know and love, such as better themes, more profile pictures, a more user friendly UI, and search functionality.

Just under 2 days of BetterMeower Classic's release, we've already updated it to have many more features than before, making BetterMeower, truly Better.

# New badges for bridged and webhook messages
Quite a minor upgrade, but we've brought the Svelte 1.5.0 post tags to BetterMeower Classic. Along with this, we also use Meower Svelte's LiText library to help prevent impersonation.

Bridged badges appear when a post is made using Meower's Discord bridge or Revower, while webhook badges appear on guest posts and webhook posts.

![BetterMeower Classic post tags](./assets/Screenshot%202023-06-03%20at%2012.47.46%20pm.png)

# Profiles that actually use all available space
If you ever looked at a Meower Profile on Meower Svelte or previous versions of BetterMeower, you'll notice that profiles are quite empty, and if a user doesn't have a quote, it's even more so.

That's where our new profiles come in, to actually use the available space. Now, you've got recent posts underneath quotes, making it easier to see user activity, and using more space.

![BetterMeower Classic Profiles](./assets/Screenshot%202023-06-03%20at%2012.52.47%20pm.png)

# Improved images system
The previous image system was pretty bad, you would have to include a file extension, and it didn't support go.meower.org links, used by Meower Discord Bridge and Revower.

Now, not only is a file extension no longer required, but we also support go.meower.org links!

![Better images system in BetterMeower Classic](./assets/Screenshot%202023-06-03%20at%202.48.42%20pm.png)

# Waaaaaaaaaaaay larger posts
Ever felt like 360 characters just wasn't enough? Well thanks to a server-side change, you can make posts up to 4K characters long in home, and 2K characters long in group chats.

Unfourtunately, Meower Svelte, the official client doesn't allow users to take advantage of this new server side change. However, with BetterMeower classic, you can take full advantage of these new limits.

![](./assets/largerPosts.mov)

# Moderation Panel for Moderators
While this definitely appeals to a much smaller group of users, this change allows moderators to use BetterMeower, while retaining access to moderation tools.

Surprisingly, this feature isn't in Meower Svelte, leaving moderators with the MeowyMod Bot, Meower Scratch, and BetterMeower Classic.

![Moderation Panel in BetterMeower Classic](./assets/Screenshot%202023-06-03%20at%203.01.33%20pm.png)

# Conclusion
With BetterMeower Classic already having many new changes, we hope you enjoy the new updates and having an alternate Svelte-based client.

*Posted by JoshAtticus*

<script src="https://utteranc.es/client.js"
        repo="BetterMeower/Blog"
        issue-term="title"
        label="comment"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>
