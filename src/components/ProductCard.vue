<template>
  <div class="q-pa-md row items-start q-gutter-md">


    <q-card class="my-card" flat bordered>
      <q-img src='../assets/productImages/socks_blue.jpg'/>

      <q-card-section>
        <q-btn
          fab
          color="negative"
          icon="delete"
          class="absolute"
          style="top: 58px; right: 12px; transform: translateY(-50%);"
        />
        <q-btn
          fab
          color="accent"
          icon="edit"
          class="absolute"
          style="top: 0; right: 12px; transform: translateY(-50%);"
        />

        <div class="row no-wrap items-center">
          <div class="col text-h6 ellipsis">
            Meias (Azul)
          </div>
<!--          <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">-->
<!--            <q-icon name="delete"/>-->
<!--            250 ft-->
<!--          </div>-->
        </div>
      </q-card-section>

      <q-card-section class="q-pt-none justify-center">
        <div class="text-subtitle1">
          $ Preço
        </div>

        <div class="text-subtitle1">
           Quantidade
        </div>

        <div class="text-subtitle1">
          Categoria
        </div>

        <div class="text-subtitle1">
          Criação
        </div>

        <div class="text-subtitle1">
          Ultima Modificação
        </div>



        <!--        -->
<!--        <div class="text-caption text-grey">-->
<!--          Small plates, salads & sandwiches in an intimate setting.-->
<!--        </div>-->
      </q-card-section>

      <q-separator/> <!--TODO: pesquisar pra que serve -->

<!--      <q-card-actions>-->
<!--        <q-btn flat round icon="event"/>-->
<!--        <q-btn flat color="primary">-->
<!--          Reserve-->
<!--        </q-btn>-->
<!--      </q-card-actions>-->
    </q-card>



    <q-card class="my-card" flat bordered>
      <q-img src='../assets/productImages/socks_blue.jpg'/>

      <q-card-section>
        <q-btn
          fab
          color="negative"
          icon="delete"
          class="absolute"
          style="top: 58px; right: 12px; transform: translateY(-50%);"
        />
        <q-btn
          fab
          color="accent"
          icon="edit"
          class="absolute"
          style="top: 0; right: 12px; transform: translateY(-50%);"
        />

        <div class="row no-wrap items-center">
          <div class="col text-h6 ellipsis">
            Meias (Azul)
          </div>
          <!--          <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">-->
          <!--            <q-icon name="delete"/>-->
          <!--            250 ft-->
          <!--          </div>-->
        </div>
      </q-card-section>

      <q-card-section class="q-pt-none justify-center">
        <div class="text-subtitle1">
          $ Preço
        </div>

        <div class="text-subtitle1">
          Quantidade
        </div>

        <div class="text-subtitle1">
          Categoria
        </div>

        <div class="text-subtitle1">
          Criação
        </div>

        <div class="text-subtitle1">
          Ultima Modificação
        </div>



        <!--        -->
        <!--        <div class="text-caption text-grey">-->
        <!--          Small plates, salads & sandwiches in an intimate setting.-->
        <!--        </div>-->
      </q-card-section>

      <q-separator/> <!--TODO: pesquisar pra que serve -->

      <!--      <q-card-actions>-->
      <!--        <q-btn flat round icon="event"/>-->
      <!--        <q-btn flat color="primary">-->
      <!--          Reserve-->
      <!--        </q-btn>-->
      <!--      </q-card-actions>-->
    </q-card>


  </div>
</template>

<script>
import {ref} from 'vue'

export default {
  setup() {
    return {
    }
  }
}
</script>

<style lang="sass" scoped>
.my-card
  width: 100%
  max-width: 300px
</style>

