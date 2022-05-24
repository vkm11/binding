<template>
    <div>
        <h1 class="homestyle">Class and Style Bindings</h1>
        <h1 v-bind:style="{color:'blue'}">Style Bindings</h1>
        <!-- <h1 v-bind:class="{display:show}">Class Bindings with objects</h1> -->
        <h1 v-bind:class="{display:show}">Class Bindings with objects</h1>
        <h1 v-bind:class="[aclass]">class binding with array</h1>
    </div>
</template>
<script>
export default{ 
    name: 'vue-Home',
    data(){
        return{ 
            show:true,
            aclass:"arrayClass"
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