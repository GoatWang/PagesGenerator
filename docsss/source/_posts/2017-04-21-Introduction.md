---
title: "IR1: 一個數學外行人學習資訊檢索(Information Retrieval)的筆記們–始"
date: 2017-04-21 19:44:26
tags:
categories: Information Retrieval
---

# 前言
近期自己投入了非常大量的時間吸收、理解這個領域的知識，也已經將這個領域部分學理論實踐在python中，也因為這樣的投入，很真實地感受到了數學的威力，我想這大約是目前我曾經接觸過的領域中唯一或唯二，持續會想讓自己跟別人一再分享的技術之一。因此，一方面想與大家分享自己再這個領域學習的喜悅，另一方面也希望記錄下自己努力的成果，盼未來的某一天回過頭來看這些文章的積累，會有柳暗花明又一村的感悟。<!--more-->

不過，身為一位初初接觸這個領域的學生，寫程式的經驗也不是太豐富，實在不敢獻醜，因此，這些文章堆的目的絕對不是要傳達多年研究的成果，也不會像學術文章般嚴謹，更無法確保其中的精確性，但我想如果把它定位為學習筆記，我更傾向於用一個數學外行人的角度詳盡的解釋每一個模型推倒的流程，如果你對這個領域有興趣，他應該會更幫助你理解它。

另外，因為仍在續再學習，因此這裡會持續更新自己的學習筆記。

# 何謂資訊檢索
從文件海中尋找出使用者需要的資訊。簡單點，可以想像成google在做的事。我在學習這門課時，自己的感受的是，這個領域主要在...用很酷的數學方法解決數十萬個if以及else。

# 參考書籍
這幾篇文章都是根據正在修習的課程以及[Introduction to Information Retrieval](https://nlp.stanford.edu/IR-book/)上學習而整理出來的一些筆記及心得，這本書寫得很好，教授也很佛心，如果看得懂英文的話，整本都免費可以在網上下載。

# 章節安排
以下所列章節皆直接使用與書上相同的章節號，其中由於本書前半段主要在講如何收集資訊的部分，並不是本堂課程要談的，因此從比較後面的章節開始學習。而在進入這個領域的過程中，首先要學習的大約是，怎麼評價一個檢索系統的好壞，否則根本無法找到本領域追尋的目標，因此第八章首先談到資訊檢索領域中的幾個重要的評價方法。接下來就是三個很酷炫的檢索模型，分別將不同的抽象的數學概念，具體的應用在資訊檢索領域中。其中第六章使用的是向量的概念，第十一章、第十二章都是使用的是機率的概念，不過思路不同、使用的機率模型不同。
- [第八章: 資訊檢索的評價(Evaluation in information retrieval)](/2017/04/22/Evaluation-in-Information-Retrieval/)
- [第六章: 空間向量模型(Vector Space Model)](/2017/04/23/Vector-Space-Model/)
- [第十一章]:機率模型(Probability Model)
- [第十二章]:語言模型(Language Model)
