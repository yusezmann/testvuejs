<template>
<v-container>
  <v-row>
    <v-col cols="4" class="ml-12"></v-col>
    <v-col cols="4" class="align-content-center ml-16">
      <img src="../assets/img/logo-medium.png" alt="">
    </v-col>
    <v-col cols="4"></v-col>
  </v-row>
  <v-row >
    <v-col cols="6">
    <div class="black--text text-center">
    <img src="../assets/img/register.png"  style="height:300px;width:300px;margin-right:5px" alt="">
      <h1 style="font-size:30px">Easy Buying Only at bee2beehub</h1>
      <p style="font-size:15px">Join Now and feel of transacting on bee2beehub</p>
    </div>
    </v-col>
    <v-col cols="2"></v-col>
    <v-col cols="4">
      <v-card
      class="mr-6"
      elevation="2"
      outlined
      style="border-radius:10px"
      >
        <v-container >
        <v-card-title >
          <div class="text-center ml-6"  style="margin-bottom:-40px;" >
            <h1 style="font-size:23px;" class="mr-6" >Register Now</h1>
            <p style="font-size:13px" >
              Already have bee2beehub account?
              <NuxtLink class="text-decoration-none" to="/login">
                <span class="warning--text " >Login</span>
              </NuxtLink>
            </p>
          </div>
        </v-card-title>
        <v-card-text>
          <v-col cols="12" >
            <v-sub-header>
            First Name
              <v-text-field
                class="mt-2"
                label="First Name"
                placeholder="First Name"
                style="border-radius:10px;"
                solo
              ></v-text-field>
            </v-sub-header>
          </v-col>
          <v-col cols="12" style="margin-top:-40px;">
          <v-sub-header>
            Last Name
            <v-text-field
              class="mt-2"
              label="Last Name"
              placeholder="Last Name"
              style="border-radius:10px;"
              solo
            ></v-text-field>
          </v-sub-header>
          </v-col>
          <v-col cols="12" style="margin-top:-40px;">
          <v-sub-header>
            Email
            <v-text-field
              class="mt-2"
              label="Email"
              placeholder="Email"
              style="border-radius:10px;"
              solo
            ></v-text-field>
          </v-sub-header>
          </v-col>
          <v-col cols="12" style="margin-top:-40px;">
          <v-sub-header>
            Phone Number
            <v-text-field
              class="mt-2"
              label="Phone Number"
              placeholder="Phone Number"
              style="border-radius:10px;"
              solo
            ></v-text-field>
          </v-sub-header>
          </v-col>
          <v-col cols="12" style="margin-top:-40px;">
          <v-sub-header>
            Password
            <v-text-field
              class="mt-2"
              label="Password"
              placeholder="Password"
              append-icon="mdi-eye"
              type="password"
              style="border-radius:10px;margin-bottom:-20px;"
              solo
            ></v-text-field>
          </v-sub-header>
          </v-col>
        </v-card-text>
        <v-col cols="12" class="text-center " style="margin-top:-20px;">
          <v-btn
            rounded
            class="black--text"
            color="warning"
            style="width:255px;height:50px"
          >
            Register
          </v-btn>
        </v-col>
        <v-card-text class="text-center py-4" style="font-size:12px;margin-top:-20px;">
          <p>By registering, I agree</p>
          <p style="margin-top:-20px;margin-bottom:-10px;">Terms and Conditions and Privacy Policy</p>
        </v-card-text>
        </v-container>
      </v-card>
    </v-col>
  </v-row>
</v-container>
</template>
