# wal-telegram

# Screenshots

![demo 1 (green)](https://user-images.githubusercontent.com/40271651/42736395-79242280-8866-11e8-8419-a9dc0b22be4c.png)
![demo 2 (orange)](https://user-images.githubusercontent.com/40271651/42736398-7e628d04-8866-11e8-9b40-ee09c09910d7.png)
![demo 3 (purple)](https://user-images.githubusercontent.com/40271651/42736400-81f08110-8866-11e8-860d-d71c3e1b4c10.png)

# Installation

```bash
git clone --depth 1 https://github.com/matteoguarda/wal-telegram
cd wal-telegram
./wal-telegram
```

To select the theme follow these steps:

1. Open telegram, go to "settings/chat background" and click on choose from file:
![instruction 1](https://user-images.githubusercontent.com/40271651/42967114-863e1890-8b9f-11e8-80f5-3b52ff75cdef.png)

2. Toggle hidden files (in english that's show hidden files):
![instruction 2](https://user-images.githubusercontent.com/40271651/42967489-b054cf42-8ba0-11e8-925d-7ca11597a537.png)

3. Double click on ~/.cache/wal-telegram/colors.tdesktop-theme:
![instruction 3](https://user-images.githubusercontent.com/40271651/42967681-5592a5ce-8ba1-11e8-83f3-195d3c14f3f8.png)

4. Double click on ~/.cache/wal-telegram/background.png or jpg depending on your wallpaper:
![instruction 4](https://user-images.githubusercontent.com/40271651/42967685-58456ba8-8ba1-11e8-8ea4-897177b9b18f.png)

# Updating

You can update wal-telegram by running git pull inside wal-telegram:
```bash
cd wal-telegram
git pull
```

# Important notes

Some color constants in colors.tdesktop-theme are marked as // [UNTESTED], this because I couldn't find the elements responsable in the app.
So if you find something strange open an issue (with a screenshot of the element and it's name if possible) and I'll fix.

You can also use light colorschemes, no need for extra option, just run tde normally.

The theme works with [wal] too, not just [pywal].

[pywal]: https://github.com/dylanaraps/pywal
[wal]: https://github.com/dylanaraps/wal
