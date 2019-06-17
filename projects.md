---
layout: page-full
menu: true
menu_order: 3

title: Проекты
permalink: /projects/
---

<div class="row justify-content-center">


  <div class="col-8 mb-4">
    <p>Здесь какой-то текст с кратким описанием. Тут что-то про компанию, здесь ещё что-то, там про данные, здесь про третье, здесь про десятое, и так далее. Ну вы поняли.</p>
  </div>


  <div class="col-12">
    <div class="card-columns text-dark">
      {% for project in site.projects %}
      <a href="{{site.baseurl}}{{project.url}}" class="card p-3 mb-4 text-dark">
        <div class="card-body">
          {% if project.logo %}<img src="{{site.baseurl}}/img/{{project.logo}}" alt="{{project.title}}" class="mb-3" height="80">{% endif %}
          <h3>{{project.title}}</h3>
          <p class="mb-0">{{project.description}}</p>
        </div>
      </a>
      {% endfor %}
    </div>
  </div>


</div>
