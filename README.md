<p align="center">
  <a href="https://newpanjing.github.io/simpleui/">
    <img alt="Simpleui" src="https://github.com/newpanjing/simpleui/raw/master/images/logo.png" width="140">
  </a>
</p>
<p align="center">let Django Admin Simple and friendly，20000+Website common choice</p>
<p align="center">
Simple and friendly.
Django admin theme the simpleui
</p>
<p align="center">
  <a href="https://github.com/newpanjing/simpleui/blob/master/LICENSE"><a href="https://opencollective.com/simpleui" alt="Financial Contributors on Open Collective"><img src="https://opencollective.com/simpleui/all/badge.svg?label=financial+contributors" /></a>
  <a href="https://github.com/newpanjing/simpleui/blob/master/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
  <a href="https://pypi.org/project/django-simpleui/#history"><img src="https://img.shields.io/pypi/v/django-simpleui.svg"></a>
<a href="https://python.org"><img src="https://img.shields.io/badge/python->=3.7.x-green.svg"></a>
<a href="https://pypi.org/project/django-simpleui/">
<img src="https://img.shields.io/pypi/dm/django-simpleui.svg">
</a>
</p>


---
<p align="center">
中文 | <a href="https://newpanjing.github.io/simpleui_docs/en/">English</a>
</p>

---

---
<p align="center">
<a href="https://www.mldoo.com" target="_blank">Community</a> |
<a href="https://newpanjing.github.io/simpleui_docs/" target="_blank">Document</a> |
<a href="https://newpanjing.github.io/simpleui_docs/en/" target="_blank">Documents</a>
</p>
---
<a href="https://www.88cto.com/admin/">
  <img alt="demo" src="https://github.com/newpanjing/simpleui/raw/master/images/%E4%B8%BB%E9%A1%B5.png" width="420" align="right" style="max-width: 50%">
</a>


simpleui Features
-----
👍 Built-in 28 popular themes

⚡️ pip lightning installation is 100% compatible with native admin without modifying the code

✨ Multi-tab pages make each module clearer

🎯 The configuration is simple and quick to get started. After adding simpleui to settings.py, it will take effect immediately and the efficiency will be increased by 100%! Make back-end development easy.

☕️ Element-UI + Vue Blessings make the ancient django admin look brand new.

🦀 Added support for Django3.0, Python3.8, and Python3.9. Dare to be the first to try it out.

# Original intention of development
Django Admin's default interface design language has some shortcomings, such as single color, use of a large number of lines, and obvious segmentation. Classifying these shortcomings is that the interface is monotonous, obvious similarities, and lacks surprises. We believe that the new platform visual style can break these constraints, try some new explorations, and inspire traditional design cognition. Therefore, combined with current design trends, we conceived Element+Django Admin's Simpleui. Let Django Admin and Element interact perfectly. With the most popular backend design style, Django Admin is more powerful.


## QQ group
+ QQ group number: 722755389
+ QQ group number:747695956
+ QQ group number: 873469913 (full)
+ QQ group number: 786576510 (full)

