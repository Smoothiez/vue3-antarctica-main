<template>
    
</template>

<style scoped>
#footContainer {
        color: white;
        text-align: left;
        background-color: black;
    }

    #footinfo {
        font-size: 20px;
        width: 80%;
        text-align: left;
        margin-left: 10%;
		padding:20px 0px 30px 0px;
		height:30px;
    }

	.footitem{
		margin-right:10px;
		padding:8px;
		border-radius:10px;
		white-space: nowrap;
	
	}
	

	
	.footitemSeperator{
		margin-right:10px;
		padding:10px;
		
		
	}
	
	.footitem:hover{
		background-color:#333333;
		cursor:pointer;
	}
	
	
       #footinfo a:link {
        text-decoration: none;
       
        color: white;
    }



    #footinfo a:visited {
        color: white;
    }
	
	@media screen and (max-width: 950px) {
	#footinfo{
	 font-size: 25px;
	 height:50px;
	}
}
</style>
