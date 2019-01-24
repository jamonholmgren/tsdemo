# Steps to replicate

```shell
git clone https://github.com/jamonholmgren/tsdemo.git
cd tsdemo
yarn
yarn upgrade ts-node@7.0.1
yarn link
cd ~
tsdemo
# observe it working
cd -
yarn upgreade ts-node@8.0.1
yarn link
cd ~
tsdemo
# observe it not working
```

