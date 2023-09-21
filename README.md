# window-object

- alert() - показывает диалоговое окно 
- atob() - декодирует строку данных
- blur() - вызывается когда элемент теряет фокус
- btoa() - кодирует строку данных
- cancelAnimationFrame() - останавливает анимацию, запланированную с помощью window.requestAnimationFrame().
- cancelIdleCallback() - отменяет обратный вызов, ранее запланированный с помощью window.requestIdleCallback().
- captureEvents() - этот метод давно удален из спецификации
- chrome
- clearInterval() - отменяет повторяющееся действие по времени, которое ранее было установлено вызовом setInterval()
- clearTimeout() - отменяет таймаут, ранее установленный вызовом setTimeout().
- clientInformation:Navigator
- close() - закрывает текущее окно или окно, которое было открыто с помощью функции Window.open().
- confirm() - отображает диалоговое окно, которое содержит две кнопки (OK и Cancel)
- createImageBitmap() - представляет собой bitmap изображение которое может быть нарисовано на <canvas>
- Crypto {} Window.crypto - даёт доступ к интерфейсу Crypto. Этот интерфейс предоставляет веб-странице доступ к встроенным в браузер возможностям криптографии.
- CustomElementRegistry {}
- document - каждая веб-страница, которая загружается в браузер, имеет свой собственный объект
- External {}
- fetch() - запускает процесс извлечения ресурса из сети
- find() - возвращает значение первого найденного в массиве элемента
- focus() - делает запрос на перенос окна на передний план
- Window - объект window представляет собой окно, содержащее DOM документ
- getComputedStyle() - возвращает объект, содержащий значения всех CSS-свойств элемента
- getSelection() - возвращает объект Selection, представленный в виде диапазона текста, который пользователь выделил на странице.
- History - интерфейс позволяет манипулировать историей браузера
- IDBFactory {} - используется для открытия базы данных IndexedDB
- innerHeight - возвращает внутреннюю высоту окна в пикселях
- innerWidth - свойвойство только для чтения innerWidth возвращает внутреннюю ширину окна в пикселях.
- isSecureContext - позволяет вам определить, выполняется ли текущий JavaScript код в безопасном контексте (secure context) или нет. 
- launchQueue
- LaunchQueue {}
- length
- localStorage - данные, находящиеся в свойстве localStorage, не имеют ограничений по времени хранения и могут быть удалены только с помощью JavaScript.
- Location - возвращает объект Location с информацией о текущем расположении документа.
- locationbar - было устаревшим и больше не поддерживается, а использовать объект window.location
- matchMedia() - медиазапрос в js
- menubar - устаревшая функциональность, и ее использование не рекомендуется. 
- moveBy() - может не работать во всех браузерах из-за ограничений безопасности и политик перемещения окон браузера. 
- moveTo() 
- Navigation - позволяет контролировать все текущие действия навигации 
- Navigator - представляет собой состояние и особенности(свойства) пользовательского агента.
    Navigator и Navigation - это два различных объекта, связанных с веб-браузером, но имеющих разные назначения и функции   
