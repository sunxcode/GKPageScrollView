<div align=center><img src="GKPageScrollViewDemo/gif/GKPageScrollView.png" width="405" height="63" /></div>

[![License MIT](https://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://raw.githubusercontent.com/QuintGao/GKPageScrollView/master/LICENSE)&nbsp;&nbsp;
[![platform](http://img.shields.io/cocoapods/p/GKPageScrollView.svg?style=flat)](http://cocoadocs.org/docsets/GKPageScrollView)&nbsp;&nbsp;
[![languages](https://img.shields.io/badge/language-objective--c-blue.svg)](#) &nbsp;&nbsp;
[![cocoapods](http://img.shields.io/cocoapods/v/GKPageScrollView.svg?style=flat)](https://cocoapods.org/pods/GKPageScrollView)&nbsp;&nbsp;
[![support](https://img.shields.io/badge/support-ios%208%2B-orange.svg)](#) 

iOS类似微博、抖音、网易云等个人详情页滑动嵌套效果
==========

GKPageScrollView是一个UIScrollview嵌套滑动库，主页参考了[JXPagingView](https://github.com/pujiaxin33/JXPagingView)，在他的基础上做了修改，实现了自己想要的效果。

## 主要功能

- 支持上下滑动、左右滑动，手势返回等
- 支持如UITableView的sectionView的悬停效果
- 支持多种分页控件，如[JXCategory](https://github.com/pujiaxin33/JXCategoryView),[WMPageController](https://github.com/wangmchn/WMPageController)等
- 可实现导航栏颜色渐变、头图下拉放大等效果
- 支持主页、列表页下拉刷新，上拉加载

## 效果图

| 说明 | 效果图 |
|-------|-------|
| **微博个人主页** | ![wb](https://github.com/QuintGao/GKPageScrollView/blob/master/GKPageScrollViewDemo/gif/wb.gif) |
| **微博发现页** | ![wb](https://github.com/QuintGao/GKPageScrollView/blob/master/GKPageScrollViewDemo/gif/wb_find.gif) |
| **网易云歌手页** | ![wy](https://github.com/QuintGao/GKPageScrollView/blob/master/GKPageScrollViewDemo/gif/wy.gif) |
| **抖音个人主页** | ![dy](https://github.com/QuintGao/GKPageScrollView/blob/master/GKPageScrollViewDemo/gif/dy.gif) |
| **主页下拉刷新** | ![dy](https://github.com/QuintGao/GKPageScrollView/blob/master/GKPageScrollViewDemo/gif/mainRefresh.gif) |
| **列表下拉刷新** | ![dy](https://github.com/QuintGao/GKPageScrollView/blob/master/GKPageScrollViewDemo/gif/listRefresh.gif) |

## 说明
简书：[iOS-多个UIScrollView滑动嵌套(仿微博、抖音、网易云个人详情页)](https://www.jianshu.com/p/5ce57fccdc03)

## 版本更新
* 2019.2.25   1.0.7 - 优化切换临界点和原点的方法，增加仿微博发现页demo
* 2019.2.20   1.0.6 - 增加快速切换临界点和原点的方法
* 2018.12.11 1.0.3 - 支持下拉刷新、上拉加载
