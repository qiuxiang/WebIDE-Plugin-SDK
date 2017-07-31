---
order: 2
title: 更新日志
toc: false
timeline: true
---
# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## 1.0.0-alpha.03
ADD:
- 增加从环境变量获取插件并编译方法


## 1.0.0-alpha.02
ADD:
- webpack 增加 externals 配置，使得在 api 设计不够完善的时候可以像 import 主项目的元素一样调用 window.app下的文件,对现有方案做一个 fallback

## 1.0.0-alpha.01
REMOVE:
- 去除 redux 内嵌支持
- 提供 modules 运行时加载所需要的基础类库

## 0.0.1-alpha.10
ADD:
- 增加 i18n 支持

## 0.0.1-alpha.09
FIXED:
- 修改 fetchPackage 逻辑

## 0.0.1-alpha.08
FIXED:
- 修改 fetchPackage 逻辑

## 0.0.1-alpha.07
FIXED:
- 修改 fetchPackage 的 git pull后参数

## 0.0.1-alpha.06
FIXED: 
- 修改 mapPackage

## 0.0.1-alpha.05
ADDED:
－ injectComponent 支持

## 0.0.1

### Main
ADDED: 增加基础的sdk与编译逻辑