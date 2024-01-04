### Hi there 👋

I occasionally write code of questionable quality.

<!--
**khakers/khakers** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


#### Code signing

As of Jan, 1, 2024, I am moving to signing commits with an SSH key instead of GPG keys.
My new signing key is stored as a FIDO2 credential on a yubikey, so it is very unlikely to change in the future.

New signing key below:

```
sk-ssh-ed25519@openssh.com AAAAGnNrLXNzaC1lZDI1NTE5QG9wZW5zc2guY29tAAAAILJfFjlHCkkfke9gevW9JsCGLZr506MnS9O4UfH9b6TrAAAAEXNzaDpnaC1raC1zaWduaW5n
```

My old GPG keys will stil be listed as valid on github to keep old commits from becoming unverified, but no new commits should be signed with them.
