# git remote

When working with git, a **remote** is any git repository that is not on the machine you're working on. The counterpart to this is **local**, or the machine that is being developed on.

Take GitHub for eample. While git is the technology that allows you to create local respositories, GitHub is the site that will host your remote respoitories. Once stored remotely, you can bring that repository back down or share it with others.

**Note**: While the respositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

### Adding a remote

A remote can be added with the `git remote add` command, followed by the name and location of the remote.

The name is a local name, meaning it's your label and does not impact the acutal remote whatsovever.

```
git reemote add origin httpls://github.com/ElevenFiftyAcademy/GitFunadamentals.git
```
### Removing a remote

A remote can be removed with the `git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```
### Rescources
- [Git Remote Documentation](https://git-scm.com/docs/git-remote)

---

[Back to home](../README/md)
