# Git Remote

When working with Git, a **remote** is any repository that is not on the machine you're working on. The counterpart to this is **local**, or the machine that is being developed on.

Take GitHub for example. While Git is the technology that allows you to create local repositories, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that repository back down or share it with others.

**Note**: While the repositories (local and remote) are related and track the same project, they can have different states if changes were not shared between the two.

### Adding a Remote

A remote can be added with the `git remote add` command, followed by the name and location of the remote.

The name is a local name, meaning it's your label and does not impact the actual remote whatsoever.

```
Git Remote add origin https://github.com/ElevenFiftyAcademy/GitFundamentals.git
```

### Removing a Remote

A remote can be removed with the `git remote remove` command, followed by the name of the remote.

```
Git Remote remove origin
```

## Resources

- [Git Remote Documentation](https://git-scm.com/docs/git-remote)

---

[Back to Home](../README.md)
