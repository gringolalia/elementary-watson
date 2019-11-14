<template lang="pug">
#app
	el-container
		el-aside(width="200px")
			el-row.tac
				el-col(:span='24')
					el-menu.el-menu-vertical-demo(default-active='1' @open='handleOpen' @close='handleClose' background-color='#607d8b' text-color='#ffffff' active-text-color='#ffffff' style="min-height: 100vh;")
						el-submenu(index='1')
							template(slot='title')
							el-menu-item-group(title='Group One')
								el-menu-item(index='1-1') Boron
								el-menu-item(index='1-2') Flourine
							el-menu-item-group(title='Group Two')
								el-menu-item(index='1-3') Uranium
							el-submenu(index='1-4')
								template(slot='title')
								el-menu-item(index='1-4-1') Helium
						el-menu-item(index='2')
							i.el-icon-menu
							span Navigator Two
						el-menu-item(index='3')
							i.el-icon-document
							span Navigator Three
						el-menu-item(index='4')
							i.el-icon-setting
							span Navigator Four
		router-view
</template>	
<style>
#app {
	font-family: "News Cycle", Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
}
</style>
