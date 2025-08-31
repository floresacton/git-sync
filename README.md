# git-sync
Manage repos between devices

Looks at directory and compares it to user's repositories.


### Usage
```gsync status [--path PATH] [--missing]```
Returns head status and save status
of local repositories. Remote repository symmetry too between
local folders and remote repositories if missing flag enabled.

```gsync clone```
Clone any repositories user repositories that don't exist locally

### Install
```pip install git_sync_tool==0.1.8```

Specify version otherwise sometimes it grabs older ones
