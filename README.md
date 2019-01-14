## Usage

1) Install cfhighlander from feature branch

```
git clone https://github.com/toshke/cfhighlander
git checkout feature/vpc-lambda-config
gem build cfhighlander.gemspec
gem install *.gem
```

2) Compile the demo

```
cfcompile github:toshke/hl-component-vpc-lambdas
```