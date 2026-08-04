---
layout: post
title: 왜 Pixel Flow는 선형적인 레벨 구조를 선택했을까?
date: 2026-02-25 00:00:00 +0900
categories:
  - Game Analysis
tags:
  - PixelFlow
  - LevelDesign
---
## Pixel Flow의 레벨 디자인 분석
![[Pasted image 20260803175646.png]]
### 0. 개요
이 글은 퍼즐 게임 **Pixel Flow**의 선형적인 레벨 구조를 중심으로, 개발사가 왜 플레이어의 레벨 선택 자유를 제한했는지 분석한다.

특히 선형적인 진행 방식이 플레이어의 **학습 곡선**(Learning Curve), ​**난이도 곡선**(Difficulty Curve), 그리고 ​**플레이 흐름**(Pacing)에 어떤 영향을 주는지 살펴보고, 이러한 설계가 게임 경험에 어떤 역할을 하는지 정리해 보았다.