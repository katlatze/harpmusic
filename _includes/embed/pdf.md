<object
  data="/files/{{page.name | slice: 11, 99 | replace:'.md','.pdf'}}"
  type="application/pdf"
>
  <iframe
    src="https://docs.google.com/viewer?url=https://harp.nebtown.info/files/{{page.name | slice: 11, 99 | replace:'.md','.pdf'}}&embedded=true"
    style="width: 100%; height: 650px"
    frameborder="0"
  ></iframe>
</object>
