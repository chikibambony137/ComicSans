<script setup>

</script>

<template>
    <header>
      <label>
          ComicSans
      </label>
    </header>

    <body>
      <div class="universes">

          <button id="dc">
            <label>DC</label>
          </button>
          
          <button id="marvel">
            <label>Marvel</label>
          </button>

          <button id="bubble">
            <label>Bubble</label>
          </button>
        
      </div>
    </body>
</template>

<style lang="scss" scoped>

    .universes {
      width: 100%;

      position: relative;
      top: 100px;

      display: flex;
      justify-content: center;
      align-items: center;

      button {
        width: 20%;
        height: 70px;
        transform: skew(-20deg);

        position: relative;
        margin: 1%;

        label {
          color: white;
          transform: none;
          line-height: 59px;
          letter-spacing: 0%;
          text-align: center;

          font: {
            family: 'Montserrat';
            size: 36px;
            weight: 400;
          }
        }
      }
    }

    #dc {
      background: rgba(3, 116, 157, 0.2);

      &:hover {
        background: rgba(0, 187, 255, 0.75);
      }
    }

    #marvel {
      background: rgba(150, 1, 1, 0.2);

      &:hover {
        background: rgba(253, 0, 0, 0.75);
      }
    }

    #bubble {
      background: rgba(39, 54, 170, 0.2);

      &:hover {
        background: rgba(50, 74, 255, 0.75);
      }
    }

</style>

