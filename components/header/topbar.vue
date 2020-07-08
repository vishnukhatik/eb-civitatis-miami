<template>
  <div id="top-bar">
    <v-app-bar color="white" dense>
      <v-toolbar-title>
        <div class="eb-logo">
          <a href="/" title="Miami by CIVITATIS">
            <span class="eb-header__logo__civitatis">Civitatis</span>
          </a>
          <a href="/" title="Miami by CIVITATIS">
            <span class="eb-header__logo__city">Miami</span>
          </a>
        </div>
      </v-toolbar-title>

      <v-spacer></v-spacer>

      <div class="">
        <ul class="flex flex-wrap">
          <li class="eb-lang">
            <div
              class="eb-top-dropdown-header flex justify-center items-center"
            >
              <!-- <span class="--abbr">ES</span> -->
              <span class="--long">English</span>
            </div>
            <div class="eb-top-dropdown-body">
              <ul>
                <li>
                  <a href="#" data-value="ES">Spanish</a>
                </li>
                <li><a href="#" data-value="FR">French</a></li>
                <li>
                  <a href="#" data-value="IT">Italian</a>
                </li>
                <li>
                  <a href="#" data-value="PT">Portuguese</a>
                </li>
              </ul>
            </div>
          </li>
          <li class="eb-dropdown-currency">
            <div
              class="eb-top-dropdown-header flex justify-center items-center"
            >
              <!-- <span class="--abbr">ES</span> -->
              <span style="font-size: 21px;">£</span>
            </div>
            <div class="eb-top-dropdown-body">
              <ul>
                <li>
                  <span
                    data-value="EUR"
                    data-abbreviation="€"
                    class="a-currency-icon--euro"
                    >Euro</span
                  >
                </li>
                <li>
                  <span data-value="USD" data-abbreviation="US$"
                    >United States dollar</span
                  >
                </li>
                <li>
                  <span
                    data-value="GBP"
                    data-abbreviation="£"
                    class="a-currency-icon--pound"
                    >Pound sterling</span
                  >
                </li>
                <li>
                  <span data-value="BRL" data-abbreviation="R$"
                    >Brazilian real</span
                  >
                </li>
                <li>
                  <span data-value="MXN" data-abbreviation="MXN"
                    >Mexican peso</span
                  >
                </li>
                <li>
                  <span data-value="COP" data-abbreviation="COP"
                    >Colombian peso</span
                  >
                </li>
                <li>
                  <span data-value="ARS" data-abbreviation="ARS"
                    >Argentine peso</span
                  >
                </li>
                <li>
                  <span data-value="CLP" data-abbreviation="CL$"
                    >Chilean peso</span
                  >
                </li>
                <li>
                  <span data-value="PEN" data-abbreviation="S/"
                    >Peruvian sol</span
                  >
                </li>
              </ul>
            </div>
          </li>
          <li class="eb-dropdown-user">
            <div class="eb-top-dropdown-header">
              <!-- <span class="--abbr">ES</span> -->
              <feather type="user"></feather>
            </div>
          </li>
          <li class="eb-dropdown-help">
            <div class="eb-top-dropdown-header">
              <!-- <span class="--abbr">ES</span> -->
              <feather type="help-circle"></feather>
            </div>
            <div class="eb-top-dropdown-body">
              <ul>
                <li>
                  <a href="#" data-value="ES">FAQs</a>
                </li>
                <li><a href="#" data-value="FR">Contact Civitatis</a></li>
              </ul>
            </div>
          </li>
          <li class="eb-dropdown-cart eb-dropdown-help">
            <div class="eb-top-dropdown-header">
              <!-- <span class="--abbr">ES</span> -->
              <feather type="shopping-cart"></feather>
            </div>
            <div class="eb-top-dropdown-body">
              <ul>
                <li>
                  <a href="#" data-value="ES">Your shopping basket is empty</a>
                </li>
              </ul>
            </div>
          </li>
        </ul>
        <!-- <feather type="user"></feather> -->
      </div>
    </v-app-bar>
  </div>
