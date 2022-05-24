<template>
    <div>
        <h1 class="homestyle">Class and Style Bindings</h1>
        <!-- <h1 v-bind:style="{color:'blue'}">Style Bindings</h1> -->
        <h1 v-bind:style="{color:colorKey}">Style Bindings</h1>
        <!-- <h1 v-bind:class="{display:show}">Class Bindings with objects</h1> -->
        <h1 v-bind:class="{display:show}">Class Bindings with objects</h1>
        <!-- <h1 v-bind:class="[aclass]">class binding with array</h1> -->
        
        <!-- inside inspect element to check yesShow or noShow  -->
        <h1 v-bind:class="[show?'yesShow':'noShow']">class binding with array</h1> 


    </div>
</template>
<script>
export default{ 
    name: 'vue-Home',
    data(){
        return{ 
            show:true,
            aclass:"arrayClass",
            colorKey:'red'
        }
    }
};

</script>
<style scoped>
.homestyle{ 
    color: orange
}
.display{ 
    background-color:brown ;
}
.arrayClass{ 
    background-color:cyan
}
</style>