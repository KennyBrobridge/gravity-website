---
title: 讀寫分離的資料庫擴展挑戰
---

以往使用資料庫系統的複寫技術（Replication）進行多資料副本，通常需要依賴搭建主從架構（Master-Slave）的叢集機制，這為管理者和開發者帶來許多困難，除了搭建複雜困難之外，維護上也相當不易。如果未來有資料庫規模擴展的需要，傳統叢集的設定和操作更是一大麻煩。這導致大多數企業為降低風險，都會盡量避免去碰觸、擴充資料庫叢集系統，資料庫的改造和擴充，相當沒有效率。

毫無疑問，面對更大量應用的資料需求、更巨量的查詢需求，其資料庫系統的擴展彈性，便會是數位轉型的關鍵瓶頸。

### 以 GRAVITY 幾分鐘內實現讀寫分離

建立多個資料庫副本，以提高查詢能力，是讀寫分離的核心運作機制。採用 GRAVITY 來實現讀寫分離，無需侵入既有應用程式架構，更不用介入資料庫系統叢集的設定和設計，只需要幾個動作，搭配簡單的設定就可以快速動態搭建完成。未來想要增減資料副本數量，也非常容易和快速，滿足應用臨時的各種資料需求。


