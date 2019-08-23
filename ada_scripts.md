# Removes inline attribute to help with ADA
```js
var frameborder = setInterval(function () {
$('*[frameborder]').each(function () {
  $(this).css('frameborder', $(this).attr('frameborder'));
  $(this).removeAttr('frameborder');
});
if (!$('*[frameborder]').length) {
  clearInterval(frameborder);
}
}, 500)
$('img').each(function () {
  $(this).css({
    'align': $(this).attr('align'),
    'border': $(this).attr('border'),
    'vspace': $(this).attr('vspace'),
    'hspace': $(this).attr('hspace')
  });
  $(this).removeAttr('align');
  $(this).removeAttr('border');
  $(this).removeAttr('title');
  $(this).removeAttr('vspace');
  $(this).removeAttr('hspace');
});
$('*[border]').each(function () {
  $(this).css('border', $(this).attr('border'));
  $(this).removeAttr('border');
});
$('*[align]').each(function () {
  $(this).css('float', $(this).attr('align'));
  $(this).removeAttr('align');
});
```