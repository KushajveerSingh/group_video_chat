# Group Video Chat
**Note:-** Since Heroku removed their free tier, I have not migrated the backend to another service. And as a result, the demo would not work. Sorry for the inconvenience. But you can still see the demo videos down below, to see the working of the app.

[demo](https://kushaj-group-video-chat.vercel.app)

![](assets/demo_image.png)

- Developed a group video chat application with support for multiple participants, screen sharing, private and group messaging, admin controls, and polling, using Agora's chat builder for scalability and rapid development.
- Enhanced existing Agora codebase with additional features such as a polling system, showcasing the ability to work effectively in large codebases and integrate new functionalities.
- Implemented user-friendly features such as meeting creation and sharing, admin controls for muting and managing participants, and options for private or group chats, promoting an engaging user experience.
- Deployed the frontend on Vercel and the backend on Heroku.

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

https://user-images.githubusercontent.com/24699564/196153810-af639f64-235a-4ecc-b4b5-71f07b7426f6.mp4

### Messaging
Group chat or chat with the specific people you want privately.

https://user-images.githubusercontent.com/24699564/196153864-0eb8da0b-0c44-4bb2-a52c-e8fadfedd7d4.mp4

### Create polls
Create polls to further engage the audience.

https://user-images.githubusercontent.com/24699564/196153893-9f891866-e6ec-4ab8-b7cd-3454258ea8cb.mp4

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
