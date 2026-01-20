{% for cert in site.data.certs %}
  <div class="cert-card">
    <h3>{{ cert.title }}</h3>
    <p>{{ cert.provider }} - {{ cert.instructor }}</p>
    <img src="{{ cert.image }}">
  </div>
{% endfor %}