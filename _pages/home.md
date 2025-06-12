---
layout: splash
title: "Henry's Portfolio"
permalink: /
css: "/assets/css/custom.css"
header:
  overlay_color: "#5e616c"
  overlay_image: mm-home-page-feature.jpg
  actions:
    - label: "View My Projects"
      url: "/projects/"
  caption:
excerpt: 'A Sophomore majoring in CS at NYCU, trying to made some great projects as an useful tool in our daily life.'
feature_row:
  - image_path: https://images.unsplash.com/photo-1625563066122-442e87b0fe49?q=80&w=2344&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
    alt: "BTC/ETH 預測"
    title: "ETHUSDT Trading Robot"
    excerpt: "A2C, DQN forecasting trading robot"
    url: "/portfolio/btc-eth"
    btn_label: "Detail"

  - image_path: IncanGold.jpg
    alt: "Incan Gold: Network multi-user turn-based game"
    title: "Incan Gold: Network multi-user turn-based game"
    excerpt: "A multiple user turn-based game develop on Network"
    url: "/portfolio/network-prog"
    btn_label: "More"

  - image_path: https://images.unsplash.com/photo-1631067958403-dcfb819057da?q=80&w=2340&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
    alt: "Japanese Yen Notifier"
    title: "日圓匯率每日通知"
    excerpt: "Using python, git, github action to notify Japanese Yen"
    url: "/portfolio/currency"
    btn_label: "More"

github:
  - excerpt: '{::nomarkdown}<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=mmistakes&repo=minimal-mistakes&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe> <iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=mmistakes&repo=minimal-mistakes&type=fork&count=true&size=large" frameborder="0" scrolling="0" width="158px" height="30px"></iframe>{:/nomarkdown}'
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
