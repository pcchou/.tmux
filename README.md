pcchou's tmux configurations
===

How to use?
---

Backup your original `.tmux.conf` and `.tmux` settings.

1. You'll need to be using a 256-color terminal. You can add ``export TERM='xterm-256color'`` to your `.bashrc`.
2. ``git clone --recursive https://github.com/pcchou/.tmux.git && ln -s .tmux/.tmux.conf`` in your home directory.
3. .
  * If you want to use powerline, you'll need to install powerline.
    1. ``pip install --user git+git://github.com/Lokaltog/powerline`` to install powerline.
    2. Download a powerline font, and put it in your `~/.fonts` to install it.
    3. Set your terminal to use it.
  * If you don't want to use powerline, please ``git checkout nopowerline`` in your `~/.tmux` directory (the repository).
4. Open tmux and press ``prefix`` (usually ``ctrl-b``) then ``I`` to install plugins.
5. Use it and report any issue or suggestions.


Plugin List
---
* [tmux-sensible](https://github.com/tmux-plugins/tmux-sensible)
* [tmux-resurrect](https://github.com/tmux-plugins/tmux-resurrect)
* [Tmux Plugin Manager](https://github.com/tmux-plugins/tmux-resurrect)
* [tmux-yank](https://github.com/tmux-plugins/tmux-yank)
