<template>
	<div class="vk-subheading" :style="alignObject">
		<h3 v-if="variant == 1" class="vk-subheading__1">{{text}}</h3>
		
		<h3 v-if="variant == 2" class="vk-subheading__2">{{text}}</h3>
		
		<div v-if="variant == 3" class="vk-subheading__3">
			<h3>{{text}}</h3>
			<hr>
		</div>
		
		<div v-if="variant == 4" class="vk-subheading__4">
			<label>{{number}}</label>
			<h3>{{text}}</h3>
		</div>
		
		<div v-if="variant == 5" class="vk-subheading__5">
			<label>{{number}}</label>
			<h3>{{text}}</h3>
		</div>
		
		<h3 v-if="variant == 6" class="vk-subheading__6"><label>{{label}}</label> {{text}}</h3>
		
		<div v-if="variant == 7" class="vk-subheading__7" :style="alignObject">
			<label>{{label}}</label>
			<h3>{{text}}</h3>
		</div>
		
		<div v-if="variant == 8" class="vk-subheading__8" :style="alignObject">
			<label>{{number}}</label>
			<h3>{{text}}</h3>
			<hr>
		</div>
		
	</div>
</template>

<script>
    export default {
        name: "vk-subheading",
	    
	    props: ['text', 'label', 'variant', 'number', 'text_align'],
	    
	    computed : {
            alignObject() {
                if(this.text_align) {
                    return {
                        'align-items' : this.text_align,
	                    'text-align' : this.text_align.replace("flex-", "")
                    }
                } else {
                    return {
                        'align-items' : 'flex-start'
                    }
                }
                
            }
	    }
    }
</script>

<style scoped lang="scss">
	.vk-subheading {
		&__1 {
			font-family: 'Capitolium Head', serif;
		}
		
		&__2 {
			text-transform: uppercase;
		}
		
		&__3 {
			h3 {
				margin-bottom: 0;
				text-transform: uppercase;
			}
			hr {
				border-top: 1px dotted #000;
				background: transparent;
				margin-bottom: 5px;
			}
		}
		
		&__4 {
			max-width: 300px;
			width: 100%;
			display: flex;
			flex-direction: row;
			flex-wrap: nowrap;
			justify-content: flex-start;
			align-items: center;
			
			label {
				font-size: 50px;
				font-family: 'Benton Sans', sans-serif;
				font-weight: 100;
				margin-right: 5px;
			}
			
			h3 {
				text-transform: uppercase;
			}
		}
		
		&__5 {
			max-width: 300px;
			width: 100%;
			display: flex;
			flex-direction: row;
			flex-wrap: nowrap;
			justify-content: flex-start;
			align-items: center;
			
			label {
				font-size: 50px;
				font-weight: bold;
				font-family: 'Capitolium Head', serif;
				margin-right: 5px;
			}
			
			h3 {
				text-transform: uppercase;
				font-weight: 100;
			}
		}
		
		&__6 {
			max-width: 300px;
			text-transform: uppercase;
			font-weight: 100;
			
			label {
				font-weight: bold;
			}
		}
		
		&__7 {
			max-width: 200px;
			display: flex;
			flex-direction: column;
			justify-content: center;
			align-items: flex-start;
			
			label {
				font-family: 'Benton Sans', sans-serif;
				font-weight: 100;
				text-transform: uppercase;
			}
			
			h3 {
				font-family: 'Capitolium Head', serif;
			}
		}
		
		&__8 {
			max-width: 200px;
			display: flex;
			flex-direction: column;
			justify-content: center;
			align-items: flex-start;
			
			label {
				font-size: 40px;
				font-weight: bold;
				font-family: 'Capitolium Head', serif;
				text-align: center;
			}
			h3 {
				text-transform: uppercase;
				font-weight: 100;
			}
			hr {
				width: 90%;
				border-top: 1px dotted #000;
				background: transparent;
				margin-bottom: 5px;
			}
		}
	}
</style>