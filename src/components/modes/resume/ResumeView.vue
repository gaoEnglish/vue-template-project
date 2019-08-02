<template>
<div class="grid" >
	<div>1</div>
	<div class="myMian_0">
		<div class="topDiv">
			<div style="width:30%">
                
                <img class="head" src="../../../assets/38745910.png">
            </div>
			<div style="width:70%">
				<ul>
					<li>
						A
					</li>
					<li>
						A
					</li>
					<li>
						A
					</li>
					<li>
						A
					</li>
				</ul>
				
			</div>
			
		</div>
		<div style="height:50%">
			<div class="downDiv">A</div>
		</div>
	</div>
	
	<div>1</div>
	
	<div>1</div>
	<div>1</div>
	<div>1</div>
	
	<div>1</div>
	<div>1</div>
	<div>1</div>
</div>

</template>
<script>
export default {
  name: 'Resume'
}
</script>

<style scoped>
	.grid{
		display: grid;
		grid-template-columns: 1fr 3fr 1fr;
		grid-template-rows: repeat(3, 265px);
		/*width:80%;*/
		/*height: 100%;*/
	}
	.grid>div{
		background-color:#eee;
		
	}
	.navigation{
		height:60px;
		background-color:#adb6bd;
	}
	.foo{
		height:60px;
		background-color:#adb6bd;
	}
	.grid .myMian_0{
		background-color: #dcecf5;
		height: 100%;
	}
	.grid .myMian_0 .topDiv{
		height: 50%;
		display: flex;
		flex-direction: row;
	}
	.grid .myMian_0 .downDiv{
		margin: auto;
		width: 80%;
		margin-top: 5%;
		height: 80%;
	}
    .grid .head{
        height: 100%;
        border-radius: 50%;
        margin: 0 15%;
    }
</style>
