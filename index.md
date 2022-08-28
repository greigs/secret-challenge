<style>
  footer {
    display: none;
  }
</style>

{% assign now = site.time | date_to_string %}
{% assign show = "30 Aug 2022" %}
{% if show == now %}
  <center><span><img src="https://upload.wikimedia.org/wikipedia/commons/5/53/Pok%C3%A9_Ball_icon.svg" width="100"/>
  <img src="https://d1nxzqpcg2bym0.cloudfront.net/google_play/com.Firecannon.PokeCam/523d34a4-1c3d-11e7-851a-71a6ed7a07bd/128x128" width="100"/>
  </span></center>
  - **The codes are 473 and 471**
  - **More information here**
{% else %}  
  **Return here on Your Special Day at 17:00 and refresh the page for further instructions.**
{% endif %}
