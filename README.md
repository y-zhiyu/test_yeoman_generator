```
$ mkdir test_yeoman_generator
$ cd test_yeoman_generator
$ npm init -y
$ npm install yeoman-generator

```

```
npm link
// package.json=> "name": "generator-tbtest",
yo tbtest  //调用generator-tbtest生成器
//  yo tbtest:page2

```

```
npm get registry
npm config set registry https://registry.npmjs.org/

npm login --registry=https://npm.pkg.github.com --scope=@y-zhiyu
yarn publish -registry=https://npm.pkg.github.com
npm install  generator-tbtest
yo tbtest

```

