---
layout: post
title: "[JAVA] Hello World 실행하기(Java Hello World!)"
date: 2014-09-16 02:01:00
image: '/assets/img/java/20140916/java_hello_world.jpg'
description: Java Hello World!.
category: 'java'
tags:
- java
- tutorial

twitter_text: [JAVA] Hello World 실행하기(Java Hello World!).
introduction: 자바(Java) 프로그래밍으로 Console, Edit Plus, Eclipse 도구를 사용해 Hello World를 실행하는 방법을 설명합니다.

---

Java를 실행할 때 콘솔(Console)에서 직접 입력하여 실행하거나, EditPlus, Eclipse, Net Beans 등과 같은 코드편집 툴(Tool)을 이용해서 실행하여 결과를 확인합니다.

아래의 예제를 통해 윈도우의 cmd 를 이용한 콘솔(Console) 프로그램, EditPlus, Eclipse에서 Hello World 코드를 실행하는 과정을 알아보겠습니다.


1. 자바(Java)의 구조
2. 콘솔(Console) 프로그램에서 실행하기
3. Edit Plus에서 실행하기
4. Eclipse에서 실행하기

-----

# 1. 자바(Java)의 구조

자바의 구조를 간단하게 설명하면 `클래스`라는 틀 안에 `메서드` 또는 `함수`라고 불리는 작은 영역들로 구성되어 있습니다.
그림으로 보면 아래와 같이 간략하게 나타낼 수 있습니다.

![그림1. 20171206_001_Structure-of-Java_1](/assets/img/java/20140916/20171206_001_Structure-of-Java_1.jpg)

자바의 모든 코드는 클래스(Class) 안에 작성되어야 합니다.
그리고 자바를 실행하면 가장먼저 클래스 안의 main() 메서드를 실행시킵니다.



## 1.1. 코드 작성
```java
class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```
