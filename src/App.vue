<template>
  <v-app>
<v-main>
  <v-container fluid>
    <v-row>
      <v-col cols="12" md="6" sm="6">

          <h1 class="my-3">outline</h1>
          <v-btn variant="outlined" prepend-icon="$vuetify">
            button
          </v-btn>
     
      </v-col>
      <v-col cols="12" md="6" sm="6">
      <v-btn variant="tonal">
        button
      </v-btn>
      </v-col>
    </v-row>

    <v-row>
     <v-col cols="12" md="6" sm="6">
<v-card
class="mx-auto"
prepend-icon="$vuetify"
subtitle="the #1 vUe ui "
width="400"
>
<template v-slot:title>
<span class="font-weight-black">웰컴</span>
</template>
<v-card-text class="bg-surface-light pt-4">
Lorem ipsum dolor sit, amet consectetur adipisicing elit. Assumenda quod veniam minima laboriosam nisi numquam rem vitae veritatis, sed repellat aut impedit consequuntur iure quibusdam adipisci earum laudantium a eos!

</v-card-text>

</v-card>
     </v-col>
      <v-col cols="12" md="6" sm="6">
         <v-card
    class="mx-auto text-white"
    color="#26c6da"
    max-width="400"
    prepend-icon="mdi-twitter"
    title="Twitter"
  >
    <template v-slot:prepend>
      <v-icon size="x-large"></v-icon>
    </template>

    <v-card-text class="text-h5 py-2">
      "Turns out semicolon-less style is easier and safer in TS because most gotcha edge cases are type invalid as well."
    </v-card-text>

    <v-card-actions>
      <v-list-item class="w-100">
        <template v-slot:prepend>
          <v-avatar
            color="grey-darken-3"
            image="https://avataaars.io/?avatarStyle=Transparent&topType=ShortHairShortCurly&accessoriesType=Prescription02&hairColor=Black&facialHairType=Blank&clotheType=Hoodie&clotheColor=White&eyeType=Default&eyebrowType=DefaultNatural&mouthType=Default&skinColor=Light"
          ></v-avatar>
        </template>

        <v-list-item-title>Evan You</v-list-item-title>

        <v-list-item-subtitle>Vue Creator</v-list-item-subtitle>

        <template v-slot:append>
          <div class="justify-self-end">
            <v-icon class="me-1" icon="mdi-heart"></v-icon>
            <span class="subheading me-2">256</span>
            <span class="me-1">·</span>
            <v-icon class="me-1" icon="mdi-share-variant"></v-icon>
            <span class="subheading">45</span>
          </div>
        </template>
      </v-list-item>
    </v-card-actions>
  </v-card>
     </v-col>
    </v-row>
  </v-container>
  </v-main>
  </v-app>
</template>

<script>
export default{
  name: 'App',
  components:{

  },
  /*new Vue({
    el:"#app",
    vuetify:new Vuetify(),
  })*/
}
</script>

<style>
@font-face {
    font-family: 'Paperlogy-8ExtraBold';
    src: url('https://fastly.jsdelivr.net/gh/projectnoonnu/2408-3@1.0/Paperlogy-8ExtraBold.woff2') format('woff2');
    font-weight: 800;
    font-style: normal;
}
#app{
  font-family: 'Paperlogy-8ExtraBold';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing:grayscale;
  text-align: center;
}
</style>