- onabort - Обработчик событий, позволяющий прерывать события объекта window. (Недоступен для Firefox 2 и Safari).
- onafterprint  - страница завершает вывод на печать
- onanimationend - событие вызывается когда CSS-анимация достигает конца своего активного периода
- onanimationiteration
- onanimationstart
- onappinstalled
- onauxclick
- onbeforeinput
- onbeforeinstallprompt
- onbeforematch
- onbeforeprint
- onbeforetoggle
- onbeforeunload - Событие вызывается перед удалением события из окна
- onbeforexrselect
- onblur - Свойство обработчика событий для исчезновение фокуса на окне.
- oncancel
- oncanplay
- oncanplaythrough
- onchange - является одним из событийных обработчиков в JavaScript и используется для отслеживания изменений в элементах формы HTML, таких как элементы <input>, <select> и <textarea>. Когда пользователь взаимодействует с таким элементом и вносит изменения, событие onchange срабатывает, и соответствующая функция или обработчик выполняется.
- onclick - возвращает обработчик события click на текущем элементе.
- ondblclick - возникает при двойном щелчке кнопки указывающего устройства
- onclose - Свойство обработчика событий для обработки закрытия окна
- oncontentvisibilityautostatechange
- oncontextlost
- oncontextmenu - Свойство обработчика событий для правого клика в окне.
- oncontextrestored
- oncuechange
- ondrag - событие, которое срабатывает при перемещении элемента на веб-странице (drag-and-drop)
- ondragend - событие, которое возникает в JavaScript при завершении операции перетаскивания (drag-and-drop) элемента на веб-странице
- ondragenter - событие, которое возникает в JavaScript при входе перетаскиваемого элемента в область элемента на веб-странице. 
- ondragleave - событие, которое возникает в JavaScript при выходе перетаскиваемого элемента из области элемента на веб-странице.
- ondragover - когда перетаскиваемый элемент находится над областью элемента на веб-странице. 
- ondragstart - событие, которое возникает в JavaScript при начале операции перетаскивания (drag-and-drop) элемента на веб-странице.
- ondrop - событие, которое возникает в JavaScript при броске (drop) перетаскиваемого элемента на целевой элемент на веб-странице. 
- ondurationchange - событие в JavaScript, которое возникает в объекте <audio> или <video> HTML, когда изменяется длительность медиа-файла (аудио или видео). Это событие срабатывает, когда браузер определяет точную длительность медиа-файла, что может произойти после начала воспроизведения.
- onemptied - событие, которое возникает в JavaScript при смене источника мультимедийного элемента (как правило, <audio> или <video>) на веб-странице. Это событие срабатывает, когда текущий источник медиа-файла обнуляется или удаляется, и элемент готовится к загрузке нового медиа-файла.
- onended - событие, которое возникает в JavaScript при завершении воспроизведения аудио или видео на веб-странице.
- onerror - событие, которое возникает в JavaScript, когда происходит ошибка при загрузке или выполнении какого-либо ресурса на веб-странице, такого как изображение, скрипт, стиль, аудио, видео и другие элементы.
- onfocus - событие в JavaScript, которое возникает при получении элементом фокуса. 
- onformdata - событие, которое возникает при отправке формы с использованием API FormData. При использовании этого API форма отправляется асинхронно без обновления всей страницы, и событие onformdata срабатывает в момент отправки данных формы.
- ongotpointercapture - событие, которое возникает в JavaScript при захвате событий указателя (например, прикосновений к сенсорному экрану или движения мыши) с помощью метода setPointerCapture() на элементе DOM. 
- onhashchange - событие, которое возникает в JavaScript при изменении фрагмента (hash) в URL-адресе веб-страницы.
- oninput - событие в JavaScript, которое возникает при вводе или изменении значения элемента ввода, такого как текстовое поле (<input type="text">) или текстовая область (<textarea>). Это событие срабатывает в реальном времени при каждом изменении содержимого элемента.
- oninvalid  - событие, которое возникает в JavaScript при попытке отправки формы, когда одно или несколько полей ввода не прошли валидацию, заданную с помощью атрибутов HTML5, таких как required, pattern, min, max, и других. Это событие срабатывает на элементах input, select и textarea, когда браузер не позволяет отправить форму из-за некорректных данных.
- onkeydown - машина была в аресте на зсу не снята с розшуку зобовязання вдвс зняття розшуку 
- onkeypress - событие в JavaScript, которое возникает при нажатии клавиши на клавиатуре в момент, когда клавиша находится в нажатом состоянии. Это событие срабатывает при каждом нажатии клавиши на клавиатуре и может быть использовано для обработки ввода текста или выполнения других действий в ответ на нажатия клавиш.
- onkeyup  - событие в JavaScript, которое возникает после отпускания клавиши на клавиатуре, когда клавиша переходит из нажатого состояния в исходное состояние. Это событие срабатывает при каждом отпускании клавиши на клавиатуре и может быть использовано для обработки ввода текста, выполнения действий при отпускании определенных клавиш или для других сценариев.
- onlanguagechange - Свойство обработчика событий для события languagechange (en-US) в окне.
- onload - Событие load происходит когда ресурс и его зависимые ресурсы закончили загружаться.
- onloadeddata - это событие в JavaScript, которое возникает на элементах <audio> и <video> веб-страницы, когда браузер успешно загружает начальные данные медиа-файла и готов начать его воспроизведение.
- onloadedmetadata - событие в JavaScript, которое возникает на элементах <audio> и <video> веб-страницы, когда браузер успешно загружает метаданные медиа-файла. Метаданные медиа-файла включают информацию, такую как длительность, размер, разрешение и другие характеристики файла.
- onloadstart - событие в JavaScript, которое возникает на различных элементах, таких как изображения (<img>), аудио (<audio>), видео (<video>) и других, когда начинается загрузка контента с сервера.
- onlostpointercapture - событие в JavaScript, которое возникает на элементах DOM, когда элемент теряет захват указателя (pointer capture).
- onmessage - событие в JavaScript, которое возникает в объекте Window, Worker, MessagePort или SharedWorker при получении сообщения от другого окна, рабочего потока или порта внутри веб-приложения. Это событие используется для обмена данными и сообщениями между различными частями вашего веб-приложения, работающими в разных контекстах.
- onmessageerror - событие, которое возникает в JavaScript при возникновении ошибки во время обработки сообщения, полученного с помощью события message (событие onmessage). Это событие позволяет обнаруживать и обрабатывать ошибки, которые могут возникнуть при приеме и обработке сообщений между окнами или фреймами в веб-приложении.
- onmousedown - событие в JavaScript, которое возникает при нажатии (нажатии и удержании) кнопки мыши над элементом веб-страницы.
onmouseenter - является событием мыши в веб-разработке, которое срабатывает, когда указатель мыши входит в определенный элемент на веб-странице. Это событие подразумевает, что указатель мыши пересек границу элемента и вошел в его область. 
- onmouseleave - является еще одним событием мыши в веб-разработке. Оно срабатывает, когда указатель мыши покидает область определенного элемента на веб-странице. 
- onmousemove - является событием мыши в веб-разработке, которое срабатывает при движении указателя мыши внутри определенного элемента на веб-странице. Это событие позволяет отслеживать движение мыши и реагировать на него, например, для создания интерактивных элементов, отслеживания позиции мыши или реализации функций, зависящих от положения указателя мыши.
- onmouseout - является событием мыши в веб-разработке, которое срабатывает, когда указатель мыши покидает определенный элемент на веб-странице. 
- onmouseover - является событием мыши в веб-разработке, которое срабатывает, когда указатель мыши наводится на определенный элемент на веб-странице. Это событие возникает, когда указатель мыши пересекает границу элемента и входит в его область. Событие onmouseover часто используется для создания интерактивных элементов на веб-странице, например, для изменения внешнего вида элемента или выполнения каких-либо действий при наведении мыши.
- onmouseup - является событием мыши в веб-разработке, которое срабатывает, когда пользователь отпускает кнопку мыши после нажатия на неё. Это событие позволяет отслеживать момент, когда кнопка мыши была отпущена.
- onmousewheel  - для обработки прокрутки колеса мыши в веб-разработке. Оно срабатывало, когда пользователь прокручивал колесо мыши внутри элемента на веб-странице, позволяя выполнять действия, связанные с этой прокруткой.
- onoffline - событие веб-браузера, которое срабатывает, когда состояние сети меняется с "онлайн" на "оффлайн" или наоборот. Это событие позволяет веб-приложениям и веб-сайтам реагировать на изменения доступности сети и принимать соответствующие меры.
- ononline - событие веб-браузера, которое срабатывает, когда состояние сети переходит из "оффлайн" в "онлайн". Оно позволяет веб-приложениям и веб-сайтам реагировать на восстановление доступности сети и выполнять соответствующие действия.
- onpagehide  - является событием веб-браузера и срабатывает, когда пользователь покидает текущую веб-страницу или закрывает вкладку, на которой она открыта. Это событие может быть использовано для выполнения определенных действий перед тем, как страница закроется или будет перезагружена.
- onpageshow - рабатывает, когда веб-страница становится видимой для пользователя, например, когда она загружается или возвращается из кэша браузера. Это событие может быть использовано для выполнения действий при отображении страницы.
- onpause - является событием мультимедийных элементов в HTML, таких как <audio> и <video>. Оно срабатывает, когда воспроизведение медиа-элемента приостанавливается, например, когда пользователь нажимает на кнопку паузы или когда медиа-элемент завершает воспроизведение.
- onplay  - является событием мультимедийных элементов в HTML, таких как <audio> и <video>. Оно срабатывает, когда воспроизведение медиа-элемента приостанавливается
- onplaying - является событием мультимедийных элементов в HTML, таких как <audio> и <video>. Это событие срабатывает, когда воспроизведение медиа-элемента возобновляется после паузы или когда воспроизведение начинается после загрузки медиа-файла и подготовки к воспроизведению.
- onpointercancel - срабатывает, когда браузер отменяет событие указателя (pointer event). Событие pointercancel может возникнуть по разным причинам, например, когда жесты с мультитач-сенсоров были прерваны, или браузер решает отменить событие указателя по какой-либо другой причине.
- onpointerdown - срабатывает, когда пользователь начинает нажимать на устройство ввода (например, экран сенсорного устройства или мышь). Это событие представляет начало взаимодействия с указателем и может использоваться для отслеживания момента начала клика, нажатия или касания.
- onpointerenter - срабатывает, когда указатель (например, палец на сенсорном устройстве или указатель мыши) входит в область элемента. Это событие предоставляет возможность реагировать на вход указателя в область элемента.
- onpointerleave - срабатывает, когда указатель (например, палец на сенсорном устройстве или указатель мыши) покидает область элемента. Это событие предоставляет возможность реагировать на выход указателя из области элемента.
- onpointermove - срабатывает, когда указатель (например, палец на сенсорном устройстве или указатель мыши) двигается внутри элемента. Это событие предоставляет возможность отслеживать движение указателя внутри определенной области и реагировать на это движение.
- onpointerout - срабатывает, когда указатель (например, палец на сенсорном устройстве или указатель мыши) двигается внутри элемента. Это событие предоставляет возможность отслеживать движение указателя внутри определенной области и реагировать на это движение.
- onpointerover - срабатывает, когда указатель (например, палец на сенсорном устройстве или указатель мыши) входит в область элемента, то есть перемещается снаружи элемента внутрь.
- onpointerrawupdate - может быть реализовано и использовано в специфических ситуациях, где требуется более низкоуровневый доступ к данным о событиях указателя.
- onpointerup - срабатывает, когда пользователь отпускает указатель (например, отпускает кнопку мыши или палец с сенсорного экрана) после выполнения действия, такого как клик или касание.
- onpopstate - срабатывает, когда пользователь выполняет навигацию в истории браузера, в частности, при нажатии кнопок "Назад" и "Вперед" или при изменении URL через JavaScript.
- onprogress  - является событием в веб-разработке, которое связано с загрузкой ресурсов, таких как изображения, аудио- и видеофайлы, стили CSS и другие элементы, которые могут быть загружены на веб-странице. Это событие срабатывает, когда браузер получает данные о ходе выполнения загрузки указанного ресурса.
- onratechange  - является одним из событий, которые могут использоваться в JavaScript для обработки изменений в скорости воспроизведения мультимедийных элементов, таких как аудио или видео. Это событие срабатывает, когда пользователь изменяет скорость воспроизведения мультимедийного контента.
- onrejectionhandled  - событие, которое возникает в контексте использования JavaScript Promise (обещаний). Оно срабатывает, когда обещание (Promise) было отклонено (rejected), но затем было успешно обработано (handled). Обещание может быть отклонено, когда возникает ошибка в асинхронной операции, и код обработчика ошибок (.catch() или второй аргумент .then()) используется для обработки этой ошибки.
- onreset - является событием HTML и JavaScript, которое срабатывает при сбросе (reset) формы на веб-странице. Формы на веб-странице могут содержать элементы ввода, такие как текстовые поля, чекбоксы, радиокнопки и другие, и с помощью кнопки "Сброс" (обычно представленной в виде <input type="reset">), пользователь может сбросить введенные данные в форме к их начальным значениям.
- onresize - является событием веб-браузера, которое срабатывает, когда пользователь изменяет размер окна браузера или когда изменяется размер элемента DOM.
onscroll  - является событием веб-браузера, которое срабатывает при прокрутке содержимого элемента или окна браузера. Это событие позволяет отслеживать изменения положения прокрутки и выполнять определенные действия при прокрутке веб-страницы или элемента.
- onscrollend - не является стандартным событием веб-браузера или JavaScript. Вероятно, вы путаете его с событием scroll или scrollend, которые более распространены и используются для отслеживания прокрутки элементов или окна браузера.
- onsearch - является событием HTML и JavaScript, которое срабатывает при выполнении поиска в поле ввода типа "search" (<input type="search">) на веб-странице. Это событие позволяет реагировать на действия пользователя, связанные с поиском информации.
- onsecuritypolicyviolation  - является частью спецификации Content Security Policy (CSP) и срабатывает, когда браузер обнаруживает нарушение политики безопасности контента (CSP) на веб-странице. CSP - это набор правил, которые определяют, какой контент и источники могут быть загружены и выполнены на веб-странице. Эти правила помогают предотвратить атаки, такие как внедрение кода (например, атаки XSS) и другие безопасностные угрозы.
- onseeked - является частью спецификации Content Security Policy (CSP) и срабатывает, когда браузер обнаруживает нарушение политики безопасности контента (CSP) на веб-странице. CSP - это набор правил, которые определяют, какой контент и источники могут быть загружены и выполнены на веб-странице. Эти правила помогают предотвратить атаки, такие как внедрение кода (например, атаки XSS) и другие безопасностные угрозы.
- onseeking  - является одним из событий HTML5 Media Element и происходит, когда происходит начало поиска (seek) в медиаэлементе, таком как <audio> или <video>. Поиск (seeking) в данном контексте означает изменение текущей позиции воспроизведения медиафайла на указанное место (обычно определенное пользователем) внутри медиаэлемента.
- onselect - является событием HTML и JavaScript, которое срабатывает при выделении текста в элементе формы, который поддерживает выделение, такой как текстовое поле (<input type="text">) или текстовая область (<textarea>).
- onselectionchange - не является стандартным событием HTML или JavaScript. Если вам нужно отслеживать изменения в выделении (выбранном тексте) на веб-странице, вам, возможно, придется использовать другие события и методы.
- onselectstart  - является событием HTML и JavaScript, которое срабатывает при попытке начать выделение текста или элементов на веб-странице с помощью мыши. Это событие может быть использовано для предотвращения начала выделения определенных элементов или для выполнения дополнительных действий при начале выделения.
- onslotchange
- onstalled
- onstorage - является устаревшим и больше не рекомендуется к использованию в современных веб-приложениях. Это событие ранее использовалось для отслеживания изменений в объекте - window.localStorage, который позволяет веб-приложениям сохранять данные на стороне клиента (в локальном хранилище).
- onsubmit - Обработчик события отправки формы
- onsuspend - одно из событий, связанных с мультимедийными элементами, такими как <audio> и <video>
- ontimeupdate - это событие мультимедийных элементов, таких как <audio> и <video>, в HTML и JavaScript. Это событие возникает в течение воспроизведения мультимедийного контента, когда текущее время (прогресс) воспроизведения изменяется.
- ontoggle - не является стандартным событием
- ontransitioncancel - не является стандартным событием в веб-разработке на данный момент (по состоянию на сентябрь 2021 года), и оно не поддерживается непосредственно браузерами.
- ontransitionend - событие, которое возникает в CSS-анимации и анимации перехода (CSS transitions). Это событие срабатывает, когда завершается анимация перехода для элемента.
- ontransitionrun  - связано с CSS-анимациями и анимациями перехода (CSS transitions). Это событие возникает, когда начинается выполнение анимации перехода для элемента, то есть в момент, когда анимация фактически начинает свое выполнение.
- ontransitionstart  - связано с CSS-анимациями и анимациями перехода (CSS transitions). Это событие возникает, когда начинается выполнение анимации перехода для элемента, то есть в момент, когда анимация фактически начинает свое выполнение.
- onunhandledrejection - событие, которое возникает в JavaScript, когда обещание (Promise) было отклонено (rejected), и исключение (ошибка) из этого отклоненного обещания не было обработано (не был вызван метод .catch() или добавлен обработчик события unhandledrejection).
- onunload  - событие в JavaScript, которое возникает, когда пользователь покидает текущую веб-страницу. Это событие может использоваться для выполнения дополнительных действий перед тем, как страница будет закрыта или перенаправлена на другой URL.
- onvolumechange  - событие, которое возникает при изменении уровня громкости мультимедийного элемента, такого как <audio> или <video>, в HTML и JavaScript. Это событие срабатывает, когда пользователь изменяет громкость воспроизведения мультимедийного контента, либо программно изменяется уровень громкости через JavaScript.
- onwaiting - событие, которое возникает при приостановке воспроизведения мультимедийного элемента, такого как <audio> или <video>, в HTML и JavaScript. Это событие срабатывает, когда воспроизведение приостанавливается временно, например, из-за буферизации данных или ожидания загрузки контента.
- onwebkitanimationend - событие, связанное с анимациями в веб-разработке, которое возникает веб-кит (WebKit) браузерах, таких как Safari и старых версиях Chrome. Это событие срабатывает, когда CSS-анимация, примененная к элементу, завершается.
- onwebkitanimationiteration - является частью API WebKit, которое использовалось в старых версиях браузерах, таких как Safari и старых версиях Chrome, для отслеживания момента завершения одного цикла анимации (итерации) CSS. Это событие срабатывало каждый раз, когда анимация завершала одну итерацию и начинала следующую.
- onwebkitanimationstart - событие, которое возникало в старых версиях браузеров на основе WebKit (таких как Safari и старых версиях Chrome) для отслеживания начала анимации CSS.
- onwebkittransitionend - событие, которое возникало в старых версиях браузеров на основе WebKit (таких как Safari и старых версиях Chrome) для отслеживания завершения анимаций перехода (CSS transitions).
- onwheel - событие, которое возникает при вращении колесика мыши (скроллинге) над элементом на веб-странице. Это событие может быть использовано для отслеживания действий пользователя, связанных с колесиком мыши, такими как прокрутка страницы или изменение каких-либо значений.
- open() - методом объекта Window или объекта XMLHttpRequest, который используется в JavaScript для выполнения определенных действий.
- window.open(): - Этот метод используется для открытия нового окна браузера или вкладки (в зависимости от настроек браузера) с указанным URL-адресом.
- openDatabase()
- opener - это объект, который представляет родительское окно или вкладку браузера, из которой было открыто текущее окно или вкладка с помощью функции window.open() 
- originAgentCluster
- outerHeight - используется для получения высоты (в пикселях) окна браузера, включая все его элементы интерфейса, такие как панель инструментов, адресную строку, закладки и прокрутку (если такие элементы видимы и доступны).
- outerWidth - используется для получения ширины (в пикселях) окна браузера, включая все его элементы интерфейса, такие как панель инструментов, адресную строку, закладки и прокрутку (если такие элементы видимы и доступны).
- pageXOffset - является частью объекта window в JavaScript и используется для получения горизонтальной (горизонтальной) позиции прокрутки (scroll) текущей веб-страницы относительно начала документа. Оно предоставляет количество пикселей, на которое страница была прокручена по горизонтали слева.
- pageYOffset - используется для получения вертикальной (вертикальной) позиции прокрутки (scroll) текущей веб-страницы относительно начала документа. Оно предоставляет количество пикселей, на которое страница была прокручена по вертикали сверху.
- parent - Ссылка на родительский объект window или родительский iframe. Это свойство используется для доступа и взаимодействия с родительским окном или фреймом из окна или фрейма, находящегося внутри него.
- performance - представляет собой интерфейс для доступа к информации о производительности веб-приложения или веб-страницы. Этот объект предоставляет различные методы и свойства, которые позволяют измерять производительность вашего кода, а также оценивать время выполнения определенных операций на клиентской стороне. Он особенно полезен при профилировании и оптимизации веб-приложений.
- personalbar - контексте веб-браузера обычно относится к панели закладок, которую пользователь может настроить для хранения и управления своими закладками
- postMessage() - метод позволяет безопасно отправлять кроссдоменные запросы.
- print() - Открывает диалоговое окно для печати текущего документа.
- prompt() - отображает диалоговое окно с необязательным запросом на ввод текста.
- queueMicrotask()  - это функция в JavaScript, которая позволяет поставить задачу (microtask) в очередь микрозадач (microtask queue) после завершения текущей выполнения стека вызовов (call stack). Задачи, добавленные с помощью queueMicrotask(), будут выполнены перед выполнением задач из очереди событий (event queue), таких как обработка событий DOM или выполнение таймеров.
                Эта функция полезна, когда вам нужно гарантировать, что определенный код будет выполнен после завершения текущей операции, но до начала выполнения следующей. Она обычно используется для выполнения асинхронных операций с высоким приоритетом.
