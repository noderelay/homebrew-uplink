# homebrew-uplink

Homebrew tap for [Uplink](https://uplinkirc.chat), a fast, secure,
IRCv3-featured IRC client.

```
brew tap noderelay/uplink
brew trust noderelay/uplink
brew install --cask uplink
```

The trust step is required once per machine: current Homebrew refuses
to load casks from third-party taps until the tap is marked trusted.

Uplink is not notarized by Apple; if macOS blocks the first launch, allow
it under System Settings -> Privacy & Security, or install with
--no-quarantine.
