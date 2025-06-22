---
title: "{{ replace .Name "-" " " | title }}" # 파일명을 기반으로 제목 자동 생성
date: {{ .Date }}
draft: true

# --- 독서록 정보 ---
book_title: ""
book_author: ""
book_cover: "" # 책 표지 이미지 경로 (예: /images/book1.jpg)
read_date: "" # 읽은 날짜 (예: 2025-06-21)
rating: 0 # 1~5 사이의 숫자 평점

# --- 블로그 기능 ---
tags: []
categories: []
---

## 서평
여기에 서평을 자유롭게 작성하세요.