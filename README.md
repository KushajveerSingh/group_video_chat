# Group Video Chat
[demo](https://kushaj-group-video-chat.vercel.app)

![](assets/demo_image.png)

A group video chat application built using [Agora App Builder](https://appbuilder.agora.io/). You can host conference video chats with support for multiple people at the same time, share screen, private and group messaging, admin controls and create polls. This project is mostly focused on working with an enterprise scale codebase and adding features on top of it (like creating polls) by reading the documentation.

## Table of Contents
- [Demo Videos](#demo-videos)
    - [Create meeting](#create-meeting)
    - [Messaging](#messaging)
    - [Create polls](#create-polls)
- [Local Setup](#local-setup)
- [License](#license)

## Demo Videos

### Create meeting
Create meetings and share a link with others to join. Admin can mute other people, stop their video, give privileges and more. Further screen sharing capability is also there.

### Messaging
Group chat or chat with the specific people you want privately.

### Create polls
Create polls to further engage the audience.

## Local Setup
**Step 1**. Setup Node.js v16.17.1. [nvm](https://github.com/nvm-sh/nvm) can be used to quickly setup Node.js (and you can also have multiple versions of Node.js).
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
nvm install 16.17.1
```

**Step 2**. Clone the repository and install all the dependencies.
```
git clone https://github.com/KushajveerSingh/group_video_chat.git
cd group_video_chat
npm install --legacy-peer-deps
```

`--legacy-peer-deps` would install the exact packages as used in the repository. The repository already includes VSCode and Prettier setup, and you can modify the default behavior in `.vscode/settings.json` and `.prettierrc` respectively.

## License
This application has Apache License Version 2.0, as found in the [LICENSE](./LICENSE) file.