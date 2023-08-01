# События и jQuery. Стили и анимация
### Задание 1
Реализовать галерею для просмотра изображений.
Возможности: <br/>
■ перелистнуть к следующему изображению; <br/>
■ перелистнуть к предыдущему изображению; <br/>
■ перейти к самому последнему изображению; <br/>
■ перейти к самому первому изображению; <br/>
■ перейти к конкретному изображению с помощью клика 
по точке на индикаторе*; <br/>
■ развернуть галерею на весь экран; <br/>
■ свернуть галерею к стандартному размеру; <br/>
■ запустить автоматическое слайд-шоу**; <br/>
■ остановить автоматическое слайд-шоу. <br/>
*Индикатор показывает, сколько всего изображений в галерее 
с помощью незакрашенных точек. Точка, которая соответствует 
текущему изображению, должна быть закрашенной. При клике на 
точку галерея переходит к соответствующему изображению. <br/>
**Автоматическое слайд-шоу предполагает перелистывание изображений раз в секунду без участия пользователя. Когда автоматическое слайд-шоу доходит до последнего изображение, то оно 
останавливается. <br/>
Требования: <br/>
■ перелистывание изображений должны сопровождаться 
анимацией на ваш вкус; <br/>
■ алгоритм должен быть рассчитан на любое количество 
изображений (пути к изображениям должны храниться в 
массиве, они не должны быть фиксировано прописанными в html);  <br/>
■ если нет следующего или предыдущего изображения для 
перелистывания, то кнопки вперед или назад должны 
блокироваться;  <br/>
■ запускать и останавливать слайд-шоу должна одна и та же 
кнопка (когда слайд-шоу не работает, на кнопке отображается иконка Play; когда слайд-шоу работает, на кнопке 
отображается иконка Stop);  <br/>
■ разворачивать и сворачивать галерею должна одна и та 
же кнопка, а иконка на кнопке меняется в зависимости от 
текущего состояния галереи (в стандартном размере или 
развернута);  <br/>
■ если изображения разных размеров, то они должны пропорционально растягиваться на всю ширину и высоту галереи
