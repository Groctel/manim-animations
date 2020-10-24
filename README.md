# manim-animations

**Here are the animations I've made using [manim](https://github.com/ManimCommunity/manim)**

# Rendering the animations

The code is designed to be run from the repository's root.

```sh
python3 -m manim scenes/euclides.py Euclides
```

You can render all scenes in a file by checking the total number of scenes and piping with `seq`:

```sh
for i in $(seq 1 34); do echo "$i" | python3 -m manim scenes/DEIIT/taller-git-github.py; done
```

Refer to [the documentation](https://docs.manim.community/en/latest/index.html) for more information on installing and running manim.
