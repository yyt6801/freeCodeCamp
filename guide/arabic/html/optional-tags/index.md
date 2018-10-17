---
title: Optional Tags
localeTitle: علامات اختيارية
---
## علامات HTML5 الاختيارية

في HTML5 ، يمكنك تجاهل بعض علامات الفتح والإغلاق تحت شروط معينة. على سبيل المثال ، كود HTML التالي ...

 `
<!DOCTYPE html> 
 <p>Hello World. 
` 

سوف تقيم تلقائيا إلى ...

 `
<!DOCTYPE html> 
 <html> 
  <head></head> 
  <body> 
    <p>Hello world. 
    </p> 
  </body> 
 </html> 
` 

مواصفات العلامة الاختيارية لعلامات HTML5 الأكثر شيوعًا هي كالتالي:

*   قد يتم حذف علامة بدء عنصر `html` إذا كان أول شيء داخل عنصر `html` ليس تعليقًا.
*   قد يتم حذف علامة نهاية عنصر `html` إذا لم يتبع عنصر `html` مباشرة تعليق.
*   قد يتم حذف علامة بدء عنصر `head` إذا كان العنصر فارغًا ، أو إذا كان العنصر الأول داخل عنصر `head` عنصرًا.
*   قد يتم حذف علامة نهاية عنصر `head` إذا لم يتبع عنصر `head` مباشرة حرف مسافة أو تعليق.
*   A `body` قد تكون أغفلت وسم بداية العنصر إذا كان العنصر فارغ، أو إذا كان أول شيء داخل `body` العنصر ليس حرف مسافة أو تعليق، إلا إذا كان أول شيء داخل `body` العنصر هو `meta` ، `link` ، `script` ، `style` ، أو عنصر `template` .
*   A `body` يمكن حذف علامة النهاية العنصر إذا لم يتبع العنصر الأساسي على الفور تعليق.

### معلومات اكثر

لمعرفة المزيد حول علامات HTML5 الاختيارية ، يرجى زيارة ![توصيات World Wide Web Consortium](https://www.w3.org/TR/html5/syntax.html#optional-tags) .