- releaseEvents() - является устаревшим и не рекомендуется к использованию
- reportError() - метод, который используется для сообщения об ошибках, возникших в асинхронных операциях, таких как обработка событий и выполнение промисов, на более высоком уровне кода. Этот метод обычно используется в объекте window.console в современных браузерах.
- requestAnimationFrame() - указывает браузеру на то, что вы хотите произвести анимацию, и просит его запланировать перерисовку на следующем кадре анимации. В качестве параметра метод получает функцию, которая будет вызвана перед перерисовкой.
- requestIdleCallback() - это API, предназначенное для выполнения задач в браузере, когда система находится в состоянии простоя, то есть когда есть достаточно времени и ресурсов для выполнения дополнительной работы без влияния на производительность и отзывчивость веб-приложения. Ставит в очередь функцию, которая будет вызываться во время периодов простоя браузера. Это позволяет разработчикам выполнять фоновую и низкоприоритетную работу в цикле основного события, без воздействия такими критично долгими событиями, как анимация и обработка ввода.
- resizeBy() - метод, который используется для изменения размера текущего окна браузера на заданные величины в пикселях. Он можно вызвать на объекте window, и он изменит размер окна браузера в соответствии с переданными аргументами.
- resizeTo() - метод, который используется для изменения размера текущего окна браузера на заданные ширину и высоту в пикселях. Он можно вызвать на объекте window, и он изменит размер окна браузера на указанные значения ширины и высоты.
- Scheduler {}
- Screen - свойство предоставляет доступ к объекту, который содержит информацию о экране пользователя, на котором открыто текущее окно браузера. Объект screen предоставляет разнообразные свойства, представляющие характеристики экрана, такие как разрешение, размеры экрана и даже информацию о цветности.
- screenLeft - было устаревшим и больше не рекомендуется к использованию. Вместо screenLeft рекомендуется использовать более современное свойство window.screenX, которое предоставляет аналогичную информацию
- screenTop - было устаревшим и больше не рекомендуется к использованию
- screenX - предоставляет горизонтальную (X) координату левого верхнего угла окна браузера относительно левого края экрана. Это свойство позволяет определить, где находится верхний левый угол текущего окна на экране
- screenY - является частью объекта window в JavaScript и предоставляет вертикальную (Y) координату левого верхнего угла окна браузера относительно верхнего края экрана. Это свойство позволяет определить, где находится верхний левый угол текущего окна на экране.
- scroll() - Метод scroll() в JavaScript предназначен для прокрутки содержимого элемента, такого как окно браузера или элемент с прокруткой, к указанным координатам или точке внутри этого элемента. Этот метод может быть использован для программного управления прокруткой на веб-странице.
- scrollBy() - Метод scrollBy() в JavaScript используется для прокрутки содержимого элемента или окна браузера на определенное количество пикселей относительно текущей позиции прокрутки. Этот метод позволяет программно управлять прокруткой вверх, вниз, влево или вправо.
- scrollTo() - Метод scrollTo() в JavaScript используется для программного управления прокруткой содержимого элемента или окна браузера до определенных координат или точки внутри этого элемента или окна. Этот метод позволяет установить точное положение прокрутки.
- scrollX - это устаревшее свойство в JavaScript, которое предоставляло информацию о текущей горизонтальной позиции прокрутки окна браузера
- scrollY - являются устаревшими свойствами
- scrollbars  - это интерфейсные элементы, которые появляются в окне браузера или внутри элемента с прокруткой, когда содержимое на веб-странице не полностью помещается в видимую область окна или элемента. Полосы прокрутки позволяют пользователю перемещать видимую область, чтобы просматривать скрытую часть контента.
- self - Свойство Window.self доступно только для чтения и возвращает объект window в виде объекта WindowProxy. 
- sessionStorage  - это объект, предоставляемый браузером в среде выполнения JavaScript, который используется для хранения данных на уровне сессии. Данные, сохраненные в sessionStorage, доступны только в рамках одной сессии браузера и сохраняются даже после перезагрузки или обновления страницы.
- setInterval() - Метод setInterval() предложен для Window и Worker интерфейсов. Он циклически вызывает функцию или участок кода с фиксированной паузой между каждым вызовом. Уникальный идентификатор intervalID, возвращаемый методом, позволяет впоследствии удалить запущенный setInterval c помощью clearInterval() (en-US). Метод определён с помощью миксина WindowOrWorkerGlobalScope.
- setTimeout() - Вызов функции или выполнение фрагмента кода после указанной задержки.
- speechSynthesis - Это экспериментальная технология. представляет собой речевой запрос. Он содержит контент, который речевая служба должна прочитать, и информацию о том, как его читать (например, язык, тон и громкость).
- statusbar - содержащих логическое visibleсвойство, которое используется для определения того, видна ли определенная часть пользовательского интерфейса веб-браузера.
    По соображениям конфиденциальности и совместимости значение свойства visibleтеперь равно, falseесли это Windowвсплывающее окно и trueв противном случае.
- structuredClone() - Глобальный structuredClone()метод создает глубокий клон заданного значения с использованием алгоритма структурированного клонирования .
- styleMedia
- toolbar - одно из группы Windowсвойств, содержащих логическое visibleсвойство, которое используется для определения того, видна ли определенная часть пользовательского интерфейса веб-браузера.
- top
- TrustedTypePolicyFactory 
- VisualViewport 
- webkitCancelAnimationFrame()
- webkitRequestAnimationFrame()
- webkitRequestFileSystem()
- webkitResolveLocalFileSystemURL() 