</template>
<script>
export default {
  data() {
    return {
      dropdown_font: ['Spanish', 'French', 'Italian', 'Portuguese'],
    }
  },
}
</script>
<style>
#top-bar .eb-header__logo__civitatis {
  color: #f70759;
}
#top-bar .eb-header__logo__city {
  color: #1c1a1a;
}
#top-bar .v-toolbar__content {
  height: 67px !important;
}
#top-bar .v-app-bar {
  height: 67px !important;
  box-shadow: none !important;
}
/* #top-bar .eb-logo {
  width: 8%;
} */
#top-bar .v-application--is-ltr .v-text-field .v-input__append-inner {
  margin-left: 0px !important;
}
#top-bar .eb-lang,
#top-bar .eb-dropdown-currency {
  list-style: none;
  position: relative;
}
#top-bar .eb-top-dropdown-body > ul li,
.eb-top-dropdown-header,
.o-page-nav__element {
  font-size: 1rem;
}
#top-bar .eb-top-dropdown-header,
#top-bar .eb-dropdown-help .eb-top-dropdown-header {
  position: relative;
  height: 4.2rem;
  border-bottom: 0;
  padding: 0 1.25rem;
  color: #999;
  line-height: 2.6875;
  cursor: pointer;
  z-index: 11;
  font-size: 1rem;
  transition: background-color 0.3s;
}

#top-bar .eb-top-dropdown-header:hover .eb-top-dropdown-body {
  display: block;
}
#top-bar .eb-top-dropdown-header::after {
  content: '⌄';
  font-size: 25px;
  margin-top: -7px;
}
#top-bar .eb-top-dropdown-header:hover {
  background: #000;
  color: #fff;
}
#top-bar .eb-top-dropdown-header i {
  font-weight: 600;
  font-size: 21px;
}
#top-bar .eb-top-dropdown-body > ul li,
#top-bar .eb-dropdown-help.eb-top-dropdown-body > ul li .eb-top-dropdown-header,
.o-page-nav__element {
  position: relative;
  width: 100%;
  padding: 10px;
  font-weight: 300;
  color: #fff;
  line-height: 1;
  font-size: 15px;
  color: #807578;
}
#top-bar ul li:hover .eb-top-dropdown-body {
  display: block;
}
#top-bar .eb-top-dropdown-body {
  display: none;
  width: 100%;
  position: absolute;
  background-color: #fff;
  padding: 10px;
  font-size: 1.125rem;
  z-index: 10;
  box-shadow: 0 4px 10px 1px rgba(0, 0, 0, 0.2);
  left: 0%;
  top: 100%;
}
#top-bar .eb-top-dropdown-body ul {
  margin: 0;
  overflow: hidden;
  line-height: inherit;
  display: block;
  padding-left: 0px !important;
}
#top-bar .eb-top-dropdown-body ul li a {
  color: #807578;
}
/* currency dropdown */
#top-bar .eb-dropdown-currency .eb-top-dropdown-body {
  width: 55.8125rem;
  right: 0% !important;
  top: 100%;
  left: auto;
}
#top-bar .eb-dropdown-currency .eb-top-dropdown-body > ul li {
  max-width: 25%;
  float: left;
}
#top-bar .eb-dropdown-currency .eb-top-dropdown-body > ul li span:before {
  position: absolute;
  left: 0;
  top: calc(50% - 0.5rem);
  content: attr(data-abbreviation);
  color: #ccc;
  display: block;
  width: 4.375rem;
  text-align: center;
  font-weight: 500 !important;
  font-family: Montserrat, arial, sans-serif;
  font-size: 1rem;
  line-height: 1;
  margin-right: 0;
}
#top-bar .eb-dropdown-currency .eb-top-dropdown-body > ul li span {
  padding: 0 0 0 4.375rem;
}
/* user dropdown */
#top-bar .eb-dropdown-user .eb-top-dropdown-header::after {
  content: '';
}
/* help dropdown */
#top-bar .eb-dropdown-help .eb-top-dropdown-header::after {
  content: '';
}
#top-bar .eb-dropdown-help .eb-top-dropdown-body {
  width: 13.8125rem;
  right: 4.7% !important;
  left: auto;
  top: 97%;
}
#top-bar .eb-dropdown-cart .eb-top-dropdown-body {
  right: 1% !important;
}
#top-bar .eb-dropdown-help .eb-top-dropdown-body ul li {
  text-align: right;
}
/* cart dropdown */
</style>
