---
date: '2022-07-05'
title: 'Zero Copy I/O Library'
github: ''
external: 'https://github.com/shaoyi1997/zero-copy-io'
tech:
  - C/C++
company: ''
showInProjects: true
---

Library implementing zero-copy read and write operations that eliminate the copying between the kernel and user buffers. User can open a file, read from the file without using a user buffer, write to the file without using a user buffer, reposition within the file and close. The user directly uses the kernel buffer provided by the library calls to read and write data.
