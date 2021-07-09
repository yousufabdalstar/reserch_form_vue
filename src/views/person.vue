<template>
<div>
    <h1 class="text-center p-5">
        نسبة انجاز البحث
    </h1>
  <vc-donut
    background="white" foreground="red"
    :size="200" unit="px" :thickness="20"
    hasLegend legendPlacement="top"
    :sections="sections" :total="2"
    
  >
   
    <h1 v-if="value=1">
      50%
        </h1>
     <h1 v-else>
      100%
        </h1>
   
  </vc-donut>
</div>
</template>
<script>
  export default {
    data() {
      return {
        sections: [
          { label: 'لم ينجز', value: 0, color: 'red' },
          { label: 'اكتمل', value: 0, color: 'green' },
          { label: 'تحت الانجاز' ,value: 1, color: 'blue' },
        ],
      
     
       
      }
    },
    
  
  }
</script>