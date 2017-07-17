## vue-popup

a vue popup component

## APIs

| name               |type          |default value /posible values      |description                |  
|----                |---           |---                                |---                        |
|value               |boolean       |false                              |v-model                    | 
|position            |string        |[top,right,bottom,left]            |where the popup to  appear | 
|modal               |boolean       |true                               |mask of popup              |
|modalClass          |string        |                                   |class name for mask        |
|zIndex              |string,number |                                   |z-index of mask and popup  |
|closeOnClickModal   |boolean       |true| click mask to close popup    |                           |  
|transition          |string        |popup-slide,[top,right,bottom,left]|transition of popup        |

## slots
	
|name  | description    |
|---   |---             |
|-     |popup content   |  


## usages   
	
	import popup from 'vue-popup'
	
	<popup v-model="popVisibility" position="bottom">
			your popup content goes here
	</popup>
	
## Inspired by 
	https://github.com/ElemeFE/vue-popup			