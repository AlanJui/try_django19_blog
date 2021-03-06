![Try Django 1.9 Logo](https://cfe-static.s3.amazonaws.com/media/try-django-19/images/try_django_19.png)

# Try Django 1.9 習作

### 課程來源
 - [YouTube 網站](http://joincfe.com/youtube) 
 - [Coding for Entrepreneurs](http://joincfe.com/projects/)

### 學習目標

 - 如何在 Blog 中顯示 HTML，  Markdown 輸出
 - 在 Post 編輯，導入如：Stack Overflow 樣式之 Markdown Editor 功能（Django Pagedown） 


### 專案摘要

以 Django 1.9 為基礎，透過：「開發 Blog 系統」為目標，學習進階 Django 技術。


## 操作指引

### 虛擬環境

```
	$ workon django_19
```

### 安裝專案所需套件
```
	$ pip freeze
	$ pip install -r requirements.txt
```

### 設定 Model 與專案所需資料庫
```
	$ cd src
	$ ./manage.py migrate
	$ ./manage.py createsuperuser
```

### 啟動Web伺服器
```
	$ ./manage.py runserver
```	