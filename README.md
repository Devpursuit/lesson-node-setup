# 🧰 Lesson 2: Play with Built-in Node Modules

Node.js comes with powerful tools built-in. Let’s explore some of them!

## 🔧 What You’ll Do

- Use `fs` to read and write files.
- Explore the `path` module.
- Use `os` to get system info.

## ✅ Activity Instructions

1. Create a new file called `modules.js`.
2. Use `fs` to write a file:

   ```js
   const fs = require('fs');

   fs.writeFileSync('message.txt', 'Learning Node is fun!');

3. Use os:

   ```js
   const os = require('os');
console.log(os.platform(), os.homedir());


# 🎯 Success Criteria

* You used 2–3 built-in Node modules.

* You understand that Node includes its own standard library.

* You created a new file with code that runs and outputs something!

# 🌟 Pro Tip

Explore the Node.js documentation to discover more modules like http, events, and crypto.
