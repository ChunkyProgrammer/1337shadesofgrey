---
layout: default
---

<div class="absolute right-0 mr-6">
  <a class="text-blue-400 underline" href="/">en</a>
  <a class="text-blue-400 underline" href="/pt">pt</a>
  <a class="text-blue-400 underline" href="/cn">cn</a>
  <a class="text-blue-400 underline" href="/ru">ru</a>
</div>

<h1 class="text-3xl font-extrabold text-transparent bg-clip-text bg-gradient-to-br from-chestnut-200 to-beaver-500 text-center mt-6">
  {% t header_title %}
</h1>

<p class="text-center my-10">
</p>

<div class="container max-w-5xl mx-auto mb-8 px-4">
  <div class="flex flex-col sm:flex-row justify-center mt-6">
    <img class="border-solid border-4 border-white mx-auto sm:m-0" src="{% t cover_file %}" style="width: 350px">
    <div class="ml-2 mt-2">
      <p>
        <b>{% t author_label %}:</b> {% t author_value %}
      </p>
      <p>
        <b>{% t country_label %}:</b> {% t country_value %}
      </p>
      <p>
        <b>{% t language_label %}:</b> {% t language_value %}
      </p>
      <p>
        <b>{% t series_label %}:</b> {% t series_value %}
      </p>
      <p>
        <b>{% t genre_label %}:</b> {% t genre_value %}
      </p>
      <p>
        <b>{% t media_type_label %}:</b> {% t media_type_value %}
      </p>
    </div>
  </div>

  <h2 class="text-xl font-extrabold text-transparent bg-clip-text bg-gradient-to-br from-chestnut-200 to-beaver-500 text-center my-6">
    {% t about_title %}
  </h2>

  <p class="my-2">
    {% t about_text %}
  </p>

  <h2 class="text-xl font-extrabold text-transparent bg-clip-text bg-gradient-to-br from-chestnut-200 to-beaver-500 text-center my-6">
    {% t content_title %}
  </h2>

  <p class="my-2">
    {% t content_paragraph_1 %}
  </p>

  <p class="my-2">
    {% t content_paragraph_2 %}
  </p>

</div>
