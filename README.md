#vue基础
##第一部分
###mvvm概述 vue入门
###vue常用指令：
####常用指令
    v-html v-text v-for v-if v-show v-once v-model
####属性操作
    v-bind v-bind:src="url" 或者直接:src=""     
###事件:
    v-on或者@:click
###简易留言板案例(界面采用bootstrap):功能添加、列表显示、删除、清空全部
###事件深入
####事件对象
    @click="show(event)"
####阻止事件冒泡
     @click.stop="show" 
####阻止默认行为 
    @click.prevent="show(event)" 
####键盘事件: 
    @keydown.enter 或者直接keyCode @keydown.13
    @keydown.up
    @keydown.down  
    @keydown.left
    @keydown.right  
###异步ajax vue-resource
    get:    post:   jsonp:
###百度搜索案例
