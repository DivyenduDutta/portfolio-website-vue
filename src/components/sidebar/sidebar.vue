
<template>
   <div class="my-sidebar">
        <ul>
            <li>Hey!!</li>
            <li>Personal Work</li>
            <li>Resume</li>
        </ul>
   </div>
</template>

<script>
export default {
    name : 'sidebar'    
}
</script>

<style scoped>
.my-sidebar{
    position: sticky;
    display: inline-block;
    vertical-align: top;

    top: 0;
    bottom: 0;
    padding: 30px;

    overflow-y: auto;
    
    /*max-height: 100%;*/
    height: 100%;

    width: 350px;

    color: #C9CCA1;
    background-color: #515262;
}

</style>