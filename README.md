### Merhabalar 👋

- 🔭 Şu an KrakenBot üzerinde çalışıyorum.
- 🌱 Şu an swift dilini öğrenmekteyim.
- 📫  Bana nasıl ulaşabilirsin: [![Github Badge](https://img.shields.io/badge/-Github-000?style=quare&labelColor=000&logo=Github&logoColor=white&link=link)](link) 
[![Instagram Badge](https://img.shields.io/badge/-Instagram-C13584?style=flat-quare&labelColor=C13584&logo=instagram&logoColor=white&link=link)](link) 
[![Medium Badge](https://img.shields.io/badge/-Medium-757575?style=flat-quare&labelColor=757575&logo=Medium&logoColor=white&link=link)](link) 
[![linkedin](https://img.shields.io/badge/Linkedin-000000?style=for-the-badge&logo=Linkedin&logoColor=white)](profilinizin linki)
<a href="https://discord.gg/6yqQFErEUx" rel="nofollow">
        <img src="https://camo.githubusercontent.com/678e7ea5c4e63f5b009013272b9e09b7505c7bf12b1205218c12df5264bb9933/68747470733a2f2f696d672e736869656c64732e696f2f646973636f72642f3330383332333035363539323438363432303f6c6f676f3d646973636f7264" alt="chat on Discord" data-canonical-src="https://img.shields.io/discord/308323056592486420?logo=discord" style="max-width: 100%;"></a>
- 😄 Cinsiyetim: Erkek
- ⚡ Eğlencelerim: Kitap okumak|Kod yazmak|Yeni bilgiler edinmek...


# GitSavvy

[![tests](https://github.com/timbrel/GitSavvy/actions/workflows/lint.yml/badge.svg)](https://github.com/timbrel/GitSavvy/actions/workflows/lint.yml)
![License](https://camo.githubusercontent.com/890acbdcb87868b382af9a4b1fac507b9659d9bf/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d4d49542d626c75652e737667)

Sublime Text plugin providing probably all git has to offer:

- basic Git functionality; `init`, `add`, `commit`, `amend`, `checkout`, `pull`, `push`, etc.
- special views for status, branches, and tags.  Try `git: status`
- a superb "Repo History", like `gitk`, just with more features; try `git: Repo History`.  
- Rebasing just from that "Repo History".  Edit a commit, reword a commit, autosquash commits, apply a fixup, whatever...  the `[r]` menu
- a "Line History", just select something in a view and search the Command Palette for `git: Line History`
- likewise a "File History"
- `git diff` view, allowing user to stage, unstage and reset (discard) files, hunks or individual lines
- fixup/squash helpers everywhere, for example from the "Line History" 
- GitHub integration
    + issue/collaborator referencing when committing
    + opening the current file or a commit on GitHub at the selected line
    + make a new PR from the current branch
    
- GitHub-style blame view, showing hunk metadata and ability to view the commit that made the change


**Note:** GitSavvy requires Git versions at or greater than 2.18.0.

**Note:** Sublime Text 2 is not supported.  Also, GitSavvy takes advantage of modern features of Sublime Text (like annotations).  For the best experience, use the latest Sublime Text _dev_ build.  Or not, I mean it could also crash you, what am I to recommend here.


## Documentation

The documentation is probably outdated.  Yeah it's sad but you can contribute and I will eventually get onto it **but** every special view has help available, just press `?`.

Feature documentation can be found [here](docs/README.md).  It can also be accessed from within Sublime by opening the command palette and typing `GitSavvy: help`.


## Highlights

<table>
    <tr>
        <th>Inline-diff</th>
        <th>Status dashboard</th>
    </tr>
    <tr>
        <td width="50%">
            <a href="https://cloud.githubusercontent.com/assets/5016978/6471628/886430f8-c1a1-11e4-99e9-883837dba86f.gif">
                <img src="https://cloud.githubusercontent.com/assets/5016978/6471628/886430f8-c1a1-11e4-99e9-883837dba86f.gif" width="100%">
            </a>
        </td>
        <td width="50%">
            <a href="https://cloud.githubusercontent.com/assets/5016978/6704171/2f236466-cd02-11e4-9b7d-22cc880b5e9d.png">
                <img src="https://cloud.githubusercontent.com/assets/5016978/6704171/2f236466-cd02-11e4-9b7d-22cc880b5e9d.png" width="100%">
            </a>
        </td>
    </tr>
    <tr>
        <td width="50%">(Un)stage and revert individual lines and hunks.</td>
        <td width="50%">Display and overview and offer actions to manipulate your project state.</td>
    </tr>
</table>

<table>
    <tr>
        <th>Branch dashboard</th>
        <th>Tags dashboard</th>
    </tr>
    <tr>
        <td width="50%">
            <a href="https://cloud.githubusercontent.com/assets/5016978/6704168/2b2e7b84-cd02-11e4-90f4-8dd96b21edeb.png">
                <img src="https://cloud.githubusercontent.com/assets/5016978/6704168/2b2e7b84-cd02-11e4-90f4-8dd96b21edeb.png" width="100%">
            </a>
        </td>
        <td width="50%">
            <a href="https://cloud.githubusercontent.com/assets/5016978/6704169/2c80beac-cd02-11e4-8940-986ea0f0d6bb.png">
                <img src="https://cloud.githubusercontent.com/assets/5016978/6704169/2c80beac-cd02-11e4-8940-986ea0f0d6bb.png" width="100%">
            </a>
        </td>
    </tr>
    <tr>
        <td width="50%">View and manipulate local and remote branches.</td>
        <td width="50%">View and manipulate local and remote tags.</td>
    </tr>
</table>

<table>
    <tr>
        <th>Github integration</th>
        <th>Rebase dashboard</th>
    </tr>
    <tr>
        <td width="50%">
            <a href="https://cloud.githubusercontent.com/assets/5016978/6704029/8fcaddbe-cd00-11e4-83b6-32276a2c2b65.gif">
                <img src="https://cloud.githubusercontent.com/assets/5016978/6704029/8fcaddbe-cd00-11e4-83b6-32276a2c2b65.gif" width="100%">
            </a>
        </td>
        <td width="50%">
            <a href="https://cloud.githubusercontent.com/assets/5016978/7017776/5ca9ceca-dcb1-11e4-8fcb-552551f7743a.gif">
                <img src="https://cloud.githubusercontent.com/assets/5016978/7017776/5ca9ceca-dcb1-11e4-8fcb-552551f7743a.gif" width="100%">
            </a>
        </td>
    </tr>
    <tr>
        <td width="50%">Reference issues and collaborators in commits.  Open files on GitHub in the browser, with lines pre-selected.</td>
        <td width="50%"> Squash, edit, move, rebase, undo, redo.</td>
    </tr>
</table>


## Installation

### Simple

1. Install the [Sublime Text Package Control](https://packagecontrol.io/) plugin if you don't have it already.
2. Open the command palette and start typing `Package Control: Install Package`.
3. Enter `GitSavvy`.


### Less simple

If you want more control over what you pull down, or if you'd like to submit changes to GitSavvy, you should pull down the repository directly in the Packages folder and restart the editor.  You still have to run `Package Control: Satisfy Dependencies` after that!
