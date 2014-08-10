<img src="http://www.cocos2d-x.org/attachments/801/cocos2dx_portrait.png" width=200>

cocos2d-x Projects Template
=============

This is a projects template of [cocos2d-x](http://cocos2d-x.org/) development.
It is in the state after running the `cocos new` command.

## Description

- You don't have to run the `cocos new` command.  
  <del>`cocos new MyGame -p com.your_company.mygame -l cpp -d NEW_PROJECTS_DIR`</del>
- You can create the universal binary for iOS in `rake` command.  

## Requirement

- cocos2d-x v3.1.1 only
- environment variables of cocos2d-x already set up

## How to start

```shell
$ git clone -b <branch-name> git@github.com:yuuki-arc/CocosNew.git
$ cd CocosNew/build
$ rake lib && rake lipo
```

## Features

- Multiple versions
- Simplify the setup

## References
- http://qiita.com/g-1/items/01f6c430326dfd125af9
- http://qiita.com/KawabataLemon/items/8387b0e54b06308a8693
