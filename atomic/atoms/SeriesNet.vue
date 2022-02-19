<template>

    <div class="boxSeries">
      
        <span >
            <img src="https://cdn.pixabay.com/photo/2015/01/08/18/29/entrepreneur-593358_960_720.jpg" alt="serie-one">
        </span>
        <span>
             <img src="https://cdn.pixabay.com/photo/2016/08/29/08/55/work-1627703_960_720.jpg" alt="serie-two">
        </span>
         <span>
             <img src="https://cdn.pixabay.com/photo/2015/01/08/18/26/man-593333_960_720.jpg" alt="serie-two">
        </span>
         <span>
             <img src="https://cdn.pixabay.com/photo/2015/01/09/11/08/startup-594090_960_720.jpg" alt="serie-two">
        </span>
         <span>
             <img src="https://cdn.pixabay.com/photo/2015/07/17/22/43/student-849825_960_720.jpg" alt="serie-two">
        </span>
       
        
    </div>
    
</template>
    
<script>

export default {
    name: 'SeriesNet'
}
</script>
<style lang="postcss">
.boxSeries {
    display: flex;
    flex-direction: row;
    margin: 0 1em;
    width: 100%;
    height: 100%;
   
    
}

.boxSeries span img{
     width: 90%;
     height: auto;
     display: inline-block;
     margin: 0.2em;
}

</style>