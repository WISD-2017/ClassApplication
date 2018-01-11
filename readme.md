<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## 關於 教室申請系統-ClassroomApplication

使用者可以透過申請表單預先上網登記想要借用的教室，並且可以瀏覽每間教室的借用情形及管理自己的教室申請。<p>
而管理者可以審核使用者的申請，並且記錄各教室借用的歷史紀錄。

## 如何復原 教室申請系統-ClassroomApplication

1.開啟Cmder.exe<p>
2.cd ClassApplication<p>
3.composer install –no-scripts <p>
4.composer run‐script post‐root‐package‐install <p>
5.composer run‐script post‐install‐cmd <p>
6.composer run‐script post‐create‐project‐cmd <p>

## 使用者

1.Clone下來後，.env檔內的<p>
   DB_DATABASE=ClassApplication<p>
   DB_USERNAME=root<p>
   DB_PASSWORD=root<p>
2.確認資料庫已經有正常運作<p>
3.如果有會員可以直接登入，若無，則要透過註冊按鈕進行註冊<p>
4.進入系統後，可以瀏覽教室借用情形，如果想要預借教室則可點選「申請」進行租借。<p>
5.申請後，點選「申請管理」，可以瀏覽教室申請審核狀況且可以自行點選取消即刪除該申請。<p>

## 管理者

1.點選「審核申請」即可看到使用者的教室申請，並且審核通過或審核不通過。<p>
2.點選「教室狀態」即可看到每間教室曾經被哪位使用者所借用及審核狀態。<p>
3.點選「歷史紀錄」即可看到哪間教室曾經被哪位使用者所借用及審核狀態。<p>

## 組員

[四資三乙 3A432058 陳欣妤](https://github.com/s3A432058)<p>
[四資三乙 3A432090 陳美妤](https://github.com/s3A432090)<p>

