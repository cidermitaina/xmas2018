<template lang="pug">
article
  .text-area
    h2
      | It's a Christmas party come and join us for Christmas dinner
    p
      | Time flies so fast! Here comes this year's Christmas. We are pleased to announce that our annual Christmas party will be held at Yoshida's House on On 15th December. We hope that you will join the party and have a great time looking back on this year.
    h2
      | Date
    p
      | 2018.12.15(Sat) 17:00〜
    h2 
      | Place
    p
      | Yoshida's House
    h2
      | Food & Drink
    ul
      li  Bread
      li  Rice
      li  Salad
      li  Roast Beef
      li  Roast Chicken
      li  Ground Meat Cutlet
      li  Stew
      li  Christmas Cake
      li  Sparkling Wine
      li  Wine（Red/White）
      li  Plum Wine
    h2
      | Timetable
    p
      | 17:00　@Hunabashihoten station
      br
      | 18:00　Start
      br
      | 20:00　Gift exchange
      br
      | 22:00　End
    h2
      | Fee
    p
      | Entry fee：¥3000
      br
      | Present：¥2000
</template>

<style lang="scss" scoped>

  article {
    width: 50%;
    background:#32996D;
    color: #fff;
    overflow-y: scroll;

    h2 {
      line-height: 1.3;
      font-size: 1.8em;
      padding-top: 40px;
      letter-spacing: 1.1px;
      font-family: 'Lobster', cursive;
    }
    .text-area {
      padding: 0 30px 60px;
    }
    p {
      line-height: 1.4;
      font-size: 1em;
      padding-top: 10px;
    }
    ul {
      padding-left: 1.5em;
      font-size: 1em;
      padding-top: 10px;
    }
    li {
      padding-top: 5px;
    }
  }
// ======================================================
  // SP
  @media screen and (max-width: 768px) {
    
    article {
      width: 100%;
      
      .text-area {
        padding-top: 20px;
      }
    }

  }
</style>
