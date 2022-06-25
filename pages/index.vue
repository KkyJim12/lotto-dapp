<template>
  <main class="px-10 py-10">
    <v-container>
      <v-row>
        <v-col md="12">
          <h1>Random result</h1>
        </v-col>
        <v-col md="2">
          <v-card :loading="isApplyLoading">
            <v-card-title class="px-10 py-10 justify-center"
              ><h1 class="display-4">?</h1></v-card-title
            >
          </v-card>
        </v-col>
        <v-col md="2">
          <v-card :loading="isApplyLoading">
            <v-card-title class="px-10 py-10 justify-center"
              ><h1 class="display-4">?</h1></v-card-title
            >
          </v-card> </v-col
        ><v-col md="2">
          <v-card :loading="isApplyLoading">
            <v-card-title class="px-10 py-10 justify-center"
              ><h1 class="display-4">?</h1></v-card-title
            >
          </v-card> </v-col
        ><v-col md="2">
          <v-card :loading="isApplyLoading">
            <v-card-title class="px-10 py-10 justify-center"
              ><h1 class="display-4">?</h1></v-card-title
            >
          </v-card> </v-col
        ><v-col md="2">
          <v-card :loading="isApplyLoading">
            <v-card-title class="px-10 py-10 justify-center"
              ><h1 class="display-4">?</h1></v-card-title
            >
          </v-card> </v-col
        ><v-col md="2">
          <v-card :loading="isApplyLoading">
            <v-card-title class="px-10 py-10 justify-center"
              ><h1 class="display-4">?</h1></v-card-title
            >
          </v-card>
        </v-col>
        <v-col md="12">
          <v-btn @click="applyLotto()" color="primary" block> Apply </v-btn>
        </v-col>
      </v-row>

      <v-row>
        <v-col md="12">
          <h1>Buy Number</h1>
        </v-col>
        <v-col md="2">
          <v-text-field
            class="display-1"
            placeholder="1st number"
            solo
            type="number"
            height="220"
          ></v-text-field>
        </v-col>
        <v-col md="2">
          <v-text-field
            class="display-1"
            placeholder="2nd number"
            solo
            type="number"
            height="220"
          ></v-text-field>
        </v-col>
        <v-col md="2">
          <v-text-field
            class="display-1"
            placeholder="3rd number"
            solo
            type="number"
            height="220"
          ></v-text-field>
        </v-col>
        <v-col md="2">
          <v-text-field
            class="display-1"
            placeholder="4th number"
            solo
            type="number"
            height="220"
          ></v-text-field>
        </v-col>
        <v-col md="2">
          <v-text-field
            class="display-1"
            placeholder="5th number"
            solo
            type="number"
            height="220"
          ></v-text-field>
        </v-col>
        <v-col md="2">
          <v-text-field
            class="display-1"
            placeholder="6th number"
            solo
            type="number"
            height="220"
          ></v-text-field>
        </v-col>
        <v-col md="4">
          <v-btn color="primary" block>Buy this number</v-btn>
        </v-col>
        <v-col md="4">
          <v-btn color="warning" block>Random number</v-btn>
        </v-col>
        <v-col md="4">
          <v-btn color="error" block>Reset number</v-btn>
        </v-col>
      </v-row>
      <v-row>
        <v-col md="6">
          <v-card class="px-5 py-5" height="600"
            ><h1>Your Buying Number</h1>
            <v-divider></v-divider>
            <p>1 - 123456</p></v-card
          >
        </v-col>
        <v-col md="6">
          <v-card class="px-5 py-5" height="600"
            ><h1>Prize History</h1>
            <v-divider></v-divider>
            <p>1 - 123456</p></v-card
          >
        </v-col>
      </v-row>
    </v-container>
  </main>
</template>

<script>
export default {
  data() {
    return {
      isApplyLoading: false,
    }
  },
  methods: {
    applyLotto() {
      this.isApplyLoading = 'primary'
    },
  },
}
</script>
