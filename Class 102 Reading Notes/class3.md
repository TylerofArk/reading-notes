# Class 3 Reading Notes

## Revisions and the Cloud

### Version Control

#### Local

One database on local harddrive that stores and changes files

#### Centralized

Allows for collaboration between multiple developers on the same file

#### Distributed

Allows clients to create mirrored repositories, or data backup, as an answer to the vulnerability of CVCS.

#### Git

- A distributed version control system.
- Lets Multiple Developers work on the same code.
- Greatly minimizes loss of data.
- Tracks all file changes.

#### Git Repository and ACP Workflow

1. Create Github Repository
2. Clone repository to VS Code using terminal
3. Add new files in VS Code from then on
4. Move to the folder of your VS Code clone using cd
5. Sync Changes from VS Code back to github using
   - git add . for all or git add filename for single file
   - git commit -m "Why you made the change"
   - git push origin main
