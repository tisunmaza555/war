<template>
  <div>

    <p>
      hp player {{ randomNo(1,3)}}
    </p>
    รูป
    <hr />
    name = {{ aPlayer.name}}
    hp= {{aPlayer.hp}}
    image= {{aplayer.image}}
    <hr />
    <p> Hp monster 150 </p>
    รูป
    <button @click="start()"> Start</button>
     <button @click="attack()"> Attack</button>
  </div>
</template>

<script>
export default {
  data:function() {
    return {
      player:[
        {name:'fairy',hp:120},
        {name:'rungpo',hp:100},
        {name:'nane',hp:120},
        {name:'teacher',hp:2500}
      ],
    monster:[
        {name:'anabell',hp:100},
        {name:'chucky',hp:120},
        {name:'juon',hp:140},
        {name:'Sunkung',hp:2000}]}
  }

}
</script>

<style>

</style>