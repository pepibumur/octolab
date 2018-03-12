OctoLab
========

[![Greenkeeper badge](https://badges.greenkeeper.io/pepibumur/octolab.svg)](https://greenkeeper.io/)

[![Build Status](https://travis-ci.org/pepibumur/octolab.svg?branch=master)](https://travis-ci.org/pepibumur/octolab)
![Github All Releases](https://img.shields.io/github/downloads/pepibumur/octolab/total.svg)
![GitHub release](https://img.shields.io/github/release/pepibumur/octolab.svg)
[![GitHub stars](https://img.shields.io/github/stars/pepibumur/octolab.svg)](https://github.com/pepibumur/octolab/stargazers)
[![GitHub license](https://img.shields.io/github/license/pepibumur/octolab.svg)](https://github.com/pepibumur/octolab/blob/master/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/pepibumur/octolab.svg)](https://github.com/pepibumur/octolab/issues)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/pepibumur/octolab.svg?style=social)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fpepibumur%2Foctolab)

OctoLab is an open source productivity app for GitHub

## Motivation

Being productive working on multiple GitHub projects can be a very tedious task. GitHub features such as issues, projects, milestones or releases, were designed to organize the work in a per-repository basis. I often found myself wondering which task I should work on, or what was the next important milestone I should focus on. I tried some apps for desktop, mobile, and web but none of them really helped me organize my daily work on GitHub. I also tried task management apps but the information ends up spreading across GitHub and your apps. The idea of building OctoLab came up from this need that I had. **What if there was a desktop app that combines the task management features with GitHub's? What if that app could leverage system features to make you even more productive?**

## Open source
OctoLab is entirely open source. As I said, my main motivation is building a tool that I need and that other developers might need as well. I don't aim to create a business out of it, or devote all my time to build it. I build OctoLab on my spare time with anyone that would love to get involved. Everyone on this project has a voice that is listened and respected. Besides the code, the planning and the roadmap of the project  will also be open. We'll share what's coming on future releases and keep all the discussions open. If you like the project and would love to contribute, I recommend you to start by reading [contributing](CONTRIBUTING.md) guidelines.

## Electron
OctoLab is built using Electron. Electron is often criticised for its performance in apps like Slack or Atom. Each Electron app runs a Chromium instance that loads your application *((HTML, CSS & JS)* and that's obviously slower than running precompiled native code. However, it's the only framework that allows building cross-platform applications using open technologies. I considered initially building OctoLab for macOS using Swift but I'd be making the app less accessible. Developers that work on environments with Linux or Window wouldn't have access to the app. I have traditionally been an Objective-C/Swift developers but I recently shifted towards defaulting to more accesible and non-propietary technologies and programming languages for my projects *(whenever it's possible)*.

## Features
- Offline mode 🌍
- Notifications 📨
- Snooze ⏰
- Priorities ☘️
- System shortcuts 💥
- Keyboard navigation 💻

## Setup

1. Git clone repository `git clone git@github.com:pepibumur/octolab.git`.
2. Install dependencies `yarn install`.
3. Run locally with `yarn run dev`.

## References

- [electron-compile](https://github.com/electron-userland/electron-compile)
- [electron](https://electronjs.org/)
- [electron-react-typescript-boilerplate](https://github.com/iRath96/electron-react-typescript-boilerplate)

## License

```
The MIT License (MIT)

Copyright (c) 2018-present Pedro Piñera

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```