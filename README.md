# Installation
- install homebrew: 

```python
ruby -e $(curl -fsSL https;?/raw.github.com/Homebrew/homebrew/go/install)"
brew doctor
```

- This makes it easy to install apps without have to:

```python
./configure
make
make install
```

- Take ownership of it and everything in usr directory.  This prevents installation from installing and giving you "needs permission error"

```python
sudo chown -R $USER /usr/local/include
```


