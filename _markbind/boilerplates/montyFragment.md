<div class="indented-level2">
<panel type="info" {{ status }} no-close >
{% set displacement="" %}
<div slot="header" class="text-white">Programming {{ icon_embedding }}&nbsp;&nbsp;<md>{{ header }}</md> <span class="badge badge-pill badge-warning">{{ tag }}</span></div>
{% set displacement=".." %}
<include src="{{ displacement }}/programming/monty/{{ fragment }}" />
</panel>
</div>
