<script setup>

</script>

<template>
    <header>
      <label class="head">
          ComicSans
      </label>
    </header>

    <body>
      <div class="universes">

          <button class="universe" id="dc">
            <label class="label-bttn">DC</label>
          </button>
          
          <button class="universe" id="marvel">
            <label class="label-bttn">Marvel</label>
          </button>

          <button class="universe" id="bubble">
            <label class="label-bttn">Bubble</label>
          </button>
        
      </div>
    </body>
</template>

<style scoped>
    header {
      width: 100%;
      height: 100px;
      display: flex;
      justify-content: center; /* Центрирует по горизонтали */
      align-items: center; /* Центрирует по вертикали */
    }

    .head {
      position: relative;
      width: 800px;
      height: 200px;
      display: flex;
      justify-content: center; /* Центрирует содержимое внутри head */
      align-items: center; /* Центрирует содержимое внутри head */

      color: rgb(255, 255, 255);
      font-family: 'Sedgwick Ave Display', cursive;
      font-size: 72px;
      font-weight: 400;
      line-height: 160px;
      letter-spacing: 0%;
      text-align: center;
    }

    .universes {
      width: 100%;
      position: relative;
      top: 100px;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .universe {
      width: 20%;
      height: 70px;
      transform: skew(-20deg);
      position: relative;
      margin: 1%;
    }

    #dc {
      background: rgba(3, 116, 157, 0.2)
    }
    #dc:hover {
      background: rgba(3, 116, 157, 0.75)

    }

    #marvel {
      background: rgba(150, 1, 1, 0.2)
    }
    #marvel:hover {
      background: rgba(150, 1, 1, 0.75)
    }

    #bubble {
      background: rgba(39, 54, 170, 0.2)
    }
    #bubble:hover {
      background: rgba(39, 54, 170, 0.75)
    }

    .label-bttn {
      color: rgb(255, 255, 255);
      font-family: Montserrat;
      transform: none;
      font-size: 36px;
      font-weight: 400;
      line-height: 59px;
      letter-spacing: 0%;
      text-align: center;
    }
</style>

