<template>
  <VRow>
    <VCol v-for="n in 200" cols="4" sm="3" md="2" lg="1">
      <VCard>
        <VImg
          :src="`https://picsum.photos/500/300?image=${n * 5 + 10}`"
          :lazy-src="`https://picsum.photos/10/6?image=${n * 5 + 10}`"
          aspect-ratio="1"
          cover
        >
          <template v-slot:placeholder>
            <v-row class="fill-height ma-0" align="center" justify="center">
              <VProgressCircular
                indeterminate
                color="grey-lighten-5"
              ></VProgressCircular>
            </v-row>
          </template>
        </VImg>
      </VCard>
    </VCol>
  </VRow>
</template>
