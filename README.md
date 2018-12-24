# How to add support for your kernel

How to add your kernel :-

1. Fork this repo

2. Create a file, like yuka.json, and write like [this](https://github.com/AyraHikari/KernelAdiutor-repo/blob/master/yuka.json)

3. Edit land.json, add your.json url like this:

```
[
  "https://raw.githubusercontent.com/AyraHikari/KernelAdiutor-repo/master/yuka.json",
  "<your.json url file>"
]
```

For example, edit `<your.json url file>` to like this `https://raw.githubusercontent.com/AyraHikari/KernelAdiutor-repo/master/yuka.json`

5. After that, please pull request at this repo

Note: For update new kernel version, just update your.json on your git
