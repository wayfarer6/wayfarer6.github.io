---
layout: post 
title: "Chickadee로 OS 복습하기"
date: 2026-01-012 13:33:00 +0900
categories: [OS]
comments: true
tags: [chickadee,Memory, OS] 
---

### chickadee로 복습하게 된 이유 

- 운영체제를 이론적으로 배우고 실제로 커널을 다루어 본적은 없었기에 시작하게 됨.

#### 사전 준비 및 디버깅 

- github에서 chickadee를 clone 하면 됨 

- git clone https://github.com/cs161/chickadee/

- docker 폴더에 들어가서 build 및 run 하면 구축 종료!

#### 디버깅 

 ```bash
gdb -x build/chickadee.gdb
 ```


 ```bash
make run-gdb-allocator
 ```


 ### 후기 

 - 당분간 GDB 사용법 및 x86-64 어셈블리어 및 아키텍처에서 시스템 콜이나 메모리 위주로 자료를 정리할 필요가 있어 보인다. 메모리를 어떻게 관리하는지는 이론으로만 알고있었는데 처음 GDB 찍어보고 살펴보니 배울것이 더 많다는 생각도 하게 되었다.