> We recommend asking questions in [Yuandui Community](https://www.mldoo.com) so that you can find them directly if you have questions in the future.


## Professional Edition
> If the free version cannot meet your needs, we also provide a more powerful pro version that can meet more needs

> Provides dozens of custom components + drag-and-drop homepage design and chart design

Demo: [https://www.mldoo.com/demo/simplepro](https://www.mldoo.com/demo/simplepro)

Official website: [https://www.mldoo.com/simplepro](https://www.mldoo.com/docs/simplepro)



## document
The document describes in detail the installation and usage methods, as well as instructions for various configuration items. Please click the link below to view it.
 
 ### Say important things 3 times:

👇👇👇👇👇👇👇👇👇👇👇

👉 1.[simpleui document tutorial instructions](https://simpleui.72wo.com/docs/simpleui) 👈

👉 2.[simpleui document tutorial instructions](https://simpleui.72wo.com/docs/simpleui)👈

👉 3.[simpleui document tutorial instructions](https://simpleui.72wo.com/docs/simpleui)👈

👆👆👆👆👆👆👆👆👆👆👆



## Local Demo download
If you don't have any python django foundation, you can download a demo that can be run directly for experience.
[😝DEMO source code](https://github.com/newpanjing/simpleui_demo)

## Docker
```shell
docker pull newpanjing/simpleui_demo

docker run -p 8080:8080 newpanjing/simpleui_demo
```

After successful startup, visit: http://127.0.0.1:8080

#simpleuiWhat is it?
🚀simpleui is a theme of Django admin. It is developed based on element-ui+vue, and more than 90% of the pages are rewritten and optimized.
It is a similar product to suit. We are a theme that is more in line with Chinese people’s aesthetics and usage habits.

# start using
For detailed steps, please visit [Usage Document](https://newpanjing.github.io/simpleui_docs/config.html). You can also refer to [Demo](#在线Demo)

+ installation
```python
pip install django-simpleui
```

After installing simpleui using pip or [source code method](#clone source code local installation), add `simpleui` to the first line of INSTALLED_APPS in the settings.py file of your project

 For example🌰:
  ```python
    # Application definition

    INSTALLED_APPS = [
        'simpleui',
        'django.contrib.admin',
        'django.contrib.auth',
        'django.contrib.contenttypes',
        'django.contrib.sessions',
        'django.contrib.messages',
        'django.contrib.staticfiles',
        ...
    ]
  ```

If you don’t know how to configure or use it, please download [localdemo](#localDemo下载) to learn. Or join the QQ group: 786576510 for consultation.

#Upgrade simpleui
```python
pip install django-simpleui --upgrade
```

# Clone source code for local installation
```shell
git clone https://github.com/newpanjing/simpleui
cd simpleui
python setup.py sdist install
```

## common problem:

1. If debug mode is turned off, please execute the following command to clone the simpleui static files to the root directory
    ```shell
    python3 manage.py collectstatic
    ```
2. Error cloning static files
Please add: to the settings.py file:
    ```shell
    STATIC_ROOT = os.path.join(BASE_DIR, "static")
    ```
3. For other questions, please refer to [django official documentation](https://docs.djangoproject.com/zh-hans/2.2/).

4. i18n internationalization adopts js internationalization. The default is English and Chinese, which can be switched with the system. For details, please see [Internationalization Configuration](/i18n.md)

For other questions, please check [Quick Start Guide](./QUICK.md)

## Supports django and python versions
[See list of supported versions](/VERSION.md)


## Browser compatibility

![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![IE](https://raw.github.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![UC](https://raw.github.com/alrra/browser-logos/master/src/uc/uc_48x48.png)
:---: | :---: | :---: | :---: | :---: | :---: | :---:
 ✔ |  ✔ |  ✔ |  11+ ✔ |  ✔ |  ✔ | ✔

## README Badge

If your project is using Simpleui, you can add the Simpleui badge [![ice](https://img.shields.io/badge/developing%20with-Simpleui-2077ff.svg)](https://github.com/ newpanjing/simpleui) add to your README:

```
[![simpleui](https://img.shields.io/badge/developing%20with-Simpleui-2077ff.svg)](https://github.com/newpanjing/simpleui)
```


## Sponsorship💰
If you think simpleui is helpful to you, you can sponsor us for a cup of coffee and encourage us to continue development and maintenance.
![Scan QR code to sponsor](https://github.com/newpanjing/simpleui/raw/master/images/pay.png)


# Login page
![](https://github.com/newpanjing/simpleui/raw/master/images/%E7%99%BB%E5%BD%95%E7%95%8C%E9%9D%A2.png)

#Homepage
![](https://github.com/newpanjing/simpleui/raw/master/images/%E4%B8%BB%E9%A1%B5.png)

# List
![](https://github.com/newpanjing/simpleui/raw/master/images/%E5%88%97%E8%A1%A8%E9%A1%B5.png)
![](https://github.com/newpanjing/simpleui/raw/master/images/%E6%95%B0%E6%8D%AE%E9%A1%B5.png)

#Switch theme
![](https://github.com/newpanjing/simpleui/raw/master/images/%E5%88%87%E6%8D%A2%E4%B8%BB%E9%A2%98.png)

# change Password
![](https://github.com/newpanjing/simpleui/raw/master/images/%E5%AF%86%E7%A0%81%E4%BF%AE%E6%94%B9.png)

# Edit page
![](https://github.com/newpanjing/simpleui/raw/master/images/%E7%BC%96%E8%BE%91%E9%A1%B5.png)

# Set font size
![](https://github.com/newpanjing/simpleui/raw/master/images/%E8%AE%BE%E7%BD%AE%E5%AD%97%E4%BD%93%E5%A4 %A7%E5%B0%8F.png)

## Quality Contributor

The development of simpleui cannot be separated from the support of the following outstanding contributors. If you want to contribute code to simpleui, please fork to your own warehouse, then initiate a merge request and merge it into the dev branch.

|Github|Contribution Scope|
|------|------|
|[@Abraverman666](https://github.com/Abraverman666)|Developers|
|[@zhangzhibo1014](https://github.com/zhangzhibo1014)|English document translation|
|[@liaogx](https://github.com/liaogx)|bug fix|
|[@shouyong](https://github.com/shouyong)|bug fix|
|[@Roddy1219](https://github.com/Roddy1219)|bug fix|
|[@WalkerWang731](https://github.com/WalkerWang731)|Quality code contribution|
|[@Beginner](https://www.seejoke.com)|223450427@qq.com, top technical consultant|
  

<a href="https://github.com/newpanjing/simpleui/contributors"><img src="https://opencollective.com/simpleui/contributors.svg?width=890&button=false"></a>

# Acknowledgments
Development tools Pycharm sponsored by [Jetbrains](https://www.jetbrains.com/)
