
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
# rust and cargo 
rustc --version

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash
# nvm

nvm install node --latest-npm
nvm use node
