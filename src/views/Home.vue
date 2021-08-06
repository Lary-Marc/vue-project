<template>
  <div class="body">
    <div
      class="b_image"
      style="background:url('https://media.istockphoto.com/vectors/cartoon-design-of-the-flag-of-uganda-vector-id472335133?k=6&amp;m=472335133&amp;s=612x612&amp;w=0&amp;h=X0iYg1eQas2mDMobdv-vU53ieRluaQAvXgUGHQ8i-wE=');background-size: contain;"
    >
      <div>
        <img
          class="resize"
          src="data:image/jpeg;base64,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"
        />
      </div>
    </div>
    <form  class="container-fluid" @submit.prevent="onSubmit">
      <div class="col-lg-10 offset-md-1" style="height:auto;">
        <h4>Ministry of Health</h4>
        <h1>COVID 19(CORONA VIRUS)</h1>
        <h4>Virus-Test Registration Form</h4>
        <div class="row">
          <div class="col">
            <div class="form-field">
              <label>Surname <span class="required">*</span></label>
              <input name="surname" id="surname" v-model.trim="surname" />
              <small
                class="error"
                v-for="(error, index) of v$.surname.$errors"
                :key="index"
              >
                {{ error.$property }} {{ error.$message }}
              </small>
            </div>
          </div>
          <div class="col">
            <div class="form-field">
              <label>Given Name <span class="required">*</span></label>
              <input name="givenName" id="givenName" v-model.trim="givenName" />
              <small
                class="error"
                v-for="(error, index) of v$.givenName.$errors"
                :key="index"
              >
                {{ error.$property }} {{ error.$message }}
              </small>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col">
            <div class="form-field">
              <label>Date of Birth <span class="required">*</span></label>
              <input name="dob" id="dob" type="date" v-model.trim="dob" />
              <small
                class="error"
                v-for="(error, index) of v$.dob.$errors"
                :key="index"
              >
                {{ error.$property }} {{ error.$message }}
              </small>
            </div>
          </div>
          <div class="col">
            <label>Place of Residence <span class="required">*</span></label>
            <div class="form-field">
              <input name="residence" id="residence" v-model.trim="residence" />
              <small
                class="error"
                v-for="(error, index) of v$.residence.$errors"
                :key="index"
              >
                {{ error.$property }} {{ error.$message }}
              </small>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col">
            <label>Occupation <span class="required">*</span></label>
            <div class="form-field">
              <input
                name="occupation"
                id="occupation"
                v-model.trim="occupation"
              />
              <small
                class="error"
                v-for="(error, index) of v$.occupation.$errors"
                :key="index"
              >
                {{ error.$property }} {{ error.$message }}
              </small>
            </div>
          </div>
          <div class="col">
            <div class="form-field">
              <label>Nationality <span class="required">*</span></label>
              <input
                name="nationality"
                id="nationality"
                v-model.trim="nationality"
              />
              <small
                class="error"
                v-for="(error, index) of v$.nationality.$errors"
                :key="index"
              >
                {{ error.$property }} {{ error.$message }}
              </small>
            </div>
          </div>
        </div>
        
          <h6 style="margin:20px 0 -10px 0; text-align:left;  font-weight: bolder;">Gender</h6>
     

        <hr />
        <div style="margin-top:-10px;">
          <div class="form-check">
            <input
              class="form-check-input"
              type="radio"
              name="gender"
              id="gender"
              checked
            />
            <h6 class="form-check-label" for="flexRadioDefault1">Male</h6>
          </div>
          <div class="form-check" style="margin-left: 70px;">
            <input
              class="form-check-input"
              type="radio"
              name="gender"
              id="gender"
            />
            <h6 class="form-check-label" for="flexRadioDefault2">Female</h6>
          </div>
        </div>
        <div class="form-row" style="margin-top:50px;">
          <div class="col form-group">
            <label>Category</label>
            <select name="select" id="select">
              <option value="none" selected disabled hidden
                >--Select Category--</option
              >
              <option></option>
            </select>
          </div>
        </div>
      </div>
      <div class="form-row" style="margin:10px 0;">
        <div class="col form-group">
          <center>
            <button class="btn btn-danger btn-lg" type="submit">
              Submit
            </button>
          </center>
        </div>
      </div>
    </form>
  </div>
</template>

<script>
import useVuelidate from "@vuelidate/core";
import { required, minLength } from "@vuelidate/validators";
// const alpha = helpers.regex("alpha", /^[a-zA-Z]+$/);
export default {
  name: "Patients",
  props: {
    msg: String,
  },
  setup() {
    return { v$: useVuelidate() };
  },
  data() {
    return {
      surname: "",
      givenName: "",
      dob: "",
      residence: "",
      occupation: "",
      nationality: "",
    };
  },
  validations() {
    return {
      surname: { required, minLength: minLength(4) },
      givenName: { required, minLength: minLength(4) },
      residence: { required },
      occupation: { required },
      dob: { required },
      nationality: { required },
    };
  },
  methods: {
    onSubmit: function() {
      this.v$.$touch();
      if (this.v$.$error) return;
      alert("Form is valid");
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.body {
  border: 1px solid;
  margin: 30px 300px;
  height: auto;
}

.b_image {
  width: 100%;
  height: 80px;
}

.resize {
  text-align: center;
  height: 80px;
  width: 80px;
  margin-left: 25px;
}

.col input,
select {
  padding: 5px 12px 10px 12px;
  /* border: 1px solid rgb(71, 71, 71); */
  border-radius: 2px;
  margin-bottom: 0px;
  margin-top: 0px;
  width: 100%;
  box-sizing: border-box;
  box-shadow: inset 0 4px 4px 0 rgb(0 0 0 / 10%);
  background-color: #fafbfc;
  font-size: 14px;
  letter-spacing: 1px;
}

input:focus,
select:focus {
  /* -moz-box-shadow: none !important;
    -webkit-box-shadow: none !important; */
  /* box-shadow: inset rgb(158, 158, 158) !important; */
  border: 1px solid #304ffe;
  outline-width: 0;
}
select {
 
  text-align-last: center;
  /* webkit*/
}
option {
  text-align: center;
}

h4 {
  font-size: 14px;
  text-align: center;
  margin-left: 23px;
}

h1 {
  font-size: 21px;
  text-align: center;
  font-weight: bolder;
}

.form-check {
  float: left;
}
label {
  font-weight: bolder;
  text-align: left !important;
  float: left;
}
small{
  color: red;
    float: left;
}
</style>
