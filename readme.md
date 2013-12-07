Плагин jQuery для расстановки переносов в русском тексте при выправке по формату (text-align: justify)
------------

Удобно подключается отдельным плагином/файлом jQuery. Применяется к множеству элементов, автоматически расставляя переносы по всем блокам с русским текстов, к которым применяется плагин.

Применение
------------
`	<script src='js/jquery.js'></script>`

`	<script src='js/jquery.hyphen.ru.js'></script>`

`	<script>`

`		$(function(){`

`			$('p').hyphenate();`

`		});`

`	</script>`


Дискуссия о работе и применении в жизни: http://htmler.ru/2013/12/07/jquery-perenosy-russkogo-teksta/ 

Источник алгоритма расстановки переносов: http://xpoint.ru/know-how/VebAlgoritmyi/RabotaSTekstami/RasstanovkaPerenosov