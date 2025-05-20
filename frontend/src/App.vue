<script setup>

</script>

<template>
    <header>
      <label> ComicSans </label>
    </header>

    <body>
      <div class="universes">

          <button id="dc">
            <label> DC </label>
          </button>
          
          <button id="marvel">
            <label> Marvel </label>
          </button>

          <button id="bubble">
            <label> Bubble </label>
          </button>
        
      </div>
    </body>
</template>

<style lang="scss" scoped>

    $dc-color-button-default: rgba(3, 116, 157, 0.2);
    $dc-color-button-hover: rgba(0, 187, 255, 0.75);

    $marvel-color-button-default: rgba(150, 1, 1, 0.2);
    $marvel-color-button-hover: rgba(253, 0, 0, 0.75);

    $bubble-color-button-default: rgba(39, 54, 170, 0.2);
    $bubble-color-button-hover: rgba(50, 74, 255, 0.75);


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
      background: $dc-color-button-default;

      &:hover {
        background: $dc-color-button-hover;
      }
    }

    #marvel {
      background: $marvel-color-button-default;

      &:hover {
        background: $marvel-color-button-hover;
      }
    }

    #bubble {
      background: $bubble-color-button-default;

      &:hover {
        background: $bubble-color-button-hover;
      }
    }

</style>

