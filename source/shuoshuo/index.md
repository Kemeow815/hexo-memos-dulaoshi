---
layout: page
top_meta: false
bottom_meta: false
sidebar: []
comments: false
title: 说说广场
---

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="referrer" content="no-referrer">
    <link rel="icon" href="/https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/img/logo.webp" type="image/*" />
    <link href="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/css/style.css" rel="stylesheet" type="text/css">
    <link href="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/css/APlayer.min.css" rel="stylesheet" type="text/css">
    <link href="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/css/highlight.github.min.css" rel="stylesheet" type="text/css">
    <link href="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/css/custom.css" rel="stylesheet" type="text/css">
    <title>Memos Top</title>

</head>

<body>
    <section id="main" class="container">
        <h1>Memos Top</h1>

        <blockquote>
            <p>Je <del>memos</del>, donc je suis - <em>René Descartes fans</em></p>
        </blockquote>

        <div class="total">Total <span id="total">0</span> Memos 🎉</div>

        <blockquote id="tag-filter" class="filter">
            <div id="tags"></div>
        </blockquote>

        <div id="memos" class="memos">
            <!-- Memos Container -->
        </div>

    </section>

    <footer class="markdown-body footer">
        <p>Copyright @
            <script>
                document.write(new Date().getFullYear())
            </script><a href="https://eallion.com/" target="_blank" rel="noopener noreferrer" class="hidden">Charles
                'eallion' Chin</a> All Rights Reserved.
        </p>

    </footer>

    <!-- Your Memos API -->
    <script type="text/javascript">
        var memos = {
            host: 'https://s.dusays.com/',  // Your Memos instance.
            limit: '10',  // Pagination to show.
            creatorId: '1',  // The old instance is 101, and the new instance is 1. 
            domId: '#memos',  // Default #memos.
            username: 'Teacher Du',  // You can customize the display ID that is not related to memos.
            name: 'Official Demo',  // You can customize the displayed full name, that is not related to memos.
        }

    </script>
    <script type="text/javascript" src="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/js/lazyload.min.js?v=17.8.3"></script>
    <script type="text/javascript" src="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/js/marked.min.js?v=11.1.1"></script>
    
    <script type="text/javascript" src="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/js/view-image.min.js?v=2.0.2"></script>

    <!-- for CJK language auto-spacing -->
    <!-- <script type="text/javascript" src="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/js/pangu.min.js?v=4.0.7"></script> -->

    <script type="text/javascript" src="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/js/moment.min.js?v=2.30.1"></script>
    <script type="text/javascript" src="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/js/moment.twitter.js"></script>

    <!-- <script type="text/javascript" src="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/js/APlayer.min.js"></script> -->
    <!-- <script type="text/javascript" src="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/js/Meting.min.js"></script> -->

    <script type="text/javascript" src="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/js/highlight.min.js?v=11.9.0"></script>
    <script type="text/javascript" src="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/js/main.js"></script>
    <script type="text/javascript" src="https://jsd.onmicrosoft.cn/gh/eallion/memos.top@main/assets/js/custom.js"></script>
    <script>hljs.highlightAll();</script>
</body>

</html>