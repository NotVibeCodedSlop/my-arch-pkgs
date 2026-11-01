# install using paru
```bash
cat >> ~/.config/paru/paru.conf <<< $'\n[NotVibeCodedSlopRepos]\nUrl = https://github.com/NotVibeCodedSlop/my-arch-pkgs.git' && paru -Sy --pkgbuilds && (cd ~/.cache/paru/clone/repo/NotVibeCodedSlopRepos/ 2>/dev/null || cd ~/.cache/paru/clone/NotVibeCodedSlopRepos/ && git submodule update --init --recursive) && paru -S --pkgbuilds
```
