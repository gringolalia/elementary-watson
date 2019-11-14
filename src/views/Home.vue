<template lang="pug">
	el-container
		el-main
			el-row
				el-col.grid-content.bg-purple-dark(:span="8")
					img(src='../assets/alchemy-sulphuric.svg')
					h2 Elements of Ewe and Eye
					el-button(type="info") Apertar
					el-button(icon="el-icon-share" type="danger")
				el-col.grid-content.bg-purple-dark(:span="8")
					img(src='../assets/alchemy-sulphuric.svg')
					h2 Elements of Ewe and Eye
					el-button(type="info") Apertar
				el-col.grid-content.bg-purple-dark(:span="8") 
					img(src='../assets/alchemy-sulphuric.svg')
					h2 Elements of Ewe and Eye
					el-button(type="info") Apertar
			el-row
				el-col.grid-content.bg-purple-dark(:span="8")
					img(src='../assets/alchemy-sulphuric.svg')
					h2 Elements of Ewe and Eye
					el-button(type="info") Apertar
				el-col.grid-content.bg-purple-dark(:span="8")
					img(src='../assets/alchemy-sulphuric.svg')
					h2 Elements of Ewe and Eye
					el-button(type="info") Apertar
				el-col.grid-content.bg-purple-dark(:span="8") 
					img(src='../assets/alchemy-sulphuric.svg')
					h2 Elements of Ewe and Eye
					el-button(type="info") Apertar
	
	
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
	name: 'home',
	components: {
		HelloWorld
	}
}
</script>
