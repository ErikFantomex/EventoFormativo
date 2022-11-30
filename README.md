# EventoFormativo
#markdown template Elearning
# {% load markdown_deux_tags %}
# {% load course %}
# {% load bootstrap4 %}
# {% load crispy_forms_tags %}
# {% load static %}
# {% load i18n %}
# 
# {% block body %}
# <div class="container">
# <div class="row">
# <div class="col-md-4">
#     <div class="card">
#         <div class="card-header">
#             <h5 class="card-title">{{ course.title }}</h5>
#         </div>
#         <div class="card-body">
#             <p class="card-text">{{ course.overview|markdown }}</p>
#             <p class="card-text">
#                 <small class="text-muted
