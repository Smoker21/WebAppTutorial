# 開始專案

本章介紹如何開始一個新的專案。這個專案的 Technology stack 採用 Spring starter project 為基礎，但是因為環境上的限制，無法使用 Spring boot，而必須部署在 Tomcat 上。專案會分成三個模組


| Project Name | Purpose |
| -- | -- |
| Starter-Parent | 作為 Parent 專案，是 Maven project 的 container  |
| Starter-Util   | 作為 Utility 專案，主要放置一些常用的 Utility 程式 (Optional) |
| Starter-Core   | 核心模組，主要放置 JPA Entity, Service, Repository, Repository Handle |
| Starter-Web    | Web 模組，主要處理 REST 呼叫，HATEOAS API 處理, Web Service, Spring MVC 等 |


本教學內容需要熟悉, Spring framework, Java, Database SQL 等後台知識。前台使用 Bootstrap + JSP.
 Ajax 部分採用 Ext Js.