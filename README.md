## Installation/Setup
1. Download or clone repo `git clone https://github.com/fcgrolleau/fcgrolleau.github.io.git`
2. Enter the folder: `cd fcgrolleau.github.io/`
3. Build it: `jekyll build`
4. Start Jekyll server: `jekyll serve`
5. Configure: `_config.yml`

Access via: [http://localhost:4000/](http://localhost:4000/) <br>
Push to Github to make it available at: [https://fcgrolleau.github.io/](https://fcgrolleau.github.io/)

## Troubleshooting
If Jekyll cannot be loaded, try:
1. Load chruby `source /usr/local/opt/chruby/share/chruby/chruby.sh`
2. Check all versions of Ruby available `chruby`
3. Switch to the latest Ruby version e.g., `chruby ruby-3.3.1`