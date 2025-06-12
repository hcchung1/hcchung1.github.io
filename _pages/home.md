---
layout: splash
title: "Henry's Portfolio"
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: mm-home-page-feature.jpg
  actions:
    - label: "View My Projects"
      url: "/projects/"
  caption:
excerpt: 'A Sophomore majoring in CS at NYCU, trying to made some great projects as an useful tool in our daily life.'
feature_row:
  - image_path: https://via.placeholder.com/600x400
    alt: "BTC/ETH 預測"
    title: "BTC/ETH 預測工具"
    excerpt: "使用 LSTM 和技術指標預測加密貨幣價格走勢。"
    url: "/portfolio/btc-eth"
    btn_label: "詳細介紹"

  - image_path: https://via.placeholder.com/600x400
    alt: "Network Chatroom"
    title: "網路程式聊天室"
    excerpt: "多人聊天室與 FTP 模擬器，支援 Broadcast、私訊與檔案傳輸。"
    url: "/portfolio/network-prog"
    btn_label: "查看專案"

  - image_path: https://via.placeholder.com/600x400
    alt: "Computer Org"
    title: "電腦組織模擬器"
    excerpt: "Verilog 實作單週期 MIPS CPU，支援 ALU、Branch、Memory 等功能模擬。"
    url: "/portfolio/computer-org"
    btn_label: "了解更多"

github:
  - excerpt: '{::nomarkdown}<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=mmistakes&repo=minimal-mistakes&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe> <iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=mmistakes&repo=minimal-mistakes&type=fork&count=true&size=large" frameborder="0" scrolling="0" width="158px" height="30px"></iframe>{:/nomarkdown}'
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
