# Collection

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
It'll ask for your Mac password (admin rights, which you have).
At the end it prints 1-2 lines starting with echo — copy and run those exact lines it gives you (they add Homebrew to your PATH; the exact path differs on Apple Silicon vs Intel Macs).
Verify: brew --version
2. Node.js LTS
brew install node
Verify: node -v (should show v20.x or v22.x) and npm -v
3. CocoaPods
brew install cocoapods
Verify: pod --version
If brew install cocoapods ever fails, the fallback is sudo gem install cocoapods instead.

4. Final check
Run all four together to confirm everything's good:

git --version && node -v && npm -v && pod --version
Once
