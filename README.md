# 🚀 DevNews

> **The platform for developers to build, share and grow their projects.**

DevNews is a social platform created for developers, game creators and other creators to share the development of their projects with a community.

Create a project, publish devlogs, release new versions, share updates, build a roadmap and communicate with your community — all in one place.

---

## ✨ Features

### 🎮 Projects

Create a dedicated page for your project with:

* Project name
* Description
* Icon & banner
* Categories
* Tags
* Website
* Download links
* Project statistics

### 📝 Devlogs

Share your development progress with the community.

Devlogs can contain:

* Text
* Images
* GIFs
* Video embeds
* Tags
* Comments
* Likes

### 📦 Releases

Publish new versions of your project and keep your release history organized.

Each release can include:

* Version number
* Release name
* Changelog
* Description
* Download link
* Release date

### 🛠️ Updates

Post quick updates and announcements without creating a full devlog.

### 🗺️ Roadmaps

Show your community what you're working on.

Roadmap statuses:

* 🟦 Planned
* 🟨 In Progress
* 🟩 Completed
* 🟥 Cancelled

### 💬 Community

Every project can have its own community.

Users can:

* Create discussions
* Comment
* Reply
* Like
* Report content

### ❤️ Following

Follow projects and keep up with their development.

Get updates when a followed project publishes:

* Devlogs
* Releases
* Updates
* Roadmap changes

### 🔔 Notifications

Receive notifications for important activity, including:

* Comments
* Replies
* New releases
* New devlogs
* Project updates

### 📊 Analytics

Project owners can view statistics such as:

* Views
* Followers
* Likes
* Comments
* Devlog views
* Release downloads

---

## 🧑‍💻 Developer Dashboard

Every project has its own management dashboard.

```text
Dashboard
│
├── Overview
├── Devlogs
├── Releases
├── Updates
├── Roadmap
├── Community
├── Analytics
└── Settings
```

Developers can manage their entire project from one place.

---

## 🛠️ Tech Stack

DevNews is built using:

* **HTML**
* **CSS**
* **JavaScript**
* **Supabase**
* **Supabase Authentication**
* **Supabase PostgreSQL**
* **Supabase Storage**

---

## 🗄️ Database

The planned database structure includes:

```text
profiles
projects
project_members
devlogs
devlog_likes
releases
updates
roadmap_items
comments
comment_likes
project_follows
notifications
community_posts
community_post_likes
```

Supabase Row Level Security is used to protect user and project data.

---

## 👥 Project Roles

Projects can have multiple members.

| Role      | Description                |
| --------- | -------------------------- |
| Owner     | Full project control       |
| Admin     | Project management         |
| Developer | Development-related access |
| Editor    | Content management         |

Permissions determine which members can edit the project, publish content or moderate the community.

---

## 🔐 Authentication

DevNews uses Supabase Authentication.

Users can:

* Create an account
* Log in
* Log out
* Reset their password
* Manage their profile

---

## 📁 Project Structure

Example project structure:

```text
DevNews/
│
├── index.html
├── login.html
├── register.html
├── projects.html
├── project.html
├── devlog.html
├── release.html
├── community.html
├── dashboard.html
│
├── css/
│   ├── main.css
│   ├── auth.css
│   └── dashboard.css
│
├── js/
│   ├── supabase.js
│   ├── auth.js
│   ├── projects.js
│   ├── devlogs.js
│   ├── releases.js
│   ├── updates.js
│   ├── roadmap.js
│   ├── comments.js
│   ├── community.js
│   └── notifications.js
│
└── assets/
    ├── icons/
    └── images/
```

The exact structure may change during development.

---

## 🚧 Development Status

DevNews is currently **in development**.

Planned development order:

* [ ] Authentication
* [ ] User profiles
* [ ] Project creation
* [ ] Project pages
* [ ] Developer dashboard
* [ ] Devlogs
* [ ] Comments
* [ ] Releases
* [ ] Updates
* [ ] Roadmaps
* [ ] Community
* [ ] Following system
* [ ] Notifications
* [ ] Search
* [ ] Analytics
* [ ] Project teams
* [ ] Moderation system

Features may change as development continues.

---

## 🎯 Vision

DevNews aims to become a place where developers can show the entire journey of their projects — from the first idea to the final release.

Instead of sharing development progress across multiple platforms, creators can have one central place for their:

**Projects → Devlogs → Updates → Releases → Roadmaps → Community**

---

## 🤝 Community

DevNews is designed around community interaction.

Developers can share what they're building, while users can follow projects, discuss updates, give feedback and watch projects grow over time.

---

## 📄 License

License information will be added later.

---

**DevNews** — *Build it. Share it. Grow it.*
