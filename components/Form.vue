<template>
  <section class="faq-one" id="form">
    <div class="container">
      <!-- /.block-title -->
      <div class="pt-5">
        <div class="block-title text-center">
          <h2 class="block-title__title">
            Fill the form to activate your free trial
          </h2>
          <!-- /.block-title__title -->
        </div>
        <div class="border-bg1 col-sm-12 col-xs-12 offset-md-2 col-md-8">
          <div class="">
            <form
              action="#"
              data-url="https://xyz.us18.list-manage.com/subscribe/post?u=20e91746ef818cd941998c598&amp;id=cc0ee8140e"
            >
              <div class="reply-form">
                <div class="vx-col w-1/2 mt-4">
                  <input
                    type="email"
                    id="mc-email"
                    class="reply-form__field"
                    placeholder="Email address"
                  />
                </div>
                <div class="vx-col w-1/2 mt-4">
                  <input
                    type="email"
                    class="reply-form__field"
                    placeholder="Business Email address"
                  />
                  <span
                    >Your business email address will be your Bip it
                    username.</span
                  >
                </div>
                <div class="vx-col w-1/2 mt-4">
                  <input
                    type="text"
                    class="reply-form__field col-12"
                    placeholder="Company name"
                  />
                  <span
                    >If you don’t have a company yet, you can use the name of
                    your project.</span
                  >
                </div>

                <div class="mt-4">
                  <label class="vs-input--label"
                    >{{ "Company’s operating hours" }}
                  </label>
                  <div class="row">
                    <div class="col-6">
                      <b-form-timepicker
                        v-model="value"
                        locale="en"
                        class="reply-form__field"
                      />
                    </div>
                    <div class="col-6">
                      <b-form-timepicker
                        v-model="value"
                        locale="en"
                        class="reply-form__field"
                      />
                    </div>
                  </div>
                </div>
              </div>

              <div class="vx-col w-1/2 mt-4">
                <!-- <label class="vs-input--label"
                  >{{ "Opening Days" }} <span class="red">*</span></label
                > -->
                <v-select
                  v-validate="'required'"
                  multiple
                  v-model="selected"
                  :options="options"
                  name="opening_days"
                  class="reply-form__field"
                  :placeholder="'Company’s opening days'"
                />
                <!-- <span
                class="text-danger text-sm"
                v-show="errors.has('opening_days')"
                >{{ errors.first("opening_days") }}</span
              > -->
              </div>
              <div class="reply-form">
                <div class="vx-col w-1/2 mt-4">
                  <input
                    v-model="number"
                    type="text"
                    @input="acceptNumber"
                    class="col-12 reply-form__field"
                    placeholder="Contact Number"
                  />
                  <span
                    >Your contact number will be added to your booking
                    page.</span
                  >
                </div>
                <div class="row text-center">
                  <div
                    class="col-offset-lg-3 col-offset-md-3 col-sm-12 col-xs-12 mt-4"
                  >
                    <button class="reply-form__btn thm-btn" type="submit">
                      <span>Submit </span>
                    </button>
                  </div>
                </div>
              </div>
            </form>

            <!-- /.mailchimp-one__mc-form -->
          </div>
          <!-- /.accrodion-inner -->
        </div>
      </div>
    </div>
    <!-- /.container -->
  </section>
</template>

<script>
import vSelect from "vue-select";
import "vue-select/dist/vue-select.css";
import { BFormTimepicker } from "bootstrap-vue";
export default {
  name: "Form",
  components: {
    "v-select": vSelect,
  },
  data() {
    return {
      number: "",
      value: "",

      selected: "",
      options: ["Monday - Friday ", "Monday - Saturday", "None of the above"],
    };
  },
  methods: {
    acceptNumber() {
      var x = this.number
        .replace(/\D/g, "")
        .match(/(\d{0,3})(\d{0,3})(\d{0,4})/);
      this.number = !x[2]
        ? x[1]
        : "(" + x[1] + ") " + x[2] + (x[3] ? "-" + x[3] : "");
    },
  },
};
</script>

<style scoped>
.border-bg {
  border: 2px solid #ff4eb5 !important;
}
.border-bg1 {
  border-top: 2px solid #ffa065 !important;
  border-left: 2px solid #ff4eb5 !important;
  border-bottom: 2px solid #ff4eb5 !important;
  border-right: 2px solid #ff4eb5 !important;
  padding-bottom: 2rem;
  padding-top: 1rem;
  border-radius: 20px;
}

.mailchimp-one__mc-form {
  height: auto !important;
}
.mailchimp-one__mc-form input {
  padding: 10px;
}
.p-10 {
  padding: 10px;
}

.reply-form input {
  margin-bottom: 0px !important;
}
</style>
