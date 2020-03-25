canvas_painting：原生实现一个canvas绘图小功能，pc端小demo，把鼠标事件换成触摸事件，可以在移动端使用

ontouchstart时要加e.preventDefault()阻止默认事件；
window:e.pageX
触摸：e.changedTouches[0].pageX