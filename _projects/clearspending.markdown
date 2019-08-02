---
layout: page

title:  Госзатраты
link: https://clearspending.ru

logo: cs-logo.png
screenshot: cs-preview.png

date: 2019-08-01 11:23:26 +0300
position: 1
---

2014 – по н.в.

Cайт проекта «Госзатраты», на котором публикуются закупки, контракты, данные о поставщиках и заказчиках, доступны ежедневные дампы базы данных и ссылки на API). Имеет раздел sub.clearspending.ru — спецпроект «Субсидии», содержащий данные о субсидиях из федерального бюджета, распределителях и получателях.

![page.title]({{site.baseurl}}/uploads/{{page.screenshot}})

#### Технологии

Python, Django, Django CMS, d3js

#### Сервисы

- телеграм-бот @csParticipantStatsBot — делится статистикой госзаказа организации по ИНН;
- телегам-бот @csDownloaderBot — формирует выборку контрактов по необходимым вам фильтрам;
- телеграм-канал @clearspending — каждый день присылает три самых крупных контракта по отраслям и оповещает, если в базе появляются очень крупные контракты;
- [расширение для браузера Google Chrome](http://bit.ly/clearspending_ext) — позволяет по сайту организации просматривать статистику ее участия в госзаказе.


<div class="text-center py-5">
	<a href="{{page.link}}" target="_blank" class="btn btn-cyan btn-lg">Перейти на сайт «{{page.title}}» <i class="fas fa-arrow-right pl-2"></i></a>
